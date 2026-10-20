# Bookish Carnival

GitOps lab on a three-node RKE2 cluster.

- Argo CD manages Kubernetes resources from Git.
- KrakenD routes requests to two backends and aggregates their responses.

## Structure

- argocd/: Argo CD Application manifest
- manifests/: Kubernetes application manifests
