# Kubernetes Cluster Setup

### 1. setup kubernetes cluster
```shell script
vagrant up
```
### 2. Setup KUBECONFIG
```shell script
  export KUBECONFIG="${PWD}/ansible-playbooks/config"
```
### 3. destroy kubernetes cluster
```shell script
vagrant destory
```
