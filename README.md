# openshift-tinyproxy

```
$ oc new-project proxy \
    --description="<description>" --display-name="<display_name>"
$ oc new-app -f ./openshift.yml
$ oc start-build tinyproxy
```
