pipeline {
    agent {
        docker {
            image 'python:3.10.7-alpine' }
    }
    stages {
        stage('build') {
            steps {
                label 'mylabel'
                sh 'python --version'
            }
        }
    }
}
