

node(){
   stage("git checkout"){
      checkout scm
      sh "pwd"
      sh "ls -l"
   }
   stage("Build and UT"){
      def directory = "devtest1"
		dir(directory){
            sh "mvn package"
      }
      
}

}
