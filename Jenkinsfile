pipeline {
    agent any

    stages {
        stage('Hello World') {
            steps {
                script {
                    echo  "Hello World"
                }
            }
        }

        stage('Print from Script') {
            steps {
                script {
                    evaluate(readFile('print.groovy'))
    
                }
            }
        }
    }
}
