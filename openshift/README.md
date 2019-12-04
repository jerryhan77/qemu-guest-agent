# Install in Openshift 4.x

```
$ oc create -f qemu-ga.yml
$ oc adm policy add-scc-to-user privileged -n qemu-ga -z qemu-ga
```
