# Deployment
These manifests will deploy a working falco install inside a GKE cluster

#### Namespace
    kubectl apply -f namespace.yaml

#### Service Account
    kubectl apply -f serviceaccount.yaml

#### ClusterRole
    kubectl apply -f clusterrole.yaml

#### ClusterRole Binding
    kubectl apply -f clusterrolebinding.yaml

#### Service
    kubectl apply -f service.yaml

#### ConfigMap
    kubectl apply -f configmap.yaml

#### DaemonSet
    kubectl apply -f daemonset.yaml

