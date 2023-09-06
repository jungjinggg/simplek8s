### Update new image
```
kubectl set image <object_type>/<object_name> <container_name>=<new image to use>
```

```
kubectl set image deployment/client-deployment client=stephengrider/multi-client:v5
```