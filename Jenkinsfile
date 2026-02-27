pipeline {
    agent any
    tools {
        maven 'MAVEN_HOME'   // ton Maven configuré dans Jenkins
        jdk 'Default'        // le JDK qu’on vient de configurer
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}