pipeline {
  agent {
    docker {
      image 'node'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo \'Wellcome\''
      }
    }

    stage('docker build') {
      steps {
        sh 'docker build .'
      }
    }

  }
}