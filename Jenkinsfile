pipeline { 
    agent any  
    tools {
        maven 'MyMaven'
        jdk 'jdk8'
    }
    stages { 
        stage('Build') { 
            steps { 
               echo 'This is a minimal pipeline.' 
                sh 'mvn clean install'
            }
        }
    }
}
