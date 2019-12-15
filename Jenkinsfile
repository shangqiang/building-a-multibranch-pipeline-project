pipeline {
    agent {
        image 'node:10'
        args '-p 8081:8000'
    }
    stages {
        stage('Build') {
            steps {
                sh 'node -v'
            }
        }
    }
}
