pipeline {
    agent any
    stages {
        stage('Welcome Step') {
            steps { 
                echo 'Welcome to Jenkins pipeline'
                //input 'enter prompt'
                echo 'change added'
            }
        stage('2nd step') {
            echo "This is one more stage"
            echo $HOSTNAME
            ifconfig
        }

        }
    }
}
