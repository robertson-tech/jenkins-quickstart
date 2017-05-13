pipeline {
    agent { docker '1science/sbt' }
    stages {
        stage('build') {
            steps {
                sh 'sbt version'
            }
        }
    }
}
