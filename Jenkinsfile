pipeline {
	agent any

  environment {
		VERSION = '0.0.1'
	}

	stages {
		stage('Deploy') {
			steps {
        // wget o curl
				bat 'copy C:\\Users\\M10630\\.m2\\repository\\bootcamp\\jenkins\\war-example\\' + env.VERSION + '\\war-example-' + env.VERSION + '.war  D:\\devenv\\ambientes\\tomcat1\\webapps\\ROOT.war'
			}
		}
	}
}
