pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo'Build' 
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                archiveArtifacts artifacts: 'Practicajs.js', fingerprint: true
            }
        }
    }
}
