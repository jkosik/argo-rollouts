# argo-rollouts
Argo Rollouts sample project

## Prerequisites
kubectl apply -f https://github.com/kubernetes-sigs/metrics-server/releases/latest/download/components.yaml
kubectl create namespace argo-rollouts

helm repo add argo https://argoproj.github.io/argo-helm
helm install argo-rollouts argo/argo-rollouts

