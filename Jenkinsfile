pipeline {
  agent {
    docker { image 'node:16.3-alpine' }
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install --save'
      }
    }
  }
}
