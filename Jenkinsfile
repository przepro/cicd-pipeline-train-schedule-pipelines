pipeline {
  agent any
  stages {
    stage ('BUild') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
