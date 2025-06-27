pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'development', url: 'https://github.com/karthikdevarkonda/GeneralSpringBootProgExce.git'
                sh 'mvn clean package'
            }
        }
    }
}
