pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                script {
                    git branch: 'main', credentialsId: 'test-jenkins-id', url: 'https://github.com/longnguyen97-full/hello-jenkins.git'
                }
            }
        }
    }
}
