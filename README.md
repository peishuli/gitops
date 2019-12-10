# A Cloud-Native GitOps Reference Architecture
GitOps has emerged as one of the best practices for delivering Kubernetes applications. However, it is very challenging to get it right when it comes to implementing GitOps. 

## Goals
- To provide a GitOps reference architecture so that you can mix and match from the GitOps tool chain to meet unique requirements of your organization. 
- To provide a roadmap for adopting GitOps in your organization
- To provide to end-to-end implementation of an executable GitOps workflow, using Tekton as the CI pipeline and Argo CD (and switch to Argo Flux once it becomes available) to deploy the Hipster Shop sample microservcies application provided by Google Cloud Platform team.

## Non-Goals
This project does not cover the following areas:
- Kubernetes cluster creation: you can use any configuration management tools (e.g., Terraform, Ansilbe, etc.) or cloud provider specific CLI tool or scripts for Kubernetes cluster provisioning.
- Git Branching Strategies: you can use whatever branching strategies that works for your organization.
- CI tools: GitOps focus on the CD aspect of the CI/CD pipeline and is decopuled from the CI processes/tools. You can any CI tools that works for your organization. 

We do discuss Progressive Delivery in this project, however.

## The Architecture
<img src="https://user-images.githubusercontent.com/22537533/70003646-6f196880-1529-11ea-9e43-c6d494c71ca7.png" alt="architecture" width="55%" />

## The Roadmap
<img src="https://user-images.githubusercontent.com/22537533/69999200-b0a41680-151d-11ea-959b-5c088af4c437.png" alt="roadmap" width="50%" />

### First Stop - Choose Your Git Provider

### Second Stop - Choose Your CI Tool

### Third Stop - Choose Your GitOps Tool

### Fourth Stop - Choose Your Poressive Delivery Tool

## A Reference Implementation
<img src="https://user-images.githubusercontent.com/22537533/69929016-26a76f80-1483-11ea-8a59-776f84c48acd.png" alt="impl" width="50%" />

