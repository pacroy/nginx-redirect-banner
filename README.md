# nginx Redirect Banner Helm Chart

## Local Installation

```sh
helm install <release_name> . --namespace=<namespace> --values <values_file>
```

## Installation from Repository

```sh
helm repo add pacroy https://pacroy.github.io/helm-repo/
helm repo update
helm install <release_name> pacroy/nginx-redirect-banner --namespace=<namespace> --values <values_file>
```
