pipeline {
  agent any 
  tools {
    maven 'my_maven'
  }
  stages {
    stage('Compile') {
      steps {
        sh "mvn compile"
      }
    }
    stage('Unit test') {
      steps {
        sh "mvn test"
      }
    }
  }
}

