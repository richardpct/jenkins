pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        sh '''
          set -eux
          pwd
          ls -la
        '''
      }
    }
    stage('Test') {
      steps {
        sh 'echo "running tests..." && sleep 1'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "deploy step..."'
      }
    }
  }
