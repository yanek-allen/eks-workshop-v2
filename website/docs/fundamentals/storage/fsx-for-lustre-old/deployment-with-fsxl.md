---
title: Dynamic provisioning using FSx for NetApp ONTAP 
sidebar_position: 30
---

Now that we understand the FSxN storage class for Kubernetes let's create a [Persistent Volume](https://kubernetes.io/docs/concepts/storage/persistent-volumes/) and change the `assets` container on the assets deployment to mount the Volume created.
