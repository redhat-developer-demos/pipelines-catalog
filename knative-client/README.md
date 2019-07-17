# Knative Client Tasks

A set of Tekton pipeline tasks using [Knative Client](https://github.com/knative/client)

```shell
oc create -f pipeline-sa-roles.yaml -n <your-namespace>
oc policy add-role-to-user pipeline-roles -z pipeline --role-namespace=<your-namespace>
```
