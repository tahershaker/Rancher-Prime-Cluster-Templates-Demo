# Rancher AWS Cluster Template - Medium Size

This is a Helm Chart to be used with Rancher Prime providing a cluster template. This Helm chart can be used with Rancher to provide a fast provisioning for clusters. This cluster template is based on a pre-defined parameters addressing the size and type of cluster.

This template will deploy an RKE2 Cluster on top of AWS EC2 instances with the following parameters:
- Number of Master (Control Plan) Nodes: `1`
- Number of Worker Nodes:                `2`
- Kubernetes distribution:               `RKE2`
- Kubernetes Version:                    `v1.26`
- Operating System:                      `SLES 15 SP5`
- EC2 Instance Size:                     `t3a.xlarge`
- AWS Region:                            `eu-west-2`
- Subnet CIDR:                           `10.10.13.0/24`

---
