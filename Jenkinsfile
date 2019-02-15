Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'gradle:5.0' } }
    stages {
        stage('build') {
            steps {
                sh 'gradle --show-version'
            }
        }
    }
}