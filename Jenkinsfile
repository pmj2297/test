pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'build .NET file'
          }
        }

        stage('Test') {
          steps {
            echo 'testing the .NET file'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'depoying the application'
      }
    }

  }
}