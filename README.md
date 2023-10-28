# DeVOps-Project_KADDEM

DeVOps Academic Project, Practicing Basic DeVOps tools and immersing into the DeVOps world!

### Objective

The objective of this project is to prepare students for the new requirements of the job market, focusing on the "KADDEM" project.

### Project Description

![205064014-71e3b383-81ae-4554-98af-e2522a972220](https://github.com/wissalsoudani/DeVOps-Project_KADDEM/assets/61351743/c3f01591-28f5-440f-8b5e-5f60e048fc42)

We aim to create an application for managing student contracts within the "Kaddem" project. This project defines a program for distributing students into teams in each department of participating universities. Each team will have a level (junior/senior or expert) in one of the following specialties: AI, networks, security, cloud.

Therefore, this project offers students contracts based on their specialty and level. Each student will receive a contract if they join a team. In the case where they are assigned to multiple teams, they will have a contract for each activity with a team.

The contract is simply a moral commitment between the student and their university ➔ therefore, they must honor their commitment by actively participating in the progress of their team.

## Requirements

For building and running the application you need:

- JDK 1.8

## Running the Application Locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the main method in the `tn.esprit.kaddemproject.KaddemProjectApplication` class from your IDE.

## Browser URL

Open your browser at the following URL for Swagger UI (giving REST interface details):

[http://localhost:9090/swagger-ui/index.html](http://localhost:9090/swagger-ui/index.html)
Alternatively you can use the Spring Boot Maven Wrapper plugin like so:

```bash
./mvnw spring-boot:run
````
## DevOps Approach

The KADDEM project uses a DevOps approach to ensure seamless development, testing, and deployment processes. Here are the key steps:

1. Git Checkout Your Branch: Retrieve the project from your branch on GitHub (The repository must be private).
2. Unit Testing: Run unit tests with JUnit and Mockito.
3. Static Analysis Testing: Run static tests with SonarQube.
4. Build Artifact: Create the deliverable (.jar) using Maven.
5. Build Docker Image.
6. Deploy Artifact to Nexus.
7. Deploy Image to DockerHub/Nexus.
8. Start Containers: Launch the TpAchat application and the database.
