pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // TODO: Add build step
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                // TODO: Add test step
                sh './gradlew test'
            }
        }
        // Add additional stages as needed
    }
}

