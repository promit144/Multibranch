node('Master') 
{
    stage('Continuous Download') 
	{
	input 'Waiting for Approval'
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}

