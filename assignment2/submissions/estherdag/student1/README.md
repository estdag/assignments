## My name is Estherdag I work with Stellar1 Outcomer and please file below my submission

## Kubernetes, Docker, Containerisation and Virtualisation

1. VMs and Containers emulate entire computer systems including the hardware by running a hypervisor. The benefit of these two categories of tools for working with images, is that they run on top of the hypervisor and can only see the virtualized hardware, staying isolated from the host machine and other VMs, and run the same in any environment.  Running separate OS for each VM incurs a lot of CPU and memory usage, and this a drawback in itself.                        With Containers, there is less security compared to VMs despite isolation.                                                        Docker image is a server templating tool that is used to capture an OS, Sofware, files, and all relevant details; then use other Iac tools like Ansible to install that image on other servers                          Docker container is a software platform that enables us to build, test and deploy applications faster. Docker packages Software into standardized units called container. Kubernetes allows you to define how to manage Docker containers as code. To run this, you first deploy a kubernetes cluster, which is a group of servers used to run Docker containers. Most cloud providers have support for deploying managed kubernetes clusters such as: EKS, GKE, AKS 

## Linux administration and shell scripting

1. XXXX

## CICD, Infrastructure as as Code (IaC), Terraform, Packer and Ansible

1. 1.Idempotence is any function that can be executed several times without changing the final result beyond its first iteration.
2.What are the benefits of adopting a DevOps way of working for an organisation?
a.Renews focus on the customers
b.Unites teams for faster product shipments
c.Simplifies development focus
d.Introduces automation to the development process
e.Supports end-to-end responsibility

3.What are the benefits of provisioning infrastructure using tools like Terraform and Ansible?
a.Infrastructure visibility, b.Compliance,c.Business continuity,d.Cloud operations ,e.Cloud migration
f.Infrastructure orchestration. g.Automated troubleshooting.

4.Some provisioning and configuration management tools require the installation of agents on managed servers. Can you list the advantages and disadvantages of tools based on agents?
a. Advantages:Lesser bandwidth requirement: Agent-based architecture reduces bandwidth requirements by collecting data locally and only transmitting processed results.Security: There is an increasing focus on security and its necessity in the development process. It’s one disadvantage with agentless environments 
b.disadvantages:it’s impossible to get information about an application’s current state or to enforce the desired state for optimal operation and performance. For example, an uninformed user may modify the machine to the extent that it suffers a security vulnerability, not noticing it until the very last minute.he complexity of developing applications rises as organizations adopt containerized microservices and data centers. As a monitoring tool, agent-based environments deploy monitoring software in all servers across the entire architecture. The agents collect data using a variety of APIs and system calls. Afterward, review log files, as well as other proprietary sources. A central monitoring server then receives the information from these agents, tabulates the results, checks thresholds and alarms, and provides users with the results.

5.Compare and contrast mutable and immutable infrastructures design paradigms.
PROS     MUTABLE Infrastructure           Immutable Infrastructure
      a Fix problems more quickly         Discrete Versioning
      The infrastructure can fit the specific need   testing is easier
      Updates are usually faster                     predictable state
CONS  a.Technical issues are difficult to diagnose The infrastructure is unable to be modified in place
   changes to the servers are not necessarilty documented.Improved agility and dynamism of immutable inf
   Updates failures

6.Name some commercial and enterprise tools and the circumstances under which you would recommend them.
Configuration Management Tools (CMT) 

Ansible, Chef and Puppet are tools design to install and manage software on existing servers. Ansible, for example, enforces a coding convention that is consistent, has predictable structure, including documentation, file layout named parameters, secrets management and many more. Most functions of these CMT tools are idempotent by default and are design to manage large numbers remote servers. CMT would be a good fit for businesses that possess or manage a huge number of servers. 

Server Templating Tools (STT) 

Docker, Packer, and Vagrant etc. are alternative to CMT and enable you to create an image of a server that captures a fully self-contained snapshot of the OS, Sofware, files, and all relevant details. You can then use other Iac tools like Ansible to install that image on other servers. Two main categories of tool for working with images: VMs and Containers. These can be recommended for an organization that 

Orchestration Tools (OT) 

Tools such as Kubernetes, Amazon ECS, Docker Swarm etc.  

Used to deploy VMs and containers, roll out updates to existing fleet of VMs and Containers using strategies such rolling deployment, blue-green deployment and canary deployment. 

Monitor the health of VMs and Containers, auto scaling, load balancing and service discovery. 

Provisioning Tools 

While CMT, STT, AND OT define code that runs each server, provisioning tools such as Terraform, Cloud Formation, OpenStack Heat and Pulumi creates the servers, databases, caches, load balancers, ques, subnet configurations firewall routing rules, Secure Sockets Layers (SSL) certificates and other aspects of infrastructure. 

