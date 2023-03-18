# Run Vanus On Kubernetes

## Installation

```sh
kubectl apply -f latest/namespace.yaml
kubectl apply -f latest/etcd.yaml
kubectl apply -f latest/root-controller.yaml
kubectl apply -f latest/controller.yaml
kubectl apply -f latest/store.yaml
kubectl apply -f latest/timer.yaml
kubectl apply -f latest/trigger.yaml
kubectl apply -f latest/gateway.yaml
```
