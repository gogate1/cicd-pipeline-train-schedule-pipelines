pipeline {

agent any

stages { 

stage ('build') {

 steps {
    
    echo 'starting build automation'
    sh './gradlew build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
 }
}
} 
}
