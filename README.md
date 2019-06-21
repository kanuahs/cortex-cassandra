Install cassandra using helm

```bash
helm install --name=test incubator/cassandra
```

Deploy cortex
```bash
kubectl apply -f k8s-cassandra
```