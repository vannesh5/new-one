pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                 git ' https://github.com/vannesh5/sunil.git'
            }
        }
        stage('run') {
            steps {
                sh "bash vann.sh"
            }
        }
    }
}
