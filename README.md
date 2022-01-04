# testing dynamic, static provisioning on pvc

## dynamic
1. appply pvc-dynamic.yaml

## static
1. creating storage account and file share
2. eplace the key and account name in secret-static.yaml
3. replace share name in pv-static.yaml
4. apply secret-static.yaml >> pv-static.yaml >> pvc-static.yaml >> pvc-static-pod.yaml