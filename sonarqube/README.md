# Sonarqube

## install use helm

```
microk8s helm repo add sonarqube https://SonarSource.github.io/helm-chart-sonarqube
microk8s helm repo update
kubectl create namespace sonarqube
microk8s helm upgrade --install -n sonarqube sonarqube sonarqube/sonarqube
```
