# 1. Creare un Pod

Il Pod è l'unità base di calcolo in Kubernetes.

### Esegui un container Nginx

Crea un Pod imperativamente:

```execute
kubectl run web-test --image=nginx:alpine
