properties([[$class: 'GithubProjectProperty', displayName: '', projectUrlStr: 'https://github.com/vasuramisetti/task5git.git/'], pipelineTriggers([githubPush()])])

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'ls -l'
                dir ('foo') {
                 writeFile file:'dummy', text:''
                 }
                }
               }
                stage('Test') {
                 steps {
                  sh 'ls -l'
                  }
                 }
                 stage('Deploy') {
                  steps {
                       echo 'Hello World'
			 build job:'jobb'
                       }
                      }
                     }
                    }
