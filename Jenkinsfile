@Library("nico-jenkins-sharedlibs") _
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sayHello()
            }
        }
                stage('Creds') {
            steps {
                getCred()
            }
        }
    }
}
