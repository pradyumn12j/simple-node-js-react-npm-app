pipeline {
    agent any    
    stages {
        stage("git") {
            steps{git 'https://github.com/pradyumn12j/simple-node-js-react-npm-app.git'}
        }
        stage('Build') {
            steps {
            sh 'npm build'

                
            }
        }
        

    }
}