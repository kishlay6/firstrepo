node{
        stage('java version') {
            bat 'java -version'
            }
        stage('test'){
            echo 'Correct!'
        }
        stage('build confirm'){
            echo 'Done!'
        }
        stage('git connection'){
         git credentialsId: 'Kislay', url: 'https://github.com/kishlay6/firstrepo.git/'
         echo 'Connected '
        }
        }
