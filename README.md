# Assessment: Use Case Oriented Project

I had to create an automated deployment and configuration of 3 microservices:

 - front-end service
 - product catalog service
 - order processing service

All the work had to be version controlled using git, the images for the services were to be made using docker and deployed using kubernetes.

## Tasks and Deliverables

### Task 1: Git Repository Setup

I created a git repo with 3 branches: 
 - development
 - testing 
 - production

After setting up the git I pushed the codes using cli

![alt text](<img/Screenshot from 2024-08-02 16-43-20.png>) 

![alt text](<img/Screenshot from 2024-08-02 16-45-46.png>)

### Task 2: Dockerize Microservices

For **Dockerfile** I created a seperate folder for each of the service and then added the necessary files in that. This was it's easy to keep track of the files and data

File Structure
![alt text](<img/Screenshot from 2024-08-02 16-46-29.png>)

Once the Dockerfile was created I build the image and the push it on the docker hub.

![alt text](<img/Screenshot from 2024-08-02 16-48-42.png>)

And the images were available on Dockerhub

![alt text](<img/Screenshot from 2024-08-02 16-50-55.png>)

### Task 3: Kubernetes Deployment

For the Kubernetes Section I created a deployment file that creates a deployment, service and replicasets for each microservice.


![alt text](<img/Screenshot from 2024-08-02 17-39-10.png>)

**Final Output**

**Front-End Service**
![alt text](<img/Screenshot from 2024-08-02 17-49-14.png>) 

**Product-Catalog Service**
![alt text](<img/Screenshot from 2024-08-02 17-49-29.png>) 

**Order-Processing Service**
![alt text](<img/Screenshot from 2024-08-02 17-49-46.png>)