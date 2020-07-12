# Webrtc stack in kubernetes(focus on jitsi)

* Usefull command to scale out scale in cluster:
```
gcloud container clusters resize cluster-1 --node-pool default-pool  --num-nodes 3  --zone europe-north1-a
kubectl config --kubeconfig=config-demo set-context jitsi
```

Helmfile is used to describe tech stack about setup

# Requirments
* requirments helmfile v0.119.1, helm v3.2.4, k8s v1.16.9-gke.6
