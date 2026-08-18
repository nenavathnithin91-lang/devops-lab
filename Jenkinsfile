pipe line {
  agent any
  stages {
    stages('compile') {
      steps {
        sh 'python3 HelloWorld.py'
      }
    }
    stages('run'){
      steps{
        sh 'python HelloWorld'
      }
    }
  }
}
