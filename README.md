#  Django App Deployed to Azure Kubernetes Service (AKS)

This project demonstrates containerizing a Django app with Docker, pushing it to Azure Container Registry (ACR), and deploying it to Azure Kubernetes Service (AKS).

---

## Tech Stack

- Django 5.x
- Docker
- Azure CLI
- Azure Container Registry (ACR)
- Azure Kubernetes Service (AKS)

---

## Create a Dockerfile

![alt text](image.png)

---

## Build Dockerfile

![alt text](<Screenshot 2025-06-01 122759.png>)

---

## Run Locally

![alt text](<Screenshot 2025-06-01 125424.png>)

---

## Create a Resource Group

![alt text](<Screenshot 2025-06-01 132215.png>)

---

## Create ACR (Azure Container Registry)

![alt text](<Screenshot 2025-06-01 132635.png>)

---

## Log in to ACR

![alt text](<Screenshot 2025-06-01 133513.png>)

![alt text](<Screenshot 2025-06-01 134711.png>)

---

## Tag Docker Image

![alt text](<Screenshot 2025-06-01 133459.png>)

---

## Push Image to ACR

![alt text](<Screenshot 2025-06-01 134953.png>)

---

## Create AKS Cluster

![alt text](<Screenshot 2025-06-01 140338.png>)

![alt text](<Screenshot 2025-06-01 140419.png>)

---

## Get AKS Credentials Locally 

![alt text](<Screenshot 2025-06-01 140521.png>)

---

## Test connection

![alt text](<Screenshot 2025-06-01 141405.png>)

---

## Create Django Deployment file

![alt text](<Screenshot 2025-06-01 141659.png>)

---

## Apply YAML to Deploy and check status

![alt text](<Screenshot 2025-06-01 142302.png>)

![alt text](<Screenshot 2025-06-01 142328.png>)

---

## Image error but fixed this by changing the version from latest to v1

![alt text](<Screenshot 2025-06-01 143033.png>)

![alt text](<Screenshot 2025-06-01 143842.png>)

---

## Django app is live from the external public IP

![alt text](<Screenshot 2025-06-01 145003.png>)

---

## Acknowledgements

This project was originally forked from [heroku](https://github.com/heroku/python-getting-started).  
Credit to the original authors for the base application.

