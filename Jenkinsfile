@Library('jenkins-shared-library@master') _
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            vcCheckout(
                branch: "master",
                url: "https://github.com/redprasa/jenkins_shared_library"
            )
            }
    }
    }
}
