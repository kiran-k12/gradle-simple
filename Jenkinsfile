pipeline {
    agent any

    stages {
	
		stage('Build') {
	
				steps {
		                bat 'gradlew clean build'
		              }
	            }

		
		        stage('Deploy') {
				steps {
				       bat 'gradlew clean deploy'
					   bat 'echo "In cleanDeploy"'
					  }
				  }
				 	
		
				
    }
}

