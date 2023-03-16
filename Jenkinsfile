pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        echo 'echo "This is build number $BUILD_NUMBER of job $DEMO"'
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}