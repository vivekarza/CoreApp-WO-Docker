pipeline {
  agent any
  stages {
    stage('git checkout') {
      steps {
        git(url: 'https://github.com/vivekarza/CoreApp-WO-Docker.git', branch: 'dev', credentialsId: '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')
      }
    }

  }
}