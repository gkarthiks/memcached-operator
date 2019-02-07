# memcached-operator

memcached-operator is a *Kubernetes* operator for the *Memcached.* This is a study project to understand the *operator-sdk* that was opensourced by *RedHat* for ease of creating the k8s operator. Utilizing this SDK will create *CRD*s and *Operator Image* for the defined *CR*.

The user will be deploying the *CRDs* in the *kubernetes* cluster that is available [here](deploy/crds/memcached_v1alpha1_memcached_crd.yaml).


The **Operator Image** is available in the docker hub [here](https://hub.docker.com/r/gkarthics/memcached-operator/tags), using this the Operator is deployed into the k8s cluster via the k8s YAML files available [here](deploy/).