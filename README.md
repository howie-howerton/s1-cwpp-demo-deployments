# s1-cwpp-demo-deployments
K8s deployment files for demos

Clone this repository:
```
git clone https://github.com/howie-howerton/s1-cwpp-demo-deployments.git
```

Change directories into the repository:
```
cd s1-cwpp-demo-deployments/<subdirectory_of_interest>
```

Apply to your K8s cluster with:
```
kubectl apply -f <name_of_deployment_file_here>.yaml
```

Delete from your K8s cluster with:
```
kubectl delete -f <name_of_deployment_file_here>.yaml
```
