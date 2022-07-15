pipeline {
    agent any

    stages {
        stage('scp') {
            steps {
                sh 'scp /var/lib/jenkins/workspace/devops/*.html ansible@ansible:/opt/ '
            }
        }
        stage('finshed') {
            steps {
                echo 'Hello World'
            }
        }
    }
}

