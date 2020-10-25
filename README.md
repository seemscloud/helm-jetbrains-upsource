# Helm JetBrains Upsource

## JetBrains Upsource Descriptions 

### Base Resources

| Name  | Image Name | Type | Kubernetes Resource |
| ------------- | ------------- | ------------- | ------------- |
| Frontend  | `jetbrains/upsource-frontend:2020.1.1815` | `scalable` | `deployment` | 
| PSI Agent | `jetbrains/upsource-psi-agent:2020.1.1815` | `scalable` | `deployment` | 
| Analyzer | `jetbrains/upsource-analyzer:2020.1.1815` | `scalable` | `deployment` | 
| Cassandra | `jetbrains/upsource-cassandra:2020.1.1815` | `not scalable` | `statefulset` | 
| Ops Center | `jetbrains/upsource-opscenter:2020.1.1815` | `not scalable` | `statefulset` | 
| PSI Broker | `jetbrains/upsource-psi-broker:2020.1.1815` | `not scalable` | `deployment` | 
| Proxy | `jetbrains/upsource-proxy:2020.1.1815` | `not scalable` | `deployment` | 
| File Clustering | `jetbrains/upsource-file-clustering:2020.1.1815` | `not scalable` | `deployment` | 

### Additional Resources
| Name  | Image Name | Type | Kubernetes Resource |
| ------------- | ------------- | ------------- | ------------- |
| Cluster Init  | `jetbrains/upsource-cluster-init` | `not scalable` | `deployment` | 

## References:
 - [Scaling Upsource services in the cluster﻿
](https://www.jetbrains.com/help/upsource/scaling-upsource-services-in-the-cluster.html)
 - [What's included﻿
](https://www.jetbrains.com/help/upsource/setting-up-upsource-cluster.html#what-s-included) 
 - [Upsource cluster hardware requirements﻿
](https://www.jetbrains.com/help/upsource/upsource-cluster-hardware-requirements.html)
