# Devops Engineer Challange


# Diagram of Given Case
<img width="617" alt="Ekran Resmi 2022-04-09 23 26 46" src="https://user-images.githubusercontent.com/63977569/162590580-88596c9c-7b0e-4116-bb5e-e25ccc2e82e4.png">

Firstly, I installed ubuntu virtual machine by vagrant. Then, I write shell script to install minikube with a k8s cluster, helm, terraform and requirements. I create this repo and clone the given repo into to this repo. All files uploaded to this repo. 






# Status of Given Case
<img width="510" alt="Ekran Resmi 2022-04-09 23 29 32" src="https://user-images.githubusercontent.com/63977569/162590645-ddc5b5e7-9b0c-4778-a90c-f929209aac80.png">


- Green sentences are done.

- Yellow sentences are not finished because of some errors.

When I write Dockerfile to dockerize the application, I got error about .Net such as following :
(Step 0 : FROM mcr.microsoft.com/dotnet/sdk:6.0 AS build-env
Pulling repository mcr.microsoft.com/dotnet/sdk
INFO[0002] invalid character '<' looking for beginning of value)

When I install Rabbitmq by Helm I got this error after I write "helm install my-release bitnami/rabbitmq"
(Killed)

When I start minikube I got this error
(Error starting host: Error creating host: Error executing step: Running precreate checks.
: VBoxManage not found. Make sure VirtualBox is installed and VBoxManage is in the path.)
