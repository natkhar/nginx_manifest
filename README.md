# nginx_manifest
## Example using minikube
- Apply the manifest
![kubectl_apply](https://github.com/natkhar/nginx_manifest/assets/46851077/3f21b2c3-ea95-4ee6-9410-0dd19318b101)

- Check that the pod is up
![kubectl_get_pods](https://github.com/natkhar/nginx_manifest/assets/46851077/2afe7524-d248-4ca0-96d6-0a852c3b83e6)

-  Describe pod to see the container info (label, volume, port, etc.)
![kubectl_describe_pod](https://github.com/natkhar/nginx_manifest/assets/46851077/74b67620-2b33-4422-8db2-fa8e6e887000)

- Check the deployment and its selector
  ![kubectl_get_deployment](https://github.com/natkhar/nginx_manifest/assets/46851077/7f933cd1-413e-4678-ac19-e373a7b02063)

- Check the service and its selector
  ![kubectl_get_svc](https://github.com/natkhar/nginx_manifest/assets/46851077/56fb31c1-5d90-4be1-a20e-099021d2f439)

- Execute minikube command to get service URL
![minikube_get_service_url](https://github.com/natkhar/nginx_manifest/assets/46851077/fe6c8341-a5e2-4b9d-90c4-54781e82db0c)

- Check HTTP response
  
  ![http_output](https://github.com/natkhar/nginx_manifest/assets/46851077/4be29524-0139-4eb1-be7b-9ae5be266b16)
