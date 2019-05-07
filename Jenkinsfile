pipeline {
	agent any

	tools {
		maven 'mvn-3.6.1'
	}

	stages {
		stage('Build') {
			steps {
				echo 'Hello worldx'
				sh "mvn clean package"
				sh "printenv"
			}
		}
	}
}
