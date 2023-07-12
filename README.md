# 🔑 Secure Supply Chain AKS

Learn how to use open-source tools to secure your container deployments on Azure Kubernetes Service.

👉 [Watch the MSBuild 2023 Talk](https://www.youtube.com/watch?v=Mep9QWc3ByE&t=1s) 

## Prerequisites

| | |
|----------------------|------------------------------------------------------|
| GitHub account       | [Get a free GitHub account](https://github.com/join) |
| Azure account        | [Get a free Azure account](https://azure.microsoft.com/free) |
| Azure CLI            | [Install Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) |
| Terraform            | [Install Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli) |
| Helm                 | [Install Helm](https://helm.sh/docs/intro/install/) |
| Docker               | [Install Docker](https://docs.docker.com/get-docker/) |
| kubectl              | [Install kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) |

## Overview

This project demonstrates how to deploy an Azure Kubernetes Service cluster and secure it using open-source tools. The project uses Terraform to deploy the Azure resources and Helm to configure the Kubernetes cluster. And then uses GitHub Actions to automate the deployment of the cluster and the configuration of the tools. 

After the cluster is deployed, you will learn how to use the following tools to secure your container deployments:

- [Notary](https://github.com/notaryproject/notary)
- [Trivy](https://github.com/aquasecurity/trivy)
- [Gatekeeper](https://github.com/open-policy-agent/gatekeeper-library)
- [Ratify](https://github.com/deislabs/ratify)


By the end of the workshop, you'll have leanred how to use these tools to secure your container deployments on Azure Kubernetes Service using Trivy to scan container images for vulnerabilities, Notary to sign container images, and Ratify to verify that the policies are being enforced.

## How to build the environment

```bash
cd terraform;
terraform init;
terraform apply
```


