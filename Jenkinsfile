pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Building Step'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing Step'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployment. Complete'
      }
    }

  }
}