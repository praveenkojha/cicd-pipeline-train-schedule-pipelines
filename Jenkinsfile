pipeline {
  agent any 
  stage {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        achiveArtifacts artifacts" 'dist/trainSchedule.zip'
       }
    }
  }
}
