## Build and Publish a Docker image 

1. Write and add dockerfile in the source code
	```sh
		FROM openjdk:8
		ADD jarstaging/com/valaxy/demo-workshop/2.0.2/demo-workshop-2.0.2.jar demo-workshop.jar
		ENTRYPOINT ["java", "-jar", "demo-workshop.jar"]
	```