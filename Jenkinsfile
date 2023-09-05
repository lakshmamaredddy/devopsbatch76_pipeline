pipeline {
  agent any
  stages {
    stage('Plan') {
      steps {
        echo 'i have a plan to work on ci/cd pipeline'
      }
    }

    stage('Code') {
      steps {
        echo 'i have code to work on ci/cd pipeline'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'i have Build to work on ci/cd pipeline'
          }
        }

        stage('Test') {
          steps {
            echo 'i have a test to work on ci/cd pipeline'
          }
        }

        stage('Release') {
          steps {
            echo 'i have a release to work on ci/cd pipeline'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I  have a deploy to work on ci/cd pipeline'
          }
        }

        stage('Operate') {
          steps {
            echo 'i have operate to work on ci/cd pipe line'
          }
        }

      }
    }

  }
}