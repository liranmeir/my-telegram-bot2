pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/liranmeir/my-telegram-bot2.git', branch: 'master', changelog: true, credentialsId: 'liranmeir', poll: true)
      }
    }
    stage('Build') {
      steps {
        sh 'echo "hello"'
      }
    }
  }
}