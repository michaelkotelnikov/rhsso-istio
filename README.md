# RHSSO Istio

This repository shows how you can onboard Red Hat Single Sign On into Red Hat Service Mesh.

## Overview

In many cases, organizations want to be able to see traffic flows from and to the OIDC server. If the OIDC server is not a member of the mesh, it will be represented as `PassthroughCluster` and there will be no information about the connection. As shown in the below diagram -

![](images/rhsso-not-in-mesh.png)
