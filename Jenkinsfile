pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'ubuntu'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'apt-get install build-essentials make cmake'
      }
    }
  }
  environment {
    myname = 'value'
  }
}