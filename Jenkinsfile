pipeline {
  agent {
    docker {
      image 'python'
    }

  }
  stages {
    stage('test') {
      steps {
        sh 'pytest .'
      }
    }
    stage('log success') {
      steps {
        echo 'success'
      }
    }
  }
}