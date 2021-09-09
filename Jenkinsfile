pipeline{
    agent any
    stages{
        stage('Compile'){
            steps{
                echo 'Compiled Successfully!!!!';
                sh 'javac date.java'
            }
        }
    stage('Run'){
            steps{
                echo 'Pass!!!!';
                sh 'java date'
            }
        }
    }
   
}

