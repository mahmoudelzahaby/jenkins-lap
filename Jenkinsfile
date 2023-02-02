pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
                sh "ls"
                sh "docker ps"
            }
        }
        stage('test') {
            steps {
                echo 'test'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}
