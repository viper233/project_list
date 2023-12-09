# project_list
List Projects that will be built out

= Single account projects

- AWS VPC with 3 subnet tiers across 3 AZs
- EKS cluster
- - esure subnets are ready
- - metrics server installed
  - ODIC configured for account access
  - manual worker node group
  - managed node group
  - - cluster autoscaler
    - karpenter
  - CSI
  - - local ebs storage class
    - EFS storage class
    - s3 storage class
  - CNI
  - - calico
    - others?
    - vpc-net security group configuration on pods
  - service account permissions for pod to access rds instance
  - Ingress
  - - nginx
  - falco
- Prometheus
- - k8s hosted
- Grafana
- - k8s hosted
- flux
- argoCD
- AWS eks clusters accross different VPCs
- - different regions
- vpc peering
- - network analyzer
  - iperf between clusters
- transit gateway
- - network analyzer
  - iperf
  - route associations
  - route propagations
  - egress vpc
  - egress vpc with alterNAT
  - vpc NACL/route configuration to limint TGW routing/egress/ingress
 
- cloudformation
- - vpc and subnets etc.
  - eks cluster
 
- terraform
- - everything else. Start with own code for eks cluster, then use registry modules
  - terragrunt for multi stage, multiregion cluster deployments etc.
- github action pipeline
- gitlab
- - repos, container registry, pipelines
  - tfsec, checkov
 
- docker/podman
- - basic python flask container
  - backent to AWS service, configure IAM service role
  - basic go container
  - basic nodejs container
 
- ecr registry
- - signed conatainers, operator to ensure signed, cosign?
    
    - 
