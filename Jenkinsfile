pipeline {
  agent {
    node {
      label 'test1'
    }

  }
  stages {
    stage('haha1') {
      steps {
        echo 'hello world'
      }
    }

    stage('haha2') {
      steps {
        echo 'test'
      }
    }

  }
  environment {
    haha1 = '123'
    haha2 = '456'
  }
}