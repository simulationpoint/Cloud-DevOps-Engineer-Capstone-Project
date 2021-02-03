// Powered by Infostretch 
// Jesh Amera 
// Feb 02/2021

timestamps {

node () {

	stage ('Cloud DevOps Engineer Final Capstone Project - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], 
 	 	doGenerateSubmoduleConfigurations: false, extensions: [], 
 	 	submoduleCfg: [], userRemoteConfigs: [[credentialsId: '', 
 	 	url: 'https://github.com/simulationpoint/Cloud-DevOps-Engineer-Capstone-Project.git']]]) 
	}
	stage ('Cloud DevOps Engineer Final Capstone Project - Build') {
 			// Shell build step
sh """ 
python web.py 
 """ 
	}
}
}