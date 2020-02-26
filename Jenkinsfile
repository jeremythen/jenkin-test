pipeline {
	agent any
	stages {
		stage("JavaCompile") {
			steps {
				echo "Before compiling JavaTest.java"
				javac JavaTest.java
				echo "After compiling JavaTest.java"
				echo "Before running JavaTest class"
				java JavaTest
				echo "After running JavaTest class"
			}
		}
	}
}