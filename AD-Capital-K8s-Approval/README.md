# AD-Capital-K8s-Approval-

This directory contains the modifications required to instrument the AD-Capital Approval node using the init container method for the Java Agent.

The files `adcap-approval-deployment.yaml`, `appdynamics-common-configmap.yaml` and `appdynamics-secrets.yaml` will need to be modified to make this work.

Deploy this new Pod using the command:

`kubectl create -f adcap-approval-deployment.yaml`
