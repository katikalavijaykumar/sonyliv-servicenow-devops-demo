pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'ServiceNow DevOps Build Started'
            }
        }

        stage('Test') {
            steps {
                echo 'ServiceNow DevOps Test Successful'
            }
        }
    }

    post {
        success {
            echo 'ServiceNow DevOps Pipeline Completed Successfully'
        }
    }
}
