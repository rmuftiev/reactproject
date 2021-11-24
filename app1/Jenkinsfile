pipeline {

  agent any

  tools {nodejs "node"}

  stages {

    stage('Install dependencies') {

      steps {

        cd app1
        sh 'npm install'

      }

    }

     

    stage('Test') {

      steps {

        sh 'npm test'

      }

    }

  }

}

