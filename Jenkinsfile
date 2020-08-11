pipeline {
    agent {
    	label 'freebsd_12_1'
    }
	stages {
		stage('Install Dependencies') {
			steps {
				sh 'echo "Install Dependencies Here"'
			}
		}
		stage('Build') {
			steps {
				 sh 'echo "Build Here"'	
			}
		}
        stage('Unit Tests') {
			steps {
				sh 'echo "Unit Tests Here"'
			}
		}
		stage('Publish') {
			steps {
				sh 'echo "Publish Here"'
			}
		}
    }
}
