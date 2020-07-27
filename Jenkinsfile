#!groovy

node('docker') {
  checkout scm
  stage('Build') {
    docker.image('python:2.7').inside {
      sh 'python --version'
    }
  }
}

