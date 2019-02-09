pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        retry(count: 1) {
          sh 'echo \'hello world\''
        }

      }
    }
  }
}