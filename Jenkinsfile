@Library('library')

import static com.guillermow90.devops.Stage.*

pipeline {
  agent any

  stages {
    stage('Compilación') {
      steps {
        script {
          //sendSlackStageMessage(this)
          buildMaven(this)
        }
      }
    }


  }


}
