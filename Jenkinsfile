pipeline {
    agent any
    stages {
	stage('beginning1') {
	    steps {
		echo "The first stage is happening1"
		sleep 20
		echo "The first stage is complete"
	    }
	}
	
	stage('middle') {
	    steps {
		echo "The second stage is happening"
		sleep 20
		echo "The second stage is complete"		
	    }
	}

	stage('final') {
	    steps {
		echo "The final stage is happening"
		sleep 20
		echo "The final stage is complete"		
	    }
	}	
    }
}
