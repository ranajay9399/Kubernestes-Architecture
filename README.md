# Kubernestes-Architecture
This is for demonstrating the kubernetes Architecture

Before moving to kubernestes, below is the very high level defintion of Docker and kubernetes as below : 

Docker - Its a containerization platform where we can create,manage and destroy multiple containers as per the requirement. 

Kubernetes - Its a container orchestration platofrm with some very cool features/advantages over Docker. 

As we know that kubernestes solves mainly below four fundamental issue that docker has - 
1)Single host dependency : In Docker, mostly we create containers in a single host, there for there is no default clustering concept available in docker unless we use docker swarm. However in k8s, it comes with default Master/Node clustering concept. 

2)Auto Healing: If any container goes down, in docker there is no any option available to make that container reviced automatically . Whereas, Kubernestes has Auto healing facility.

3)Auto Scalling: If there is any load on traffic and the working container is not able to handle these many of the requestes then Docker doesn't have anything default auto scalling mechanism but K8s does have that facility to auto scale the infra.

4)Enterprise level support: So by default Docker does not have enough enterprise level support features like load balancing,Firewall,API Gateway etc . But Kubernestes not only have these enterprise level suport functions but also have adavnce features as well. 

Now its time to know the kubernestes architecture : 

![image](https://github.com/ranajay9399/Kubernetes-Architecture/assets/122826508/0e9101e5-0fd4-4a42-8e32-f09f59867eac)





