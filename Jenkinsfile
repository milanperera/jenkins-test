pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                sh 'cd pushwoosh; mvn clean install'
		sh 'cd Maritz; mvn clean install'
            }
        }
    }
}
