pipeline {
    agent any

    stages {
        stage('Node Version') {
            steps {
                script {
                    docker.image('node:24.13.0-alpine3.23').inside {
                        sh 'node --version'
                    }
                }
            }
        }
    }
}
