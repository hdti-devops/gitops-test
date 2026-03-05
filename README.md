```
helm install argocd argo/argo-cd --namespace=argocd --create-namespace --version 9.1.6 --set argo-cd.configs.cm."kust
omize\.buildOptions"="--load-restrictor LoadRestrictionsNone"
```