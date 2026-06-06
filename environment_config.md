# Configurations

If you would work on the dev spaces sandbox on developers.redhat.com, then you would require the installation of the
argo rollouts and kustomize plugin.

## OC Argo Rollouts Plugin
```shell
curl -LO https://github.com/argoproj/argo-rollouts/releases/latest/download/kubectl-argo-rollouts-linux-amd64
chmod +x ./kubectl-argo-rollouts-linux-amd64
sudo mv ./kubectl-argo-rollouts-linux-amd64 ./kubectl-argo-rollouts
```

## Kustomize
```shell
curl -s "https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/hack/install_kustomize.sh" | bash
```