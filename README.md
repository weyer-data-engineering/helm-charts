# helm-charts

Lint helm chart
```
helm lint charts/aiteza-frontend

helm lint charts/aiteza-backend
```

Test templating
```
helm template -f charts/aiteza-frontend/test-values.yaml charts/aiteza-frontend

helm template -f charts/aiteza-backend/test-values.yaml charts/aiteza-backend
```