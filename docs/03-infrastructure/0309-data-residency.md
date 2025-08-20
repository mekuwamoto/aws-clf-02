---
sidebar_position: 9
---

# Data Residency

## What is Data Residency?
Data Residency is a physical geographic location where an organization or cloud resources reside

## What is Compliance Boundaries?
It is a regulatory compliance by a government or organization that describes where data and cloud resources are allowed to reside

## What is Data Sovereignty?
Data Sovereignty is the jurisdictional control oor legal authority that can be asserted over data because it's physical location is within jurisdictional boundaries


For workloads that need to meet compliance boundaries strictly defining the data residency of data and cloud resources in AWS, you can use:
- **AWS Config** is a policy as code service. You can create rules to continuous check AWS resources configuration. If they deviate from your expectations, you are alerted or AWS Config can in some cases auto-remediate
- **AWS Outposts** is a **physical rack of servers** that you can put in your datacenter. Your data will reside wherever the outpost physically resides
    - ![aws outpost](./img/outpost.jpg)
- **IAM Policies** can be written explicitly to deny access to specific AWS Regions