```
docker build -t myapp:1.0 .
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
minikube service myapp
```
