## Objective
Deploy and manage applications in Kubernetes using Minikube on Windows.

## Tools Used
* Docker Desktop
* Minikube
* kubectl
* Git Bash

## Steps Performe
1. Installed kubectl.
2. Installed Minikube.
3. Started a local Kubernetes cluster.
4. Created a Deployment using deployment.yaml.
5. Deployed an NGINX application.
6. Created a Service using service.yaml.
7. Exposed the application using NodePort.
8. Verified pods and services.
9. Viewed deployment details and logs.
10. Scaled the deployment from 2 replicas to 5 replicas.
11. Verified successful scaling.

## Files Included
### deployment.yaml
Creates an NGINX Deployment with multiple replicas.
### service.yaml
Creates a NodePort Service to expose the NGINX application.

## Verification Commands

```bash
kubectl get nodes
kubectl get pods
kubectl get services
kubectl describe deployment nginx-deployment
kubectl logs <pod-name>
kubectl scale deployment nginx-deployment --replicas=5
kubectl get all
```

## Screenshots
The screenshot included : 
* deployment.yaml
* service.yaml
* kubectl get nodes
* kubectl get pods
* kubectl get deployments
* kubectl get services
* nginx webpage
* kubectl describe deployment
* kubectl logs
* scale to 5 pods
* scale back to 2 pods

## Outcome
Successfully created a local Kubernetes cluster using Minikube, deployed an application, exposed it through a Service, verified functionality, and scaled the deployment.
