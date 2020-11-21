pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        git(url: 'https://github.com/superfrink/test-2020-11.git', branch: 'master')
        sh 'echo test'
      }
    }

  }
}