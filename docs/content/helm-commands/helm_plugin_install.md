+++
title = "helm plugin install"
weight = "25"

tags = ["commands"]
section = "helm-commands"
categories = ["helm-commands"]
type = "page"

slug = "helm-plugin-install"

[menu.main]
  url = "helm-plugin-install"
  parent = "helm-commands"

+++

## helm plugin install

install one or more Helm plugins

### Synopsis


install one or more Helm plugins

```
helm plugin install [options] <path|url>...
```

### Options

```
      --version string   specify a version constraint. If this is not specified, the latest version is installed
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
* [helm plugin](#helm-plugin)	 - add, list, or remove Helm plugins