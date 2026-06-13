# image-update-operator
An image update operator for Kubernetes

# Scope
The scope of this project is to create a Kubernetes operator that automatically updates a deployment's image tag based on a rule defined in a CRD.
This operator will check the image repository for a new tag and patch the deployment.
