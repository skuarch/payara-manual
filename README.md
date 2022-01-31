# Requirements
- minikube
- kubectl
- minikube with ingress enabled (minikube addons enable ingress)
- modify *host file* with parayara.net host
> 127.0.0 payara.net  
192.168.49.2 payara.net

# Run
- kubectl apply -f payara-manual-deployment.yaml
- kubectl apply -f payara-manual-service.yaml
- kubectl apply -f payara-manual-ingress.yaml

# Test
- curl payara.net
