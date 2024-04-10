pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Clone code') {
            steps {
                git branch: 'dev', url: 'https://github.com/ravdy/tweet-trend.git'
            }
        }
    }
}
