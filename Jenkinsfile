pipeline {
  agent any
  stages {
    stage('Test') {
      agent {
        docker {
          image 'php'
        }

      }
      steps {
        sh 'php --v'
      }
    }
  }
}