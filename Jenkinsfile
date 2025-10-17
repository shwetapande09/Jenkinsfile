pipeline {
    agent any
    stages{
        stage ("Run Job01"){
            steps{
                build job:'Job-01'
            }
        }
        stage ("Run Job02"){
            steps{
                build job:'Job-02'
            }
        }
    }
} 