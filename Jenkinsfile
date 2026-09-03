pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the application...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                bat 'if not exist "C:\\Deployments\\DemoApp" mkdir "C:\\Deployments\\DemoApp"'
                bat 'copy index.html "C:\\Deployments\\DemoApp\\index.html"'
            }
        }
    }
}
