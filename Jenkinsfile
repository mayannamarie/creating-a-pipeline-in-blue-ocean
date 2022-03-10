pipeline {
  agent {
    docker {
      image 'node:15-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      parallel {
        stage('Build ') {
          steps {
            sh 'npm install'
            sh 'npm install'
          }
        }

        stage('Build') {
          steps {
            sh 'npm install'
          }
        }

      }
    }

  }
}