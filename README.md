# kube-news

Faça a instalação do k3d e do kubectl.

Instalar K3D: • https://k3d.io/

Instalar Kubectl: • https://kubernetes.io/docs/tasks/tools/

Na pasta ./k8s faça o seguinte:

Primeiro comando: • k3d cluster create cluster-kube-news --agents 2 --servers 2 -p "80:30000@loadbalancer"

Segundo comando: • kubectl apply -f deployment.yaml

Para testar, acesse: http://localhost
