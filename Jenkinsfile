pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello ${MY_NAME}!'
      }
    }
  }
  environment {
    MY_NAME = 'Kari'
  }
}