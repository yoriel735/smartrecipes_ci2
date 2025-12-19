pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Compilando...'
            }
        }
        stage('Test') {
            steps {
                echo 'Ejecutando tests...'
            }
        }
    }
}
