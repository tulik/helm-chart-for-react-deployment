# Getting Started with Create React App

Check helm chars:
```
helm lint helm-chart
```
Install
```
helm install dev-release ./helm-chart/  --values helm-chart/config-values/config-dev.yaml
```
Apply changes
```
helm upgrade dev-release ./helm-chart/ --install --force --values helm-chart/config-values/config-dev.yaml
```
Delete
```
helm delete dev-release
```
