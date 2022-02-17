pipeline {
    agent none
    stages {
        stage ('Maven Install') {
            agent { label 'u20-mvn-jdk8' }
            steps {
                sh 'mvn clean install' 
            }
        }
    }
}
