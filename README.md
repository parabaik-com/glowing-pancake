# Cluster version
``` kubectl version ```
## Minikube
```
Client Version: version.Info{Major:"1", Minor:"20", GitVersion:"v1.20.4", GitCommit:"e87da0bd6e03ec3fea7933c4b5263d151aafd07c", GitTreeState:"clean", BuildDate:"2021-02-18T16:12:00Z", GoVersion:"go1.15.8", Compiler:"gc", Platform:"linux/amd64"}
Server Version: version.Info{Major:"1", Minor:"20", GitVersion:"v1.20.2", GitCommit:"faecb196815e248d3ecfb03c680a4507229c2a56", GitTreeState:"clean", BuildDate:"2021-01-13T13:20:00Z", GoVersion:"go1.15.5", Compiler:"gc", Platform:"linux/amd64"}
```
## Docker Desktop
```
Client Version: version.Info{Major:"1", Minor:"20", GitVersion:"v1.20.5", GitCommit:"6b1d87acf3c8253c123756b9e61dac642678305f", GitTreeState:"clean", BuildDate:"2021-03-18T01:10:43Z", GoVersion:"go1.15.8", Compiler:"gc", Platform:"windows/amd64"}
Server Version: version.Info{Major:"1", Minor:"22", GitVersion:"v1.22.5", GitCommit:"5c99e2ac2ff9a3c549d9ca665e7bc05a3e18f07e", GitTreeState:"clean", BuildDate:"2021-12-16T08:32:32Z", GoVersion:"go1.16.12", Compiler:"gc", Platform:"linux/amd64"}
```
## Jelastic
```
Client Version: version.Info{Major:"1", Minor:"21", GitVersion:"v1.21.6", GitCommit:"d921bc6d1810da51177fbd0ed61dc811c5228097", GitTreeState:"archive", BuildDate:"2021-12-0
8T15:17:50Z", GoVersion:"go1.16.9", Compiler:"gc", Platform:"linux/amd64"}
Server Version: version.Info{Major:"1", Minor:"21", GitVersion:"v1.21.6", GitCommit:"d921bc6d1810da51177fbd0ed61dc811c5228097", GitTreeState:"archive", BuildDate:"2021-12-0
8T15:09:47Z", GoVersion:"go1.16.9", Compiler:"gc", Platform:"linux/amd64"}
```
-----------------------------------------------
``` kubectl cluster-info ```
## Minikube
```
Kubernetes control plane is running at https://172.17.0.11:8443
KubeDNS is running at https://172.17.0.11:8443/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy
To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
```
## Docker Desktop
```
Kubernetes control plane is running at https://kubernetes.docker.internal:6443
CoreDNS is running at https://kubernetes.docker.internal:6443/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy
To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
```
## Jelastic
```
Kubernetes control plane is running at https://k8sm.parabaik.in1.cloudjiffy.net:6443
CoreDNS is running at https://k8sm.parabaik.in1.cloudjiffy.net:6443/api/v1/namespaces/kube-system/services/kube-dns:dns/proxy
To further debug and diagnose cluster problems, use 'kubectl cluster-info dump'.
```
-------------------------------------------------
``` kubectl get node```
## Minikube
```
NAME       STATUS   ROLES                  AGE   VERSION
minikube   Ready    control-plane,master   24m   v1.20.2
```
## Docker Desktop
```
NAME             STATUS   ROLES                  AGE   VERSION
docker-desktop   Ready    control-plane,master   8d    v1.22.5
```
## Jelastic
```
NAME                                    STATUS   ROLES                  AGE   VERSION
node92718-parabaik.in1.cloudjiffy.net   Ready    <none>                 43h   v1.21.6
node92719-parabaik.in1.cloudjiffy.net   Ready    control-plane,master   43h   v1.21.6
```
------------------------------------------------
```
kubectl create deployment kubernetes-bootcamp --image=gcr.io/google-samples/kubernetes-bootcamp:v1
```
## Minikube
```
deployment.apps/kubernetes-bootcamp created
```
## Docker Desktop
```
deployment.apps/kubernetes-bootcamp created
```
## Jelastic
```
deployment.apps/kubernetes-bootcamp created
```
