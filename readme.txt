nginx-deployment.yaml

This file defines:

    2 replicas of the Nginx container.
    nginx:latest as the container image.
    #$kubectl get pods -l app=nginx