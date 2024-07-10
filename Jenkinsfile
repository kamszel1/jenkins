pipeline {
	agent {
		docker {
			image 'python:3.9' 
		}

	stages {
		stage('Run python code') {
			steps {
				sh 'python hello.py'
			
			}
		}
	}
	}
}
