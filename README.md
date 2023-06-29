# k3s-k8s-nginxingresscontroller-charts
a very easy used charts for deploy nginx-ingress-controller in k3s or k8s, optional to uninstall traefik


## how

just deploy this charts to your env, and follow the questions if use rancher or use helm to render the questions.

## tips

1. you can modify your own image in templates/daemonset.yaml that default use 'rancher/nginx-ingress-controller:nginx-0.35.0-rancher2'

2. if you decided to 'replaceTraefik', it will never back because it really deleted and i don't supply any restore methods.
