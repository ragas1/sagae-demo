#!groovy

properties([
	[$class:'GithubProjectProperty',
	displayName:'',
	projectUrlStr:'https://github.com/smodalasagar/Demo_branch.git/'],
	pipelineTriggers([upstream('down'),
	githubPush()])])
///uncoment

pipeline {
	agent any

	stages {
		stage('Build') {
			steps {
				sh 'pwd'
			}
		}

		stage('Test') {
			steps {
				sh 'pwd'
			}
		}

		stage ('Deploy') {
			steps {
				sh 'java -version'
			}
		}
	}
}
