pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git 'https://github.com/reddy-sv/jenkins-demo.git'

            }
        }

        stage('Run Script') {
            steps {
                sh 'python3 app.py'
            }
        }
    }
}
