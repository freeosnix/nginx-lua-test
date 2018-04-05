pipeline {
    agent { dockerfile true }
    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker build -t lazzo/nginx-lua-test .'
            }
        }
    }
}
