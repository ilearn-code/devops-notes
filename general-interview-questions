# General DevOps Questions 🚀

## 1. What is DevOps, and how is it different from Agile? 🤔
DevOps is a set of practices that combines software development (Dev) and IT operations (Ops) to shorten the development lifecycle and ensure continuous delivery. It emphasizes automation, monitoring, and collaboration.

**Difference from Agile:**
- Agile focuses on iterative software development. 🔄
- DevOps focuses on automating the release and deployment process. ⚙️

## 2. What are the key benefits of DevOps? 🌟
- Faster delivery of software updates 🚀
- Improved collaboration between teams 🤝
- Reduced failures and quick recovery 🔧
- Higher automation, reducing manual work 🤖
- Better scalability and reliability 📈

## 3. What are the main phases of a DevOps lifecycle? 🔄
1. **Plan** – Define project goals 📝  
2. **Develop** – Write and manage code 💻  
3. **Build** – Compile and package code 🛠️  
4. **Test** – Automated testing ✅  
5. **Release** – Versioning and deployment 🚀  
6. **Deploy** – Move to production 📦  
7. **Operate** – Monitor and maintain 🔍  
8. **Monitor** – Collect logs and metrics 📊  

## 4. Explain Infrastructure as Code (IaC). How does it benefit DevOps? 🏗️
IaC means managing and provisioning infrastructure through code instead of manual processes.  
**Benefits:**
- Consistency ✅
- Automation 🤖
- Version control 📂
- Faster provisioning ⚡

## 5. What are CI, CD, and Continuous Deployment? 🔧
- **Continuous Integration (CI):** Automates code integration and testing. 🛠️
- **Continuous Delivery (CD):** Ensures code is always in a deployable state. 🚀
- **Continuous Deployment:** Automates deployment to production without manual approval. 🤖

---

# Version Control & Git 🗂️

## 6. What is Git, and how does it help in DevOps? 🌐
Git is a distributed version control system that helps in tracking changes in code. It enables collaboration and integrates with CI/CD pipelines.

## 7. What is the difference between Git Merge and Git Rebase? 🔀
- **Merge:** Creates a new commit combining changes. 🛠️
- **Rebase:** Moves commits from one branch to another, keeping a linear history. 📜

## 8. How do you resolve a Git merge conflict? ⚔️
1. Run `git status` to check conflicting files. 📋  
2. Edit files manually to resolve conflicts. ✏️  
3. Use `git add` to stage resolved files. ✅  
4. Commit the changes using `git commit`. 💾

## 9. What is Gitflow, and when should it be used? 🌳
Gitflow is a branching model that uses develop, feature, release, and hotfix branches. It’s used in large teams for structured development.

## 10. How do you squash commits in Git? 🧹
Use `git rebase -i HEAD~n` (replace `n` with the number of commits).  
Mark the commits you want to squash as `squash`.

---

# CI/CD (Jenkins, GitHub Actions, GitLab CI/CD) 🔄

## 11. What is the role of Jenkins in a DevOps pipeline? 🤖
Jenkins automates building, testing, and deployment of applications.

## 12. How does a CI/CD pipeline work? 🛠️
1. Developers push code 📤  
2. CI runs tests ✅  
3. Code is built 🏗️  
4. Deployment (CD) happens automatically or manually 🚀  

## 13. What are some best practices for writing Jenkins pipelines? 📝
- Use declarative pipelines. ✅
- Keep pipeline scripts in version control. 📂
- Use credentials securely. 🔒

## 14. What is the difference between declarative and scripted pipelines in Jenkins? 🛠️
- **Declarative:** Uses a simple syntax (`Jenkinsfile`). 📝
- **Scripted:** Uses Groovy scripting for complex workflows. 🧑‍💻

## 15. How do you implement rollback strategies in CI/CD? 🔄
- **Blue-Green Deployments:** Keep the previous version running. 🟦🟩
- **Canary Releases:** Deploy to a small subset first. 🐦
- **Revert in Version Control:** Use Git to roll back. 🔙

---

# Configuration Management (Ansible, Chef, Puppet) ⚙️

## 16. What is Configuration Management, and why is it important in DevOps? 🛠️
Configuration Management ensures consistent and automated infrastructure configuration, reducing human errors.

## 17. How does Ansible differ from Chef and Puppet? 🤔
- **Ansible:** Agentless, YAML-based, easy to use. 📝
- **Chef/Puppet:** Agent-based, more complex but powerful. 🧑‍💻

## 18. What are Ansible playbooks, and how do they work? 📖
Playbooks are YAML files that define automation tasks.

## 19. How do you manage sensitive data in Ansible? 🔒
Use **Ansible Vault** to encrypt sensitive files.

## 20. Explain idempotency in configuration management. 🔄
Running the same script multiple times doesn’t change the system beyond its intended state.

---

# Containerization & Orchestration (Docker, Kubernetes) 🐳

## 21. What are the benefits of using Docker? 🚀
- Lightweight and portable 🧳
- Fast deployments ⚡
- Isolated environments 🔒

## 22. What is the difference between a Docker image and a Docker container? 🐳
- **Image:** Blueprint of the container. 📄
- **Container:** Running instance of an image. 🏃

## 23. How do you manage persistent storage in Docker? 💾
Use **Volumes** (`docker volume create mydata`).

## 24. What is Kubernetes, and how does it help with container orchestration? ☸️
Kubernetes automates deployment, scaling, and management of containerized applications.

## 25. What is the difference between Deployment, StatefulSet, and DaemonSet in Kubernetes? 🛠️
- **Deployment:** Stateless applications. 📦
- **StatefulSet:** Stateful applications (databases). 🗄️
- **DaemonSet:** Runs one pod per node. 🖥️

## 26. What are Kubernetes namespaces, and why are they used? 🏷️
Namespaces isolate resources within a cluster.

## 27. Explain the role of Kubernetes Ingress. 🌐
Ingress manages external access to services.

## 28. What are Kubernetes ConfigMaps and Secrets? 🔒
- **ConfigMaps:** Store non-sensitive config data. 🗂️
- **Secrets:** Store sensitive data (base64 encoded). 🔑

---

# Infrastructure as Code (Terraform, CloudFormation) 🏗️

## 29. What is Terraform, and how does it differ from CloudFormation? 🌍
Terraform is a cloud-agnostic IaC tool, while CloudFormation is AWS-specific.

## 30. What are Terraform modules, and why should you use them? 📦
Modules reuse code for better organization.

## 31. How do you handle state management in Terraform? 🗂️
Store state files in remote backends (e.g., S3, Consul).

## 32. What is the difference between `terraform plan` and `terraform apply`? 🛠️
- **`plan`:** Shows changes before applying. 🔍
- **`apply`:** Executes the changes. ✅

## 33. How do you use Terraform with multiple environments? 🌐
Use workspaces or separate state files.

---

# Security & Compliance in DevOps 🔒

## 44. How do you integrate security into a DevOps pipeline (DevSecOps)? 🛡️
- Static code analysis 🧑‍💻
- Dependency scanning 🔍
- Automated security testing ✅

## 45. What is Shift Left security? ⬅️
Integrating security earlier in the development lifecycle.

## 46. What tools do you use for security scanning in DevOps? 🛠️
- **Snyk** 🛡️
- **SonarQube** 📊
- **Trivy** (Docker security) 🐳
