pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed'
      }
    }

    stage('Test') {
      parallel {
        stage('Test1') {
          steps {
            echo 'Test1 Completed'
          }
        }

        stage('Test2') {
          steps {
            echo 'Test2'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Completed'
      }
    }

  }
}