pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'g++ -o main main.cpp'
            }
        }
	stage('run'){
            steps {
                sh './main'
		sh 'pwd'
            }	
	}
    }
}