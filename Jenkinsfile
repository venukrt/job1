node{
	stage('SCM Checkout'){
		git 'https://github.com/venukrt/job1.git'
	}
	stage('compile-source'){
		sh 'mvn clean compile'
	}
	
	stage('Test the code'){
		sh 'mvn test'
	}
	stage('Package'){
		sh 'mvn package'
	}
	





}
