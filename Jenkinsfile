pipeline {
    agent any

    stages {
        stage('Compile Java Program') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }

        stage('Run Java Program') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
