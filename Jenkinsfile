pipeline {
    agent any
    stages {
        stage('first stage') {
            steps {
                sh 'echo "I am the first stage"'
            }
        }
        stage('second stage') {
            steps {
                sh 'echo "i am the second stage"'
            }
        }
        stage('third stage') {
            steps {
                sh 'echo "I am the third stage"'
            }
        }
	stage('fourth stage') {
	    steps {
		sh 'git clone https://github.com/phatinga/gradleproject.git'
	    }
	}
    }
}
