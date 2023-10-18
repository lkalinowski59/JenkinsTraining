pipeline {
  agent {
    node {
      label 'noeud 2'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'whoami'
      }
    }

    stage('network') {
      steps {
        sh 'ifconfig'
      }
    }

  }
}