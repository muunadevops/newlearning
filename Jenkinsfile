pipeline {
//    agent any
    agent { docker { image 'maven:3.6.3'} }
    stages {
    stage('Build') {
        steps {
            echo "build"
            echo "test"
            echo "integration test"
        }
    }
    stage('Test') {
     steps {
         echo "build"
         echo "test"
         echo "integration test"
      }
    }
    stage('Integration Test'){
        steps {
            echo "build"
            echo "test"
            echo "integration test"
        }
    }
}
post {
    always {
        echo "i am awesome i run always"
    }
    success {
        echo "i am run only success"
    }
    failure {
        echo "i will run only failure senario"
    }
}
}