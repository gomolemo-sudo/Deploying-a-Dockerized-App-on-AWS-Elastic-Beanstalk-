# **Deploying a Dockerized App on AWS Elastic Beanstalk**  

### **Overview**  
This project demonstrates how to **containerize an application using Docker** and deploy it to **AWS Elastic Beanstalk** for scalable hosting.  

### **Features**  
- 📌 **Custom Docker Image**: Built and deployed a containerized app  
- 📌 **Local Testing**: Ran the container locally to ensure functionality  
- 📌 **Port Mapping & Troubleshooting**: Resolved a port conflict issue during deployment  
- 📌 **AWS Elastic Beanstalk Deployment**: Hosted the app with auto-scaling and load balancing  

### **Lessons Learned**  
Understanding **Docker port mappings** and troubleshooting conflicts was a key takeaway. Deploying to **Elastic Beanstalk** simplified infrastructure management, making the process seamless.  

## 🛠️ Tech Stack  
- **Docker** 🐳 - For containerizing the application  
- **AWS Elastic Beanstalk** ☁️ - For managed deployment  
- **Nginx** 🚀 - As a high-performance web server  

### **Setup Instructions**  
1️⃣ Install **Docker** and create a **Dockerfile**  
2️⃣ Build a custom **Docker image** using `docker build -t my-app .`  
3️⃣ Run the container locally using `docker run -p 3000:3000 my-app`  
4️⃣ Deploy the containerized app to **AWS Elastic Beanstalk**  
5️⃣ Test the app in a live environment!  

[📄 Project Documentation](#)  [legendary-aws-compute-eb.pdf](https://github.com/user-attachments/files/19473459/legendary-aws-compute-eb.pdf)
