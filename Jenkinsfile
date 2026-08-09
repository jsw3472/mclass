pipeline {
    agent any

    tools {
        maven 'maven 3.9.12'
    }

    stages {
        state('Git Checkout') {
            steps {
                checkout scm
            }
        }
    }
}