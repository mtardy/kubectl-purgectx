# Kubectl purgectx

Kubectl purge context removes the context from a kubeconfig file and its associated
user and cluster.

## Installation

Using curl:

```bash
curl -LO https://github.com/mtardy/kubectl-purgectx/raw/master/kubectl-purgectx
chmod +x ./kubectl-purgectx
sudo mv ./kubectl-purgectx /usr/local/bin/kubectl-purgectx
```

## Usage

```console
$ kubectl purgectx
usage: ./kubectl-purgectx <context-name>

available contexts:
CURRENT   NAME       CLUSTER    AUTHINFO   NAMESPACE
          minikube   minikube   minikube   default
```
