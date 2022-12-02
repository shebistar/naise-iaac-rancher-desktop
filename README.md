# naise-iaac-rancher-desktop

## Environment Overview:

![Rancher Desktop Architecture Overview](images/RancherDesktopOverview.png)

# Pre-requisites

## Install Rancher Desktop from https://rancherdesktop.io

## Clone this repo to get access to the files

    git clone https://github.com/shebistar/naise-iaac-rancher-desktop


## Create Kubernetes resources using Rancher Desktop Dashboard GUI

Open Rancher Desktop Dashboard and create the namespace using the file [00_namespace.yaml](kubernetes/00_namespace.yaml) and the option Import YAML on the main screen:


![Rancher Desktop Dashboard Overview](images/RancherDesktop.png)

Repeat the same process with files [01_app-naise_pvc.yaml](kubernetes/01_app-naise_pvc.yaml), [02_app-naise_deployment.yaml](kubernetes/02_app-naise_deployment.yaml) and [03_app-naise_service.yaml](kubernetes/03_app-naise_service.yaml)





