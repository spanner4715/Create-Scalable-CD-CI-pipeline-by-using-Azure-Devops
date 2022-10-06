# Create Scalable CD/CI pipeline to deploy ML model by using Azure Devops

### Objective  
Most of the time, the machine learning models are trained and developed in local Python notebook and the codes are provided to an app developer, who have to integrate it into an application and deploy it. It's common to see the bugs and the performance issue happened without noticing until the code has already been deployed.  
To tackle this problem, building Machine learning apps through Azure DevOps could be a good option. The whole process  becomes a part of the Continuous Integration (CI) and Continuous Delivery (CD) pipeline of the Azure DevOps. Users can continue to write and train models in their favorite Python environment and  deployed the model to production without worrying about any conflicts between the app and the model.

### DevOps: Development and Operations
1. Continuous Integration and Continuous Delivery (CI/CD)
2. Real-time monitoring
3. Collaborated platforms
4. Cloud agility
5. Orchestration
### Azure Repos  
1. A software to keep tracking changing of codes
2. Two version control tools: Git and TFVC
### Clone Azure Repos through VScode
1. Create a project in Azure DevOps ![image](https://user-images.githubusercontent.com/103509243/194382316-7e79664d-5c51-4e57-9456-38b487b8285b.png)
2. Then create a repository, click "Clone in VS code" ![image](https://user-images.githubusercontent.com/103509243/194384381-d496621f-2bb1-44d8-b670-76745e3498e0.png)
3. Select a repository location and put the file into this folder, files will then be displayed on VScode ![image](https://user-images.githubusercontent.com/103509243/194393055-9adee5c8-858c-43a0-85ff-2b2ea9d2b514.png)
4. Files will be uploaded to Azure simultaneously ![image](https://user-images.githubusercontent.com/103509243/194402089-c85b6295-703d-41d6-ae2c-d99e23ec23b3.png)
### Define FastAPI
FastAPI is a fast, high-performance web framework for building API with Python. ![image](https://user-images.githubusercontent.com/103509243/194414136-0e1707e5-6e26-4c58-b799-c938afa5437e.png)
### Utilize of Docker
Docker is an open platform for developing, shipping and running applications. Its containers are specialized for (CD/CI) workflow. Docker image is a read-only template with instructions for creating containers. ![image](https://user-images.githubusercontent.com/103509243/194413590-16818291-7071-4741-84a8-4430316a3ba3.png)
### Define Docker file
Creating a dockerfile, put its syntax to define the necessary steps to create docker image and run it. ![image](https://user-images.githubusercontent.com/103509243/194412474-1e2359b7-7122-4e16-ac6b-1aa5f8ec39eb.png)
### Create Azure Resource Group
Create a resource group which contains every related resources for Azure solution ![image](https://user-images.githubusercontent.com/103509243/194416350-a93a13e9-beef-4023-9544-74261417edfe.png)
### Create Azure Container Registry
The Azure container registry is a hosting platform for Docker images and a fast, scalable retrieval of container workloads. The benefits of Azure container registry includes "Manage images for different types of containers", "Automated container building, testing and scanning", "Manage windows and Linux container images in a single registry"
1. Go to resource group and choose "Container Registry" ![image](https://user-images.githubusercontent.com/103509243/194423061-30759ae6-6409-4165-8a1e-808bbf6ace0d.png)





