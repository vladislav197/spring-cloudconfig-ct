pipeline {
  agent any
  stages {
    stage('Stage1') {
      agent any
      environment {
        Demo = '1'
      }
      steps {
        sh 'echo \'This is build $BUILD_NUMBER of demo $Demo\''
      }
    }

  }
}