pipeline {
    agent {
        label 'docker-agent'
    }

    stages {
        stage('Test') {
            steps {
                sh 'echo Running on Docker Agent'
                sh 'sleep 120'
                sh 'echo Finished'
            }
        }
    }
}
