properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'ls -l'
                sh 'python main.py'
            }
        }
        stage('World') {
            steps {
                sh 'ls -l'
                sh 'python main.py'
            }
        }
    }
}
