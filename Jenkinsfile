pipeline {
 agent any
 stages {
 stage ('Build') {
 steps {
 echo 'Running build automation'
 sh './gradlew build --no-d'
 archiveArtifacts artifacts: 'dist/trainSchedule.zip'
 }
 }
 }
 }
