pipeline {
    agent any
    stages {
        stage("clone") {
            steps {
                git branch: 'branch2', url: 'https://github.com/viswkum/devops122a.git'
            }
        }
        stage("rename") {
            steps {
                sh 'mv hdfc ICICIBANK'
            }
        }
    }
}
