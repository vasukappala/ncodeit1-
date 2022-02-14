pipeline {
        agent none 
  parameters {
    choice(
        name: 'TestingParameters',
        choices: "Value\nOption2\nValue2\nOption3",
        description: 'interesting stuff' )
             }


    stages {
        stage('Example Build') {
            
            steps {
                echo 'Hello, Maven'
                sh 'pwd'
            }
        }
        stage('Example Test') {
            
            steps {
                echo 'Hello, JDK'
                sh 'java -version'
            }
        }
    }
}
