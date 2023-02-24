pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build completed'
        timeout(time: 5, unit: 'SECONDS'){
          sh 'sleep 10'
        }

      }
    }
    stage('Test') {
      steps {
        echo 'test completed'
      }
    }
    stage('Deploy') {
      steps {
        echo 'deploy completed'
      }
    }
  }
}