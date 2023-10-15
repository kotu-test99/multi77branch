pipeline {   
    agent any

    stages {   
        stage('Development branch') { 
            steps { 
               sh 'echo "This is development branch"' 
            }
        }
     
        stage('Testing ') { 
            steps { 
               sh 'echo "test application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
