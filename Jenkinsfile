pipeline {
    agent any
    
    stages {
        state ('build') {
            steps {
                sh 'echo Compile'
            }
        }
        
        stage ('test') {
            steps {
                sh 'echo Test'
            }
        }
        
        stage ('deploy') {
            steps {
                sh 'echo Deploy'
            }
        }
    }
}
