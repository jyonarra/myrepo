pipeline{
	agent any
	stages{
	   stage ("initialize") {
        steps {
             sh '''
                 echo "PATH = ${PATH}"
                 echo "M2_HOME = ${M2_HOME}"
                
                '''
            }
          }
          stage ('Build project') {
            steps {
                sh "docker version"
                 }
			}
		
	
	}
	}