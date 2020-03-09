pipeline {
    agent any
	
    stages {
        stage('Build') {
		
            when{
              tag 1.0
            }
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
