# AWS Cloud Infrastructure Solution for Medical Startup Application

## Introduction
The Medical Startup, a burgeoning software-as-a-service (SaaS) company, has ventured into the realm of online medical social networking and diagnosis assistance. The company's innovative application connects patients and doctors through virtual consultations, remote appointments, diagnostics, and prescription services. To support its anticipated growth and ensure efficiency, scalability, and security, the company aims to transition from traditional on-premise infrastructure to AWS cloud services.

## Executive Summary
The Medical Startup, previously relying on physical resources and hosting companies for infrastructure development and testing, is poised for a transformation. By adopting Amazon Web Services (AWS), the company seeks to enhance its infrastructure management, scalability, and security. This report outlines the AWS-based cloud solution, encompassing user authentication, network security, web and application tiers, business continuity, and auditing.

## Customer Requirements
* Configure Access Permissions: Align access permissions with AWS best practices.
* Build Network Architecture: Design network architecture that adheres to AWS best practices while supporting required network services.
* Scale Infrastructure: Design an architecture that can handle double the current number of servers.
* Ensure Security: Protect sensitive medical information with robust security measures.
* Utilize Load Balancers: Employ load balancers for web and application tiers supporting HTTP, HTTPS, and TCP protocols.
* Support Multiple Locations: Make the application accessible to users in the United States, Europe, and APAC regions.

## Solution Overview
* Identifying AWS Services: The architecture leverages a range of AWS services including AWS WAF, AWS CloudTrail, AWS Cognito, AWS Route 53, AWS CloudFront, AWS CloudWatch, AWS IAM, AWS S3, AWS Classic Load Balancer, AWS VPC, AWS EC2, AWS NAT Gateway, AWS Auto Scaling Group, AWS Application Load Balancer, AWS RDS, and AWS Availability Zones.

* User Authentication: IAM groups and roles are established for different user categories. Password policies and Multi-Factor Authentication (MFA) enhance security.

* Network and Security: The architecture achieves high availability, scalability, and security by deploying separate tiers for web, application, and database, utilizing multiple availability zones, and enforcing strict security groups.

* Web and Application Tier: Classic and application load balancers manage traffic distribution, ensuring the application remains accessible and responsive.

* Business Continuity: A master-slave database architecture across availability zones ensures continuous operation in case of failures. Auto Scaling ensures resources adapt to traffic fluctuations.

* Auditing: AWS CloudTrail, VPC flow logs, AWS Config, Amazon Cognito, and AWS CloudFront are utilized for comprehensive auditing of AWS resources and operations.

## Architecture Diagram
The AWS cloud architecture is designed to meet the Medical Startup's requirements for scalability, availability, security, and performance. The architecture incorporates separate development and production environments, multiple availability zones, and load balancing mechanisms.
![image](https://github.com/shreyask1406/AWS-Cloud-Architecting/assets/143536245/ef03233d-986d-41b8-92d2-5e45fbc0ff2d)



## Conclusion
The AWS cloud infrastructure solution offers the Medical Startup the means to seamlessly transition from on-premise infrastructure to a scalable and secure cloud environment. By utilizing a range of AWS services, adhering to best practices, and addressing specific requirements, the company can ensure the efficient and reliable operation of its medical social networking and diagnosis assistance application. The architecture encompasses high availability, scalability, security, and auditing, providing a solid foundation for the application's success and user satisfaction.

For a more detailed exploration of the architecture, implementation details, and the benefits of transitioning to AWS, please refer to the project's repository and documentation.
