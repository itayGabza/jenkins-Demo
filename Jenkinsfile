pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'docker --version'
      }
    }

    stage('Test1') {
      parallel {
        stage('Test1') {
          steps {
            sh 'echo \'Welcome\''
          }
        }

        stage('Test2') {
          steps {
            sh 'ech4o Welcome3'
          }
        }

      }
    }

  }
}