# Publish a website with Kubernetes
The goal of this laboratory is to practice with the complete workflow required to create, package and deploy a website on a Kubernetes-based cluster. Overall, this aims to better highlight how the different building blocks learned during the previous laboratories (e.g., containers creation, applications deployment and exposition, . . . ), can be combined to achieve a fully functional service.
The very same approach, then, could be generalized, to account for more complex scenarios composed of multiple microservices which cooperate together and implement complex functionalities. An example of such complex setup is provided by the Online Boutique demo application made available by Google.
To show the successful completion of the laboratory, students will be requested at the end to send on the #lab channel of the course’s Slack workspace the link to access their website.

## How to pull the Image
Link to the Docker Image (DockerHub): [s296114/hugo-cloud-site](https://hub.docker.com/r/s296114/hugo-cloud-site). For the cluster it's necessary to clarify the correct tag in the Manifest (e.g., s296114/hugo-cloud-site:lab4). To pull the image: 

`docker pull s296114/hugo-cloud-site`

## For K8s 
It has been used a sandbox namespace provided by **Politecnico di Torino**. Since it's used an HTTPS connection, it must be present a proper certificate (also provided by the Sandbox for TLS connection)
