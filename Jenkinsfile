pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('Test') {
      steps {
        sh 'node --version'
      }
    }
  }
  stages {
    stage('Test 2') {
      steps {
        sh 'node --version'
      }
    }
  }
}
