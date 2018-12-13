pipeline {
  agent any
  stages {
    stage('Hello world') {
      agent {
        docker {
          image 'library/hello-world'
        }

      }
      steps {
        sh 'echo hello world'
      }
    }
  }
}