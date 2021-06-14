pipeline {
    agent any
    stages {
        stage('first'){
            steps{
                git 'https://github.com/kfir-mobilebrain/testingpipline.git'
            }
        }
        stage('something'){
            steps{
                sh 'app.py'
            }
        }
    }
}
