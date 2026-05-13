pipeline {
    agent any
       
    stages {
        stage('Hello') {
            steps {
                echo 'Hello Everybody'
            }
        }
        stage('Good Morning') {
            steps {
                echo 'Good Morning Everybody'
            }
        }
        stage('git pull') {
            steps {
                sh 'git pull origin master'
            }
        }
         stage('Display') {
            steps {
                sh 'cat file1'
            }
        }
    }
}
