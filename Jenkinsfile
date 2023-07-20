pipeline {
  agent {
    node {
      label 'Node-Ritesh'
    }

  }
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/riteshakadu/demo-git.git', branch: 'main', poll: true)
      }
    }

    stage('Build Code') {
      steps {
        sh 'echo "Build is Successful"'
      }
    }

  }
}