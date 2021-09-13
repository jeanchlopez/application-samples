# Deploy Crunchy postregs operator for keycloak app example
## Tool Requirements
- OpenShift CLI Version >= 4.3.0<br>_Needed for kustomize_

```bash
oc version
```

- Deployemnt parameters

When deploying the Crunchy postgres operator you *must* deploy in a namespace as `postgres-operator`.

The ACM application is free of choice.
