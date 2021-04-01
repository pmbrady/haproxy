This role will install and configure HAProxy to enable you to deploy a J8s cluster.

You must configure your HAProxy host and k8s hosts in your inventory as follows.

    haproxy:
      hosts:
        iomplprdhap01: