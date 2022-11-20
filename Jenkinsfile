pipeline {
    agent any

    stages {
        stage('Git checkout') {
            steps {
                git branch: 'jawher', credentialsId: '27f3931f-c071-4b49-abb5-84698cb54e78', url: 'https://github.com/Farouk-Belhassine/DevOps-first-project.git'
            }
        }
    }
}