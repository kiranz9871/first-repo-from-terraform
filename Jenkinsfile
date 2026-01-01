pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'echo "checking code"'
      }
    }

    stage('build') {
      steps {
        sh '''echo "building the job"
sh ls 
sh pwd'''
      }
    }

    stage('test') {
      steps {
        echo 'build is under test'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "deploy successfully"'
      }
    }

  }
}