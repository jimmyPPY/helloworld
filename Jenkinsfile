pipeline {
  agent any
  stages {
    stage('Deploy WAF') {
      steps {
        echo 'Copying files'
        sh 'touch test.txt'
      }
    }
  }
  environment {
    Staging = 'Staging.ineat-conseil.fr'
  }
}