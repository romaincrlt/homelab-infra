# Homelab-Infra
Homelab-infra

## Introduction

This repo contain the configuration for my Kubernetes infrastucture components.

The purpose is to try and learn new things but also to self host some applications.


### Composition

The cluster run on a single node k3s server.
AlmaLinux is used as host OS provisioned with Ansible.
Then FluxCD is install pointing to this repo.

Storage is provisioned with k3s local-path and local-storage for my data on an USD device.

Dev cluster is usaually virtual machines.


### Principes

I'm trying to keep it simple and minimalist.
