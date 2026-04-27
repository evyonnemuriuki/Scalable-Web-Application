# Scalable-Web-Application
Scalable Web Application with ALB and Auto Scaling. The project demonstrates best practices for compute scalability, security and cost optimization.

This is a two-tier architecture made up of **web tier** and **application tier**.
The web tier consists of an ALB connected to an ASG which has a predetermined number of instances to launch according to certain thresholds.

## Launch Template
The launch template is created to act as the source for what the AutoScaling group deploys. All the settings we need e.g. instance type, AMI are specified in this template.
