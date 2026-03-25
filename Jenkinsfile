pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Run App') {
            steps {
                sh 'node index.js'
            }
        }
    }
}