7.What do you understand by imperative and declarative way of provisioning infrastructure?
In declarative programming, you specify the name and properties of the infrastructure resources you wish to provision, and then the IaC tool figures out how to achieve that end result on its own. You declare to your IaC tool what you want, but not how to get there. Some examples of popular IaC tools that use the declarative programming paradigm include Terraform, Puppet, Ansible, Salt, and CloudFormation.
In imperative programming, you specify a list of steps the IaC tool should follow to provision a new resource. You tell your IaC tool how to create each environment using a sequence of command imperatives. Chef is a popular imperative IaC tool, and both Ansible and Salt have some support for imperative programming as well.

8.Describe the role that GitHub Actions plays in a fully automated CICD integrated toolchain?
GitHub Actions is a platform for continuous integration / continuous delivery (CI/CD). It enables you to automate build, testing, and deployment pipelines. It also lets you run arbitrary code on a specified repository when an event occurs. Actions uses code packages in Docker containers that run on GitHub servers. They are compatible with all programming languages to ensure you can run them on public clouds as well as local servers.

9.What is a Runner in the context of a provisioning pipeline?
Runners allows you to run builds in Pipelines on your own infrastructure,

10.What GitHub Action code syntax would you implement to trigger a GitHub Action workflow upon a pull request on a codebase?
GitHub Actions uses YAML syntax to define the workflow. Each workflow is stored as a separate YAML file in your code repository, in a directory named .github/workflows.

11.In the context of GitHub Actions, what are actions and where might you obtain them?
An Action is a package you can import and use in your workflow. GitHub provides an Actions Marketplace to find actions to use in workflows.
On GitHub.com, navigate to the main page of the repository. Under your repository name, click Actions. In the left sidebar, click the workflow you want to see. From the list of workflow runs, click the name of the run to see the workflow run summary.


## System Architecture and Application Design, Cloud Computing (AWS)

1. XXXX


## Site Reliability Engineering (SRE), Troubleshooting, Observability

1. Your manager asked you to run a script that is unfamiliar to you. How are you going to go about ensuring that this operation is done safely?

Ans: Ask your manager what the script does and what are the behaviour when run.



## DevOps and Agile Transformation principles and methodology

1. Learn Linux,Learn How Infrastructure Components Work,Learn Cloud Computing & Virtualization,arn Infrastructure Automation,Learn Container Orchestration and Distributed Systems,Logging & Monitoring & Observability,Learn Security Best Practices (DevSecOps),Learn Coding & Scripting,Learn Git, GitOps & Learn to Document

2. I agree totally.........getting remote job can be challenging but not impossible

3. XXXX

4. XXXX


## New commands logs - Enter up to ten new commands you have learnt this week

| Number      | Commands | What does it do and how might you check its effect     |
| :---        |    :----:   | :---  |
| 1  | terraform init     | initialize directory, pull down providers  |
| 2  | .terraform apply      | apply changes   |
| 3  | terraform destroy --auto-approve      | destroy/cleanup deployment without being prompted for “yes  |
| 4  | terraform version.       | display Terraform binary version, also warns if version is old   |
| 5  | terraform plan      | output your plan to apply it later  |
| 6  | Terraform validate       | catch syntax errors, version errors, and other issues   |
| 7  | git clone        | This will make a copy of the project to your local workspace so you can start working with it.  |
| 8  | Git branch      | This command will create a branch locally   |
| 9  | git checkout      | To work in a branch, first you need to switch to it  |
| 10 | git status      | all the necessary information about the current branch  |

## Glossary of the week - Enter new technical words you have learnt this week and their meanings.

| Number   | Word | Meaning     |
| :---     | :----:   |  :---  |
| 1  | Continuous Delivery      | allow software to be developed and deployed rapidly, reliably, and repeatedly with minimal human intervention  |
| 2  | Continuous Deployment       | A software development practice in which every code change goes through the entire pipeline and is put into production automatically, resulting in many production deployments every day  |
| 3  | Continuous Integration     | A software development process where a branch of source code is rebuilt every time code is committed to the source control system  |
| 4  | Containerization      | include file system, disk quota, CPU and memory, I/O rate, root privileges, and network access. Much lighter-weight than machine-level virtualization and sufficient for many isolation requirement sets.  |
| 5  | Configuration Management     | A process for establishing and maintaining consistent settings of a system. These solutions also include SysAdmin tools for IT infrastructure automation  |
| 6  | Commit       | A way to record the changes to a repository and add a log message to describe the changes that were made   |
| 7  | Cluster      | A set of connected computers that work together to enable load balancing, auto scaling and high availability.  |
| 8  | Infrastructure-as-Code (IaC)     | IaC involves managing and storing your infrastructure in a repository as code, where it can be recreated or rolled back to a past state with the click of a button  |
| 9  | XXXXXXXX       | YYYYYYYY   |
| 10 | XXXXXXXX       | YYYYYYYY   |

