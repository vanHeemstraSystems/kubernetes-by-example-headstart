# 100 - Pods

Based on "Pods" at https://www.kubernetesbyexample.com/en/concept/pods

A pod is a collection of containers sharing a network, acting as the basic unit of deployment in Kubernetes. All containers in a pod are scheduled on the same node.  

To launch a pod using the container [image](https://quay.io/repository/openshiftlabs/simpleservice/) ```quay.io/openshiftlabs/simpleservice:0.5.0``` and exposing a HTTP API on port 9876, execute:

more ...
