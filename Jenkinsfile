pipeline {
    agent any

    stages {
        stage('Clone GitHub Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/zaynab44/coffee-website.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the coffee website...'
                // Example: run npm install or python build
                // sh 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the coffee website...'
                // Add deployment steps here
            }
        }
    }
}
