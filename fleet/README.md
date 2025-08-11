# Manifests Example

This example will deploy the Azure Store Quickstart application.
The app will be deployed into the `fleet-manifest-example` namespace.

```yaml
kind: GitRepo
apiVersion: fleet.cattle.io/v1alpha1
metadata:
  name: manifests
  namespace: fleet-local
spec:
  repo: https://github.com/mcgonagle/aks_terraform
  paths:
  - fleet 
```
