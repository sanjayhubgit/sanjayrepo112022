node('built-in') 
{
    stage('Continuous Download_builtin') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_builtin') 
	{
    sh label: '', script: 'mvn package'
	}
}
