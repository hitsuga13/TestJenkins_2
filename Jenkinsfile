pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/hitsuga13/TestJenkins_2', branch: 'main')
      }
    }

    stage('error') {
      steps {
        sh 'ls -la'
      }
    }

  }
}