# k8s-configs

This repository stores Kubernetes manifests for all services.

Structure:

- base/: cluster-wide objects (namespaces, storageclass, secrets)
- apps/: each service has its own directory with deployment + service
- ingress/: ingress routes

You can apply everything with:

