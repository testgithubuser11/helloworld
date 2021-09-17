pipeline {
  agent any
  stages {
    stage('teststage1') {
      parallel {
        stage('teststage1') {
          steps {
            echo 'Hello this is test step 1'
          }
        }

        stage('teststage 2') {
          steps {
            sh 'echo \'this is test stage 2\''
          }
        }

      }
    }

  }
}