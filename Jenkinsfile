peline {
    agent {
        label ''
    }

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code...'
                git 'https://github.com/itsmeshamaislam/my-first-ci-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'cat readme.txt'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "No tests defined."'
            }
        }
    }
}

































