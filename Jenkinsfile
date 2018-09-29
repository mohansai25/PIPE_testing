pipeline {
    agent any

    stages { 
	stage('git') {
            steps {
                git 'https://github.com/mohansai25/PIPE_testing.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
