pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat 'docker build -t flask-app -f dockerfile .'
            }
        }

    }
}