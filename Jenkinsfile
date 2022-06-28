pipeline {
    agent any 
    stages{
        stage('fetch code'){
            steps{
                git branch: 'master' , url: 'https://github.com/hvnischith/jenkins-git-integration.git' 
            }
            }
        stage('build'){
            steps{
                sh 'mvn clean install'
            }
        }
    }
}
