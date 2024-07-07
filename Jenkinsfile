pipeline {
    agent any
    environment {
        GITHUB_TOKEN = credentials('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')
    }
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/pradeepswamyy/sihi.git', credentialsId: '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'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing sihi jenkins...'
                // Add your test steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy steps here
            }
        }
    }
}
