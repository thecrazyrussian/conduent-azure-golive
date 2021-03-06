# Conduent Go-Live Training v2 Labs - Labs
These labs have been customized to illustrate rancher usage using Conduent's work current and planned workflow.

## Organization
The labs follow the in-person lesson breakdown and highlights areas of functionality. These labs should be completed in sequence and some depend on the previous lab's infrastructure and Rancher UI being online.

## Requirements

### Applications
This lab has been tested with the following application versions, it may work with others but that is not guaranteed.
- helm 2
- azure cli 2.2
- rancher cli 2.3
- kubectl 2.3.2
- docker 19.03
- rke  >= 1.0.8 

### Hosting Environment
Full Access to Empty Azure Account *

Usage in a utilized account could unintentionally effect existing infrastructure.

## Lab Outline

### Section 2 : Cluster Management With Rancher
#### 2.1 Rancher Setup
- 2.1.6 LAB: Create RKE on Azure Cluster

#### 2.2 Rancher CLI
- 2.2.2 LAB: Adding and Moving Namespaces

#### 2.3 Deploying Clusters with Rancher
- 2.3.2	LAB: Add AKS Cluster via Rancher UI
- 2.3.4	LAB: Import Cluster via Rancher UI
- 2.3.5 LAB: Import Cluster via Rancher CLI
- 2.3.6 LAB: Add RKE Cluster via Rancher UI

#### 2.4 RBAC /w Azure AD
- 2.4.3	LAB: Connect AKS Rancher Azure Active Directory

#### 2.5 Projects & Namespaces
- 2.5.1	LAB: Projects via Rancher UI
- 2.5.2	LAB: Namespaces via Rancher UI
- 2.5.3	LAB: Limits via Rancher UI

#### 2.6 PVC & Storage Classes
- 2.6.2	LAB: Add Azure Storage Class via Rancher UI

#### 2.7 Monitoring
- 2.7.5	LAB: Setting Up Persistent Storage for Grafana & Prometheus

### Section 3 : Kubernetes Fundamentals
#### 3.1 Jobs
- 3.1 LAB: Setup and run a sample job.

#### 3.2 Cron Jobs
- 3.2 LAB: Setup sample cron job.

#### 3.3    CRDs
- 3.3 LAB: Example CRD setup

### Section 4 : Security
#### 4.2 Pod Security Policies
- 4.2.1 LAB: Update local RKE cluster to enable Pod Security Policies.
- 4.2.2 LAB: Deploy a Deployment with Pod Security Policy.

### Section 5 : Operational Usability
#### 5.1 Debugging Workloads
- 5.1.3.3 LAB: Add sidecar to a workload.

#### 5.3 Scaling AKS
- 5.3.3 LAB: Add HPA to Deployment

#### 5.4 Out of Resource Handling
- 5.4.1.5 LAB: Resource prioritization, implement workloads
