pipeline {
  agent any
  stages {
    stage('Step1') {
      steps {
        bat '1.bat'
      }
    }
    stage('Step2') {
      steps {
        bat '2.bat'
      }
    }
    stage('') {
      steps {
        powershell '1.ps'
      }
    }
  }
  environment {
    name = 'Sathya'
  }
}