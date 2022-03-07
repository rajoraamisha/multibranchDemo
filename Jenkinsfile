pipeline {
    agent any
    stages {
        stage('Master Branch Deploy Code') {
            when {
                branch 'main'
            }
            steps {
                echo "hii you are in main branch"
            }
        }
        stage('Develop Branch Deploy Code') {
            when {
                branch 'Dev'
            }
            steps {
                echo "hii you are in dev branch"
           }
        }
        stage('sit Branch Deploy Code') {
            when {
                branch 'sit'
            }
            steps {
                echo "hii you are in sit branch"
            }
        }
    }
}

