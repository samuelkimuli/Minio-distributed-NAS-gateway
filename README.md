# Minio-distributed-NAS-gateway

Running MinIO in a distributed NAS Gateway configuration requires additional work and is something to investigate in the future.

With a single node of that, it's an extra single point of failure so we suddenly have no advantage running two instances or more, and if we start clustering etcd then uh we'd have to adopt Swarm or K8s  on very short notic
