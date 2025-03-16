pipeline {
    agent {
        docker { image 'node:18'}
    }
    stages {
        stage('Build') {
            steps {
                echo 'third try...'
            }
        }
        stage('Test') {
            steps{
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}