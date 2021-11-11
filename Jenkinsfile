node {
    stage ("SCM Checkout") {
	 	cleanWs()
           	 git url: "https://github.com/pns99/santu-sonar.git"
    }
    stage ("Compile-package") {
	    //mvntest
	//def mvnHOME = tool name: 'mymaven', type: 'maven'
        sh "/opt/maven/bin/mvn package"
    }
}
