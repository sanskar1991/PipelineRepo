pipeline {
  agent any
  
  stages {
    stage('build') {
      steps {
        sh 'pip install -r requirements.txt'
      }
    }
    stage('test') {
      steps {
        sh 'pytest test_Calculator.py -v'
      }   
    }
  }
}