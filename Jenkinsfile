pipeline {
    agent { label 'OPENJDK' }
    stages {
        stage('git') {
            steps {
                git branch: 'main', url: 'https://github.com/krishna5683akp/js-e2e-express-server.git'
            }
        }
    }
}