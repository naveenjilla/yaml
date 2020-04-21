pipeline {
  agent {
    label 'build-pod'
  }
  stages {
    stage('testPython') {
      steps {
        container('python') {
          script {
            sh "python -v"
          }
        }
      }
    }
  }
}
