# ArgoCD-nov-jobs-again
for argocd deployement


kind create cluster --config cluster-config.yaml
# kind create cluster --config name-of-yaml-file

kind create cluster --name=name-of-cluster --config=cluster-file.yaml


kind create cluster --name=dev-cluster --config=new-cluster.yaml
# kind delete cluster -n=kube-monitor ----> this is a way to remove the clusterquit

