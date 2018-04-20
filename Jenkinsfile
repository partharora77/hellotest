pipeline {
  agent any
  stages {
    stage('printing1') {
      parallel {
        stage('printing1') {
          steps {
            echo 'this is to print 1.'
          }
        }
        stage('multi 1') {
          steps {
            echo 'this is to make multi branch one.'
          }
        }
      }
    }
    stage('printing 2') {
      steps {
        echo 'this is to print 2.'
      }
    }
  }
}