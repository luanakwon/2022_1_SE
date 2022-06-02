pipeline {
    agent {
        label "demoAgent"
    }

    stages {
        stage('Build') {
            steps {
                echo "202206022249 Building.."
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
