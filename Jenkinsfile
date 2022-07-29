node('master') 
{
    stage('Continuous Download_loan') 
	{
    git 'https://github.com/hari1155/maven.git'
	}
    stage('Continuous Build_loan') 
	{
    sh label: '', script: 'mvn package'
	} 
          
}
