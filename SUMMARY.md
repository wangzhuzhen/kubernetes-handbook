# Summary

- [前言](README.md)
- [1. Kubernetes简介](introduction/index.md)
  - [1.1 核心概念](introduction/concepts.md)
  - [1.2 Kubernetes 101](introduction/101.md)
  - [1.3 Kubernetes 201](introduction/201.md)
  - [1.4 Kubernetes集群](introduction/cluster.md)
- [2. 核心原理](architecture/index.md)
  - [2.1 设计理念](architecture/concepts.md)
  - [2.2 主要概念](architecture/objects.md)
    - [2.2.1 Pod, Service, Namespace和Node](introduction/concepts.md)
    - [2.2.2 Service](architecture/Service.md)
    - [2.2.3 Volume和Persistent Volume](architecture/Volume.md)
    - [2.2.4 Deployment](architecture/deployment.md)
    - [2.2.5 Secret](architecture/Secret.md)
    - [2.2.6 StatefulSet](architecture/statefulset.md)
    - [2.2.7 DaemonSet](architecture/daemonset.md)
    - [2.2.8 ServiceAccount](architecture/serviceaccount.md)
    - [2.2.9 ReplicationController和ReplicaSet](architecture/replicaset.md)
    - [2.2.10 Job](architecture/job.md)
    - [2.2.11 CronJob](architecture/cronjob.md)
    - SecurityContext
    - Resource Quota
    - Pod Security Policy
    - Horizontal Pod Autoscaling
    - Network Policy
    - Ingress
    - ThirdPartyResources
  - [2.3 核心组件的工作原理](components/index.md)
    - Etcd
    - API Server
    - Scheduler
    - Controller Manager
    - Kubelet
    - Kube Proxy
    - Kube DNS
    - hyperkube
    - Federation
    - [kubeadm](architecture/kubeadm.md)
- [3. 插件指南](plugins/index.md)
  - [3.1 认证和授权插件](plugins/auth.md)
  - [3.2 网络插件](plugins/network.md)
  - [3.3 Volume插件](plugins/volume.md)
  - [3.4 Container Runtime Interface](plugins/CRI.md)
  - 3.5 Network Policy
  - 3.6 Ingress Controller
  - 3.7 Cloud Provider
  - 3.8 Scheduler
  - [3.9 其他](plugins/other.md)
- [4. 常用技巧](deploy/index.md)
  - [4.1 部署](deploy/index.md)
    - [4.1.1 单机部署](deploy/single.md)
    - [4.1.2 集群部署](deploy/cluster.md)
    - [4.1.3 kubeadm](deploy/kubeadm.md)
    - [4.1.4 附加组件](addons/index.md)
  - [4.2 监控](monitor/index.md)
  - [4.3 日志](deploy/logging.md)
  - [4.4 高可用](ha/index.md)
  - [4.5 调试](debugging/index.md)
- [5. 开发指南](dev/index.md)
  - [5.1 开发环境搭建](dev/index.md)
  - [5.2 单元测试和集成测试](dev/testing.md)
  - [5.3 社区贡献](dev/contribute.md)
- [6. 应用管理](apps/index.md)
  - [6.1 Helm](apps/helm-app.md)
  - [6.2 Deis workflow](apps/deis.md)
- [7. 附录](appendix/index.md)
  - [7.1 awesome-docker](appendix/awesome-docker.md)
  - [7.2 awesome-kubernetes](appendix/awesome-kubernetes.md)
  - [7.3 Kubernetes ecosystem](ecosystem.md)
  - [7.4 参考文档](reference.md)
