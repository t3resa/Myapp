pipeline {

    agent any

    stages {

        stage('Build') {
            steps{
                echo 'Building Application'}
        }

        stage('Sonar') {
            steps{
                echo 'Checking Application'}
        }

        stage('Nexus') {
            steps{
                echo 'Nexusing Application'}
        }

        stage('Depoly') {
            steps{
                echo 'Deploying Application'}
        }
    }
}