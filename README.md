# cf-templates

VPC1.yml : CF template that creates a VPC with Subnets, RoutingTables, IGW, NAT-GW, SG etc.

Validation1.yml: Launches workload in VPC1 with a ELB.

VPC2.yml: Create a second VPC VPC2. Peer VPC1 and VPC2 using VPC peering.

Validation2.yml: Launch workloads to verify the VPC peering functionality.

