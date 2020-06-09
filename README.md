# Kubernetes_assignments
Wordpress and Mysql deployment in Kubernetes(using minikube).

Download all files on you root path and then execute following command:

kubectl apply -k ./                         #this will create all expected deployments

Create 3 replicas of deployments using these commands:

kubectl scale  --replicas=3 deployment/wordpress

kubectl scale  --replicas=3 deployment/wordpress-mysql

Wordpress website is accessible at following link:

<minikube-ip address>:30080

