node{
	stage("Build"){
		if(env.TAG_NAME != null){
			println(" we are building a tag and tag is ${env.TAG_NAME}")
		}
		else{
			println(" we are building a branch")
			//ki
		}
		
		if(env.TAG_NAME == "release-1.0"){
			println(" we are building specifically release-1.0 tag")
		}
		
	}
}
