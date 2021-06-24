pipeline {
  agent any
  tools {nodejs "node"}
  stages {
    stage('Cloning Git') {
      steps {
        git 'https://github.com/gautam43/nodejs-ex.git'
      }
    }
    stage('Install dependencies') {
      steps {
        sh 'npm install'
      }
    }
  }
}
