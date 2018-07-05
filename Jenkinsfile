pipeline {
  agent any
  stages {
    stage('Git') {
      steps {
        script {
          version = ${GIT_COMMIT}
        }
        echo "${version}"
      }
    }
  }
}
