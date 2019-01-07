pipeline {
	agent {
		node {
			label 'master'
		}
	}
	environment {
		GOROOT = "${HOME}/go"
	}

	stages {
		stage('Build') {
			steps {
				echo 'make ep11server'
			}
		}
	}
}
