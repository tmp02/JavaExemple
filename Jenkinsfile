Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'maven:3.6.1' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}