@Library('sharedlib') _
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh(libraryResource('list.sh'))
                echo libraryResource('input.json')
            }
        }
    }
}