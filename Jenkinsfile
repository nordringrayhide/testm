pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Building ...'
        sh 'echo "Hello world"'
      }
    }
    stage('test') {
      steps {
        echo 'Testing ...'
      }
    }
    
    stage('deploy') {
      steps {
        step {
          echo 'Deploing ...'
        }
      }
    }
  }
}
