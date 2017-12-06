#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/mamathaawsdevops/mamatha1.git'],
    pipelineTriggers([githubPush()])])
pipeline {
     agent any
 stages {
        stage('Build') { 
            steps { 
              echo "first step one"
              echo "first step one"
                echo "first step one"
              echo "first step one"
            }
        }
        stage('Test'){
            steps {
               echo "second steep" 
            }
        }
        stage('Deploy') {
            steps {
                echo "third step"
            }
        }
    }
}
