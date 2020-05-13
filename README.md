# Helm charts

This repo contains charts that are not hosted originally created by SchubergPhilis but are not hosted in official helm repositories just yet.

```console
helm repo add schubergphilis https://raw.githubusercontent.com/schubergphilis/k8s-team-helm-charts/master/
helm repo update
helm install --name my-release schubergphilis/chart
```
