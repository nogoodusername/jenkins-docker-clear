pipeline {
  agent any
  stages {
    stage ('Initialize') {
      steps {
        echo 'Clearing Docker System'
      }
    }
    stage ('Clear') {
      steps {
        sh 'docker system prune -af'
      }
    }
  }
}
