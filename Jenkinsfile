pipeline {
    agent any 
    stages {
        stage ('Build') {
          steps {
          echo 'building a maven project'
          sh './gradlew build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
          }
        }
    }
}
        
        
