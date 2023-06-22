# k9s-docker
## Make sure kubeconfig was created and k8s cluster is accessible
```bash
docker run --it --privileged -v ~/.kube/config:/root/.kube/config quay.io/derailed/k9s
```

## Tips
| Action        | Description        | Examples |
| :---          | :---               | :---     |
| /<keyword>    | Filter selection   | /abc     |
| :<searchword> | kubectl get deploy | :deploy  |
