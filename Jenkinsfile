pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'cd HighScoresServiceClient & mvn install'
      }
    }
  }
}