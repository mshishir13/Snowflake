pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
         parallel{

                stage('TestA') {
                        steps {
                            echo 'Testing..'
                        }
                }
                stage('TestB') {
                        steps {
                            echo 'Testing..'
                        }
                }

            }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}