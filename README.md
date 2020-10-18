MLOps.Helm


# Installation of Helm
Follow steps here:
- https://helm.sh/docs/intro/install/

Add the .exe to your environment variables:
I located it at C:\Helm and added that to the PATH user  variable.

# Create a chart
`helm create mychart`

# Install kubectl

# Download kubeconfig from Rancher

# Install chart
`helm install $RELEASE_NAME ./mychart`


Annotations will contain:
- meta.helm.sh/release-name     full-coral