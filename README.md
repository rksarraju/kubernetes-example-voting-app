# kubernetes-example-voting-app
Deploy Docker's example voting app on Kubernetes

kubectl create -f voting-app-pod.yml

kubectl get pods

kubectl create -f voting-app-service.yml

kubectl get services

kubectl create -f redis-pod.yml

kubectl get pods

kubectl create -f redis-service.yml

kubectl get services

kubectl create -f postgres-pod.yml

kubectl get pods

kubectl create -f postgres-service.yml

kubectl get services

kubectl create -f worker-app-pod.yml

kubectl get pods

kubectl create -f result-app-pod.yml

kubectl get pods

kubectl create -f result-app-service.yml

kubectl get services


