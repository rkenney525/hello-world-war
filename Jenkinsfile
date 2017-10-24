pipeline {
    agent any
    tools {
        maven 'Maven 3.3.9'
        jdk 'Java 8'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'mvn --batch-mode install'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}