properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'python3 main.py'
            }
        }
    }
}
