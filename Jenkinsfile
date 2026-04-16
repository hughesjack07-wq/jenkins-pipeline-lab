pipeline {
    agent any

    environment {
        COMPANY_NAME = "University of Galway"
    }

    stages {
        stage('Build') {
            steps {
                echo "Building the application for ${env.COMPANY_NAME}..."
            }
        }
        stage('Test') {
            steps {
                echo "Running tests for ${env.COMPANY_NAME}..."
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying the project to the server..."
            }
        }
    }
}
