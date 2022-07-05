# Mini-Microservices-App

## General
A simple micro-services app uses Node, Express, Docker, Kubernetes, Nginx-ingress, and Skaffold.

### Services include:
1. client
2. comments
3. event-bus
4. moderation
5. posts
6. query

### Infrastructure
Every micro-service has a docker file and K8S Deployment with ClusterIP YAML file. The Load Balancer is set with Ingress-Nginx and connected to the React client.
The docker files are sets with Skaffold.

### Run
`skaffold dev`
