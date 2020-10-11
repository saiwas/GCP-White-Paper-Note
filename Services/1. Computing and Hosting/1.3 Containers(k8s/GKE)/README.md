# GKE(Google Kubernetes Engine)

A good choice for use cases that include the following:
+ Create and manage groups of Compute Engine instances running Kubernetes, called clusters. GKE uses Compute Engine instances as nodes in a cluster. Each node runs the Docker runtime, a Kubernetes node agent that monitors the health of the node, and a simple network proxy.

+ Declare the requirements for your Docker containers by creating a simple JSON configuration file.

+ Use Container Registry for secure, private storage of Docker images. You can push images to your registry and then you can pull images to any Compute Engine instance or your own hardware by using an HTTP endpoint.

+ Create single- and multi-container pods. Each pod represents a logical host that can contain one or more containers. Containers in a pod work together by sharing resources, such as networking resources. Together, a set of pods might comprise an entire application, a microservice, or one layer in a multi-tier application.

+ Create and manage replication controllers, which manage the creation and deletion of pod replicas based on a template. Replication controllers help to ensure that your application has the resources it needs to run reliably and scale appropriately.

+ Create and manage services. Services create an abstraction layer that decouples frontend clients from pods that provide backend functions. In this way, clients can work without concerns about which pods are being created and deleted at any given moment.

+ Create an external network load balancer.
