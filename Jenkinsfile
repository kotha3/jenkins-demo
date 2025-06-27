pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                echo 'Cloning GitHub Repo...'
            }
        }
        stage('Run Script') {
            steps {
                sh 'chmod +x hello.sh'
                sh './hello.sh'
            }
        }
    }
}
