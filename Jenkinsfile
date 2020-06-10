pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn clean install -Dlicense.skip=true'
        sh 'mvn clean install -Dlicense.skip=true'
      }
    }

  }
}