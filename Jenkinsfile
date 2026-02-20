pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Verify Git') {
            steps {
                sh 'git --version'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Running pipeline on Apple Silicon Mac"'
            }
        }
    }
}
