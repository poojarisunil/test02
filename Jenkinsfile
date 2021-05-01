node () {

	stage ('maven-build_01_5 - Checkout') {
 	 checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '', url: 'https://github.com/poojarisunil/test02.git']]]) 
	}
	stage ('maven-build_01_5 - Build') {
 	sh """"
		    cd $WORKSPACE
			ls-ltra
			mvn install
	 			 
			} 
 		} 
	
