
pipeline {
  agent any
  stages {
    stage (test){
      steps {
        echo "test"
      }
    }
    stage (test1){
      steps {
        sh "ls -la"
      }
    }
    stage (test2){
      steps {
        sh "cat index.html"
      }
    }
  }
}
