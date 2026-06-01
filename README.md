# Using AWS CDK for Infrastructure as Code IAC

Published: 2024-09-23
Medium: [https://medium.com/@kyle-t-jones/using-aws-cdk-for-infrastructure-as-code-iac-00f7d1fd47cb](https://medium.com/@kyle-t-jones/using-aws-cdk-for-infrastructure-as-code-iac-00f7d1fd47cb)

## Business context

Infrastructure as Code (IaC) maintains and supplies computing infrastructure using machine-readable configuration files. IaC lets system managers and developers specify their infrastructure using code, which can be versioned, shared, and automated, much like application code. This method is essential in DevOps and contemporary cloud computing systems, giving infrastructure management uniformity, repeatability, and efficiency.

Infrastructure as Code uses of several tools, each with advantages and ecosystems.

- Terraform: Terraform, developed by HashiCorp, is one of the most popular IaC tools. It allows users to define infrastructure using a declarative language called HashiCorp Configuration Language (HCL). Being cloud-agnostic, Terraform can handle infrastructure across several cloud providers, including AWS, Azure, and Google Cloud. Because of this adaptability, Terraform is a great option for companies using multi-cloud approaches. - AWS CloudFormation: CloudFormation is AWS's native IaC tool, allowing customers to define and provision infrastructure using JSON or YAML templates. It tightly integrates with AWS services and will enable teams to manage AWS resources in a predictable and repeatable manner. It's ideal for organizations using AWS as their primary cloud provider. - Ansible: Unlike Terraform and CloudFormation, Ansible is more focused on configuration management, though it can also be used to provision infrastructure. Ansible uses YAML files to define playbooks, which automate tasks like setting up servers, installing software, and configuring network settings. Ansible is often used to automate the management of existing infrastructure rather than provisioning new infrastructure from scratch. - Chef and Puppet: These configuration management tools enable infrastructure provisioning through code. Like Ansible, they focus on automating server configurations and provide some capabilities for managing infrastructure at a higher level. They are often used in hybrid environments where cloud and on-premises infrastructure must be managed. - Kubernetes: While not strictly an IaC tool, Kubernetes uses declarative YAML files to define containerized applications' desired state and infrastructure. Kubernetes automates applications' deployment, scaling, and management, making it a crucial part of IaC strategies for organizations adopting container-based architectures.



## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).