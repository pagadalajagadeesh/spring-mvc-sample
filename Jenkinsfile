pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                  echo 'Building..'
                  sh 'mvn clean package' 
            }
        }
        stage('Deploy') { 
            steps {
                  echo 'Deploying....'
            }
        }
    }
}
