# eksctl
a simple yaml for EKSCTL

- use cloudformation file attached to create a VPC and Subnets
	- change the region and names accordingly
- use the cluster-with/without-vpc.yaml to create EKS clusters
	- change the regions accordinly
	- provide the subnets and VPC id in with VPC yaml
	- "eksctl create cluster -f cluster-with/without-vpc.yaml" to create the cluster
- "kubernetes.io/cluster/$CLUSTER_NAME"
	- ensure that $CLUSTER_NAME should be the name in eksctl yaml and cloudformation yaml

 
