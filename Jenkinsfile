pileine {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-dameon'
        archiveArtificats artificats: 'dist/trainSchedule.zip'
        }
      }
    }  
  }  
