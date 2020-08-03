# Ticketing Application

## Dev Environment

The dev environment uses Skaffold to manage all the Kubernetes services and pods.

### Run local services

```bash
skaffold dev
```

## Dev Notes

```bash
# If ingress controller is not working, stop apache server
sudo apachectl stop

# If google throws error of security of page. Type the following anywhere on page.
thisisunsafe

# Creating ENV variables
kubectl create secret generic jwt-secret ---from-literal=JWT_KEY=value
```
