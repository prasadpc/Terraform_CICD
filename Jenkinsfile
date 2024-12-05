pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch: 'main', url: 'https://github.com/prasadpc/Terraform_CICD.git'
            }
        }
        stage('init') {
            steps {
                sh 'terraform init'
            }
        }
        stage('plan') {
            steps {
                sh 'terraform plan'
            }
        }
         stage('fdkfkjkjkjkjd') {
            steps {
                sh 'terraform apply -auto-approve'
            }
        }
    }
}
