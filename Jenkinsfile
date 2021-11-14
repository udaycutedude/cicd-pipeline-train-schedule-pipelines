pipeline {
    agent any 
           stage ('build') {
             steps {
               echo "run build automation"
               sh './gradle build --no-daemon'
               archiveArtifacts artifacts: 'dist/trainSchedule.zip'
             }
           }
 }
