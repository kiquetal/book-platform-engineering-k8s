#### Apply nginx ingress controller

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/release-1.8/deploy/static/provider/kind/deploy.yam


#### Install the application


helm install conference oci://docker.io/salaboy/conference-app --version v1.0.0
