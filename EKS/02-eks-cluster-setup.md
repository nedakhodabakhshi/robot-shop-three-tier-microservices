# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster-three-tier-1 --region us-east-1
```
## Step 1: Create EKS Cluster

![Create EKS](screenshots/01-creat-eks.png)

## Step 2: Verify Cluster

![Cluster Running](screenshots/02-aws-cluster-robotshop.png)

## Step 3: Worker Nodes

![Worker Nodes](screenshots/03-worker-nodes.png)

## Delete the cluster

```
eksctl delete cluster --name demo-cluster-three-tier-1 --region us-east-1
```



