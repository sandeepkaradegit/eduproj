pipeline { 
    agent any 
    stages {
        stage('JOB1') { 
            steps { 
                echo 'JOB1'
                build job: 'JOB1'
            }
        }
        stage('JOB2'){
            steps {
                echo 'JOB2'
                build job: 'JOB2'
            }
        }
        stage('JOB3') {
            steps {
                echo 'JOB3'
                build job: 'JOB3'
            }
        }
        stage('JOB4') {
            steps {
                echo 'JOB4'
                build job: 'JOB4'
            }
        }
    }
}
