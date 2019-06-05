pipeline {
	agent {
		docker { image 'ubuntu:latest' }
	}
	stages {
		stage('checkout') {
			steps {
				sh 'echo "Hello World"'
			}
		}
	}
}