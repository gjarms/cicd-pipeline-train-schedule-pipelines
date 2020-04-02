pipeline {
agent any
stages {
  stage('Build') {
  steps {
    echo 'hello'
    sh './gradlew build --no-daemon'
    archiveArtifacts artifacts: dist/trainSchedule.zip
   }
  }
 }
}
