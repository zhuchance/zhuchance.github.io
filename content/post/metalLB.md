+++
+++

#### metalLB 负载均衡

用来给services暴露IP出来，规划一个集群同网段的IP出来，使用的时候services不能删除，这样方便对接公网的Load balance的nginx，
为了让k8s集群和旧的swarm集群能同时提供服务。
