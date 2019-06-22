pipeline {
    agent {slave1}
    stages{
        stage('START'){
            steps {
                sh 'ECHO NEW EXECUTION'
            }
            post {
                success {
                    echo 'Now Archiving...'
                }
            }
        }
		stage('BUILD'){
            steps {
                sh 'ECHO REALIZANDO BUILD'
				
            }
            
        }
    }
}