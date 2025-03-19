# datadog-bt
```
helm repo add datadog https://helm.datadoghq.com
helm install datadog-operator datadog/datadog-operator
kubectl apply -f datadog-agent.yaml
```

## File based logging
- https://docs.datadoghq.com/containers/kubernetes/log/?tab=datadogoperator#recommended-configurations