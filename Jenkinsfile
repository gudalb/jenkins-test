pipeline {
	agent any
	parameters{
		choice(name: 'DEPLOY_ENV', choices:['int', 'stage', 'prod'], description:'Target environment')
	}

	stages {
		stage('Build application'){
			agent any
			steps{
				sh 'mvn -v'
			}
		}

		stage('Deploy application'){
			agent any
			steps{
				sh 'mvn -v'
			}
		}
	}






}
