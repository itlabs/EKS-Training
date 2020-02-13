# Kubernetes on AWS
## Using Amazon Elastic Kubernetes Service
Materials Created by me, [@vallard](https://twitter.com/vallard)

### ⚠️ THIS IS A WORK IN PROGRESS AND WILL BE COMPLETE BY FEB 25, 2020. ⚠️

✅ Most of the materials are not yet uploaded but will be soon!


## Contents

### Segment 1 - Introduction / Foundations
* Introduction
* Big Picture Overview
* Clone Github Resources
* Benefits of Kubernetes on AWS
* [Install `kubectl`](segment1/kubectl.md)



### Segment 2 - IAM
* Create IAM Policies
* Create IAM Group
* Create IAM Roles
* Create IAM User
* [AWS Setup](segment02-iam/aws-creds.md)
* [Install `eksctl`](segment02-iam/eksctl.md)


### Segement 3 - Launch EKS
* [Launch the EKS cluster with eksctl](segment03-install/eks.md)
* Apply `ConfigMaps` to join nodes to the cluster
* `kubectl` access

### Segment 4 - Cluster Verification
* [Verify components and launch sample test application](segment04-verify/README.md)


### Segment 5 - Launch Applications
* [Persistent Volumes](segment05-apps/PV.md)
* Create an Network Loadbalancer for accessing the cluster
* Configure R53 DNS to point to the ELB
* Install NGINX ingress controller for TLS certificates
* Access applications secure via https://

### Segment 5 - Cluster Lifecycle
* Demonstrate adding additional users to login to cluster
* Cluster Autoscaling
* Upgrading cluster

### Segment 6 - Connecting to additional AWS services
* lambda functions to run something on EKS cluster
* Jobs on EKS access DynamoDB and S3

### Segment 7 - Wrap up and Questions
* Additional feedback, etc. 

