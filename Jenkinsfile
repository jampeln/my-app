pipeline {
    agent any
    stages {
        stage('clean') {
            steps {
                sh "mvn clean"
                sh "succesfully cleaned"
            }
        }
        stage('test') {
            steps {
                sh "mvn test"
            }
        }
        stage('package') {
            steps {
                sh "mvn package"
            }
        }
    }
}
