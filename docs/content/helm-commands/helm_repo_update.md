+++
title = "helm repo update"
weight = "33"

tags = ["commands"]
section = "helm-commands"
categories = ["helm-commands"]
type = "page"

slug = "helm-repo-update"

[menu.main]
  url = "helm-repo-update"
  parent = "helm-commands"

+++

## helm repo update

update information on available charts in the chart repositories

### Synopsis



Update gets the latest information about charts from the respective chart repositories.
Information is cached locally, where it is used by commands like 'helm search'.

'helm update' is the deprecated form of 'helm repo update'. It will be removed in
future releases.


```
helm repo update
```

### Options inherited from parent commands

```
      --debug                     enable verbose output
      --home string               location of your Helm config. Overrides $HELM_HOME (default "~/.helm")
      --host string               address of tiller. Overrides $HELM_HOST
      --kube-context string       name of the kubeconfig context to use
      --tiller-namespace string   namespace of tiller (default "kube-system")
```

### SEE ALSO
* [helm repo](#helm-repo)	 - add, list, remove, update, and index chart repositories