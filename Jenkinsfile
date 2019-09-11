pipeline{
agent any
stages {
stage('build'){
steps  {
      echo 'running build parameter'
      sh './gradlew build --no-daeom '
      archiveArtifacts artifacts: 'dis/trainSchedule.zip'
    }
  }
 }     
}
