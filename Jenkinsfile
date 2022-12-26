pipeline {
    agent { docker { image 'python:3.10-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'pip list'
            }
        }
    }
}
