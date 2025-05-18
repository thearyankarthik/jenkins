pipeline {
  agent { 
    label 'docker-agent-alpine' 
  }
  stages {
    stage('Checkout & Run') {
      steps {
        checkout scm  // Checks out code from Git
        bat 'python helloworld.py'  // Runs Python script
      }
    }
  }
}
