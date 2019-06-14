node {
    checkout scm
}
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'make'
            }
        }
    }
}
