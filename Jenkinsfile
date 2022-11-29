pipeline {
  agent any
  stages {
    stage ('build') {
         steps {
              sh 'bash linux'
             }
           }
    stage ('build1') {
      steps {
         sh 'bash New'
      }
    }
    stage ('test') {
      steps {
         sh 'bash tnstc'
      }
    }
    docker {image 'praveen191291/apache:latest}
  }
}
}
}

