pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        fileExists 'kong.yaml'
      }
    }

  }
}