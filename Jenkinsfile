pipeline {
    agent any
    
    environment {
        PROJECT_NAME = "Mega project"
        OWNER_NAME   = "Evgeniy Polyakov"
    }
    
    stages {
        stage('1-Build') {
            steps {
                echo 'Start of Stage Build'
                echo 'Building.............'
                echo 'Finish of Stage Build'
            }
        }
        stage('2-Test') {
            steps {
                echo 'Start of Stage Test'
                echo 'Testing.............'
                echo "${OWNER_NAME}"
                echo "Project name is ${PROJECT_NAME}"
                echo 'Finish of Stage Test'
            }
        }
        stage('3-Deploy') {
            steps {
                echo 'Start of Stage Deploy'
                echo 'Deploy.............'
                echo 'Finish of Stage Deploy'
            }
        }
    }
}
