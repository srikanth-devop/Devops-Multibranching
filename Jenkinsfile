pipeline {   
    agent any

    stages {   
        stage('hotfix branch') { 
            steps { 
               sh 'echo "This is multi changed hotfix branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
