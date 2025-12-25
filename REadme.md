# Gateway api
Gateway api is solved a same problem that Ingress solve like nort-south traffic. But Gateway api's trying to solve a problem by addressing Drawback of Ingress.

# Components in Kubernetes Gateway
Kubernetes community provide 3 custome resources which add an advantages.
- Gateway class
- Gateway resources
- Http route 

## Gateway
Gateway class just like Ingress controller, whenever Platform engineer creates gateway controller e.g (Envoy, Nginx, Traefic) then they will create Gateway class resorces. 

## Gateway resources
Gateway resources defines which Gateway class will be used 

# Http route
Http route defines backend service configuration, on which port should be accessed, on which path, waf, canary, should be accessed. 
it defines production grade feature that you need in load balancer ande verything is supported by Http route. 