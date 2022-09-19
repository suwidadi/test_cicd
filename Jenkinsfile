pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/suwidadi/test_cicd', branch: 'dev')
      }
    }

    stage('') {
      steps {
        sh 'ls -la'
      }
    }

  }
}