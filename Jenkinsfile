pipeline {
  agent any
  stages {
    stage('Machine Clean Up') {
      steps {
        parallel(
          "LvNgInstaller13": {
            echo 'Cleaning ...'
            
          },
          "LvNgInstaller15": {
            echo 'Cleaning...'
            
          }
        )
      }
    }
  }
}