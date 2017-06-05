pipeline {
  agent any
  stages {
    stage('input') {
      steps {
        input(message: 'confirm deployment', ok: 'go')
        echo 'going on.'
      }
    }
  }
}