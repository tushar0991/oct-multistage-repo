pipeline {
agent any
stages {

	stage ('print first message')
	{steps { sh 'echo job-is-building'}}
	
	stage ('print second message')
	{steps { sh 'echo package-is-deploying'}}
	
	stage ('print final message')
	{steps { sh 'echo deploy-to-prpd'}}

}
}
