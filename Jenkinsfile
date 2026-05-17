pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                echo 'Fetching source code from GitHub'
            }
        }

        stage('Build Docker Images') {
            steps {
                echo 'Building frontend and backend Docker images'
            }
        }

        stage('Push Docker Images') {
            steps {
                echo 'Pushing images to Azure Container Registry'
            }
        }

        stage('Deploy to AKS') {
            steps {
                echo 'Deploying microservices to AKS cluster'
            }
        }
    }
}
