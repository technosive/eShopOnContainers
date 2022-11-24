pipeline {
  agent any
  stages {
    stage('inital') {
      steps {
        echo 'Test build'
      }
    }

    stage('Build') {
      steps {
        sh 'Dotnet build'
      }
    }

  }
}