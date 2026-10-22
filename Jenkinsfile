pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls'
            }
        }

        stage('Test') {
            steps {
                sh 'pwd'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cd Task1 && docker compose up -d --build'
            }
        }
    }
}
