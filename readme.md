# 🚀 Jenkins-Based DevOps Pipeline on AWS – Practice Project

This is a hands-on practice project I created to understand how different DevOps tools work together in a CI/CD pipeline.  
I’m learning DevOps by **doing everything manually** — launching servers, installing tools, connecting them, facing errors, and fixing them.

---

## 🔧 What I Did

- Launched a **t2.medium EC2 instance** on **AWS** (manually, not using any template)
- Installed **Jenkins** on the EC2 instance
- Configured required ports (8080 for Jenkins, 8081 for app deployment)
- Connected **GitHub repo** to Jenkins using webhook for automatic build triggers
- Created a **Declarative Jenkinsfile** with multiple stages:
  - **Clone code** from GitHub
  - **Build** the Java project using **Maven**
  - **Code Quality Scan** using **SonarQube**
  - **Deploy** a simple web page (HTML/Java) to verify the final output
- Installed and configured **SonarQube** locally
- Integrated SonarQube with Jenkins using credentials and project key
- Fixed several issues during plugin setup, Sonar analysis failures, and Maven build errors

---

## 💡 What I Learned

- Jenkins pipeline structure and how each stage works  
- How to connect GitHub with Jenkins using webhooks  
- How Maven builds a Java project and generates artifacts  
- SonarQube integration with Jenkins and how to read quality gates  
- How port mapping works in EC2 for different services  
- Troubleshooting real-world errors (like plugin issues, permissions, build failures)  
- Importance of understanding the **flow from code to deployment**

---

## 📂 GitHub Repository

Here’s the complete code and Jenkinsfile used in this project:  
🔗 [https://github.com/saurabhgusain09/jenkins_superlab_.git](https://github.com/saurabhgusain09/jenkins_superlab_.git)

---

## 🙌 About Me

I’m a DevOps learner building small real-world projects to improve my understanding.  
This project helped me understand the **basics of CI/CD** in a real environment using core tools like Jenkins, GitHub, SonarQube, and AWS.

Always open to feedback and suggestions!

**Saurabh Gusain**  
📧 usainsaurav08@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/saurabhgusain12/)
