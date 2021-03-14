pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
                sh 'sleep 5'
            }
        }
        
        stage('testing')
        {
            steps {
                sh 'echo "Testing to build"'
                sh 'sleep 10'
                
            }
        }
         stage('deployment')
        {
            steps {
                sh 'echo "deploy to build"'
                sh 'sleep 11'
            }
        }
    }
}
