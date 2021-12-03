# Notes-03-Cloud-Global-Infrastructure
Notes 03: Cloud Global Infrastructure

## Cloud infrastructure #
Describes the components and resources needed for cloud computing. You can create a private cloud by building it yourself using resources dedicated solely to you. Or you can use a public cloud by renting cloud infrastructure from a cloud provider like Alibaba, Amazon, Google, IBM, or Microsoft. And by incorporating some degree of workload portability, orchestration, and management across multiple clouds you can create a hybrid cloud.

The AWS infrastructure has been architected to be flexible and secure cloud computing environments. Is also designed to provide an extremely scalable and highly reliable platform that enables customers to deploy applications and data quickly and securely.

This infrastructure is built and managed not only according to security best practices
and standards, but also with the unique needs of the cloud in mind. AWS uses
redundant and layered controls, continuous validation and testing, and a substantial
amount of automation to ensure that the underlying infrastructure is monitored and
protected 24x7. AWS ensures that these controls are replicated in every new data
center or service.

Customers  get a resilient infrastructure, designed for high security, without the capital outlay and operational overhead of a 
traditional data center.


### AWS Global Infrastructure Terminology

##### AWS Regions 
Separated geographic areas that AWS uses to house its infrastructure. These regions are distributed around the world for customers to choose the region closest to them to host their cloud infrastructure. The closer region the better to reduce latency.

##### Best practices for choosing AWS Regions
		Proximity
		Services
		Cost
		Service Level Agreement (SLA)

AWS Availability Zones (AZ)
Is the logical building block that makes up an AWS Region. There are 76 AZ’s which are isolated locations or data centers, within a region. 

#### Edge Locations >> # of Availability Zones  >>> # of Regions


##### AWS Infrastructure is Elastic and Scalable, resources can adjust to increases or decreases in capacity requirements. 
