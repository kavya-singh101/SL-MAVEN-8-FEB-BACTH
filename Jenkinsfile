pipeline
{
	agent any
		tools
		{
			maven 'MAVEN_HOME'
		}
		stages
		{
			stage('Welcome Stage')
			{
				steps
				{
					echo 'Welcome to Pipeline'
				}
			}
			
			stage('Clean Stage')
			{
				steps
				{
					bat 'mvn clean'
				}
			}
			stage('Finish Stage')
			{
				steps
				{
					echo 'Finish Stage'
				}
			}
			
		}
}