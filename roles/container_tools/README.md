Role Name
=========

Installs :

- buildah
- podman-compose
- packer
- terraform
- minikube
- skaffold
- kubectl

Requirements
------------

- Haven't found a clean way to add the hashicorp repo to dnf yet, this must be ran first :

```
sudo dnf config-manager --add-repo https://rpm.releases.hashicorp.com/fedora/hashicorp.repo
sudo dnf update
```

