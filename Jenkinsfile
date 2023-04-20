/* Requires the Docker Pipeline plugin */
pipeline {
    agent any{ 
        label 'Python'
    }
    stages {
        stage('build') {
            steps {
                sh 'python3 p.py'
            }
        }
    }
}
