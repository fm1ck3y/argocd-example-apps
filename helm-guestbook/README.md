# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/fm1ck3y/argocd-example-apps
# cd into the cloned directory
git checkout 0a99e5399c6ad43a697d3a8efca680ad371ba99e
helm template . --name-template development-helm-guestbook --include-crds
```
