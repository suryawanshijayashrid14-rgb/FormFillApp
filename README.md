🚀 DevOps CI/CD Pipeline Project – 2 (Linux Environment)
📌 Project Description

This project demonstrates the implementation of a complete CI/CD pipeline in a Linux environment using Jenkins, Maven, Git, and Apache Tomcat.

The entire setup and configuration were performed on a Linux server accessed via MobaXterm (SSH). The pipeline automates code integration, build, and deployment of a Java web application.

🖥️ Environment Setup

Operating System: Linux (Ubuntu/CentOS)

Access Tool: MobaXterm (SSH client)

Application Type: Java Web Application (.war)

Deployment Server: Apache Tomcat

CI Tool: Jenkins

Build Tool: Maven

Version Control: Git & GitHub

🏗️ Project Architecture

Developer → Git → GitHub → Jenkins (Linux Server) → Maven Build → WAR File → Tomcat Server

⚙️ Tools & Technologies Used

Git

GitHub

Jenkins

Maven

Java

Apache Tomcat

Linux

MobaXterm

🔄 CI/CD Workflow
1️⃣ Source Code Management

Developer pushes code to GitHub repository.

Jenkins is configured to monitor the repository.

2️⃣ Continuous Integration

Jenkins pulls latest code from GitHub.

Maven executes the build command:

mvn clean package

WAR file is generated inside the target/ directory.

3️⃣ Continuous Deployment

The generated WAR file is deployed to:

/opt/tomcat/webapps/

Tomcat automatically deploys the application.

4️⃣ Application Access

The deployed application can be accessed via:

http://<Server-IP>:8080/<Application-Name>

🛠️ Linux Commands Used
# Check Java version
java -version

# Clone repository
git clone <repository-url>

# Build application
mvn clean package

# Start Jenkins
sudo systemctl start jenkins

# Start Tomcat
sudo systemctl start tomcat
🎯 Key Features

Automated build process using Jenkins

Maven-based build management

WAR file generation and deployment

Complete CI/CD setup in Linux environment

Remote server management using SSH (MobaXterm)

📈 Learning Outcomes

Hands-on experience with CI/CD pipeline setup

Linux server configuration and management

Jenkins job configuration

Maven build lifecycle understanding

Tomcat deployment process

🚀 Future Enhancements

Implement Jenkins Pipeline (Jenkinsfile)

Docker containerization

Kubernetes deployment

SonarQube integration for code quality

Email notification integration

👩‍💻 Author

Jayashri Suryawanshi
DevOps Engineer | Linux | Jenkins | Maven | Git | CI/CD Enthusiast
