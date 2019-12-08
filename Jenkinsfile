pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'sh "mvn clean"'
      }
    }

    stage('Test') {
      steps {
        sh 'sh "mvn  test"'
      }
    }

  }
}