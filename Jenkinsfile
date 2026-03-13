pipeline {
    agent any
    tools {
        maven 'MVN'
        jdk 'JDK'
    }
    stages {
        stage('clean') {
            steps {
                sh 'mvn clean'
            }
        }
        stage('test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('verify') {
            steps {
                sh 'mvn verify'
            }
        }
    }
}
