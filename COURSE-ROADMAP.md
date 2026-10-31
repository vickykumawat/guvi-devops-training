# Course Roadmap --- Advanced Cloud Engineering & DevOps

This roadmap organizes the modules and topics listed in the course
syllabus into a learning path. Use it alongside the root
[`README.md`](./README.md) to navigate the repository.

> **How to use this roadmap:** Follow the modules in order, review the
> related notes, practise the examples and labs, and revisit topics when
> preparing for assignments or revision. Repository materials will be
> added as the course progresses.

------------------------------------------------------------------------

## Learning Path at a Glance

1.  Linux Foundations
2.  Networking Foundations
3.  Programming & Scripting with AI Tools
4.  Cloud Fundamentals (AWS)
5.  Introduction to DevOps
6.  Git & Version Control
7.  Docker and Containers
8.  Kubernetes & Cloud Native --- AI Assisted
9.  AWS EKS Deployment
10. CI/CD with DevSecOps
11. AWS CI/CD
12. AI-Powered Infrastructure as Code Deployments
13. Configuration Management --- Ansible with AI Tools
14. GitOps
15. Observability

------------------------------------------------------------------------

## Module 01 --- Linux Foundations

**Repository folder:**
[`01-linux-foundations/`](./01-linux-foundations/)

### Topics

-   Operating systems and Linux: OS functions, Linux history, open
    source, server/desktop architecture, CLI vs GUI.
-   Virtualization: hosted vs nested virtualization; Ubuntu setup using
    VirtualBox or WSL.
-   Linux setup and file system: file-system hierarchy, absolute and
    relative paths, file types, hard and soft links.
-   Users, groups, passwords, ownership, and permissions.
-   Linux commands: command syntax and options, standard
    input/output/error, pipes, redirection, and basic text processing.
-   Processes and jobs: foreground and background jobs.
-   Services and system operations: daemons, systemd, service lifecycle,
    packages, and logs.
-   System monitoring: disk, CPU, and memory.
-   Searching, archiving, compression, and package management.

### Practice focus

Navigate the file system, create and manage files, work with permissions
and users, inspect processes and services, and explore system logs and
resource usage.

------------------------------------------------------------------------

## Module 02 --- Networking Foundations

**Repository folder:**
[`02-networking-foundations/`](./02-networking-foundations/)

### Topics

-   How data travels between a requester and a web server using the OSI
    model.
-   Ports and protocols.
-   DNS working principles.
-   HTTP vs HTTPS.
-   SSH basics and remote access.
-   IP addressing, subnet basics, subnetting, netmasks, and CIDR.
-   Common network troubleshooting techniques and commands.

### Practice focus

Use networking commands, investigate connectivity and name-resolution
issues, and practise remote access.

------------------------------------------------------------------------

## Module 03 --- Programming & Scripting with AI Tools

**Repository folder:**
[`03-programming-scripting-ai-tools/`](./03-programming-scripting-ai-tools/)

This module contains shell scripting and Python topics from the
syllabus.

### A. Shell Scripting

-   Introduction to shell scripting and Bash.
-   Script creation and execution.
-   Script structure and the shebang line.
-   Variables and environment variables.
-   Reading user input.
-   Conditional statements: `if`, `else`, and `elif`.
-   Loops: `for` and `while`.
-   Functions and reusable script blocks.
-   Passing arguments to scripts and functions.
-   Exit status and return codes.
-   Automation with shell scripts.
-   Scheduling tasks with cron.
-   Debugging, error handling, and logging script output.
-   File and process automation.

### B. Python Fundamentals

-   Introduction to Python, syntax, variables, and writing a first
    program.
-   Comments and data types.
-   Numeric, Boolean, and collection data types.
-   Control flow and conditional statements.
-   Loops, iteration, and loop-control statements.
-   Functions, arguments, and return values.
-   File handling: create, read, and update files.
-   Python recap, automation basics, and an overview of API interaction.

### Practice focus

Write and execute scripts, automate repetitive tasks, use conditions and
loops, create reusable functions, process files, and practise basic
Python automation.

------------------------------------------------------------------------

## Module 04 --- Cloud Fundamentals (AWS)

**Repository folder:**
[`04-cloud-fundamentals-aws/`](./04-cloud-fundamentals-aws/)

### Topics

-   Cloud computing fundamentals and AWS global infrastructure.
-   Identity and Access Management (IAM).
-   VPC and cloud networking.
-   EC2 instance management.
-   Auto Scaling and load balancing.
-   Amazon S3.
-   EBS, EFS, and FSx storage services.
-   RDS and DynamoDB.
-   DNS and content delivery.
-   Serverless computing with AWS Lambda.
-   Monitoring and logging in AWS.
-   AWS cost optimization and best practices.

### Practice focus

Explore the purpose of core AWS services and practise the corresponding
tasks where a lab environment and permissions are available.

**Cost reminder:** Check estimated charges before creating AWS resources
and remove lab resources when finished.

------------------------------------------------------------------------

## Module 05 --- Introduction to DevOps

**Repository folder:**
[`05-introduction-to-devops/`](./05-introduction-to-devops/)

### Topics

-   Introduction to DevOps strategies and tools.

### Practice focus

Connect the tools and technical skills covered in the course to the
DevOps workflow.

------------------------------------------------------------------------

## Module 06 --- Git & Version Control

**Repository folder:**
[`06-git-version-control/`](./06-git-version-control/)

### Topics

-   Introduction to version control and Git.
-   Git repository management.
-   Branching and merging operations.
-   Remote repositories and collaboration.
-   Pull requests, rebase, and SSH authentication.

### Practice focus

Create repositories, stage and commit changes, inspect history, work
with branches, resolve merge conflicts, and practise collaboration using
a remote repository.

------------------------------------------------------------------------

## Module 07 --- Docker and Containers

**Repository folder:**
[`07-docker-containers/`](./07-docker-containers/)

### Topics

-   Setting up Docker environments.
-   Building Docker images.
-   Docker management.

### Practice focus

Build and run containers, practise image builds, and use Docker commands
to manage containerized applications.

------------------------------------------------------------------------

## Module 08 --- Kubernetes & Cloud Native --- AI Assisted

**Repository folder:**
[`08-kubernetes-cloud-native/`](./08-kubernetes-cloud-native/)

### Topics

-   Kubernetes architecture.
-   Kubernetes cluster setup.
-   Pods and application deployment.
-   Services and networking.
-   Persistent volumes and storage classes.
-   Role-Based Access Control (RBAC).
-   ConfigMaps, Secrets, and environment variables in Pods.
-   Horizontal Pod Autoscaler (HPA).
-   Resource requests and limits.
-   Stateful vs stateless applications.
-   Helm charts and repositories.
-   Deployment strategies: rolling, blue-green, and canary.
-   Kubernetes best practices.

### Practice focus

Create Kubernetes resources using YAML, deploy and expose applications,
configure storage and access control, manage configuration and scaling,
and practise Helm-based deployments and rollbacks.

------------------------------------------------------------------------

## Module 09 --- AWS EKS Deployment

**Repository folder:**
[`09-aws-eks-deployment/`](./09-aws-eks-deployment/)

### Topics

-   Amazon EKS and managed Kubernetes concepts.
-   EKS cluster setup overview.
-   Configuring `kubectl` for EKS.
-   Deploying applications on EKS.
-   Microservices architecture in Kubernetes.
-   Multi-service deployment using YAML.
-   Service communication and scaling.

### Practice focus

Explore the EKS deployment workflow and practise deploying applications
to a suitable AWS lab cluster.

------------------------------------------------------------------------

## Module 10 --- CI/CD with DevSecOps

**Repository folder:** [`10-cicd-devsecops/`](./10-cicd-devsecops/)

### Topics

-   CI/CD concepts and benefits.
-   Continuous Integration vs Continuous Delivery vs Continuous
    Deployment.
-   CI/CD pipeline stages and build, test, and deploy workflows.
-   Build automation.
-   Sonatype Nexus and artifact management.
-   Setting up Jenkins, SonarQube, and Nexus.
-   End-to-end pipeline deployment using Jenkins, SonarQube, and Nexus.
-   GitHub Actions: workflow YAML, events and triggers, jobs, steps,
    actions, environment variables, secrets, and reusable workflow
    basics.

### Practice focus

Explore a pipeline from source-code changes through build, testing,
quality checks, artifact management, and deployment.

------------------------------------------------------------------------

## Module 11 --- AWS CI/CD

**Repository folder:** [`11-aws-cicd/`](./11-aws-cicd/)

### Topics

-   AWS CodeCommit.
-   AWS CodeBuild.
-   AWS CodePipeline.
-   AWS CodeDeploy.

### Practice focus

Understand the role of each service in an AWS CI/CD workflow and
practise the pipeline flow in an appropriately configured lab.

------------------------------------------------------------------------

## Module 12 --- AI-Powered Infrastructure as Code Deployments

**Repository folder:**
[`12-infrastructure-as-code-terraform/`](./12-infrastructure-as-code-terraform/)

### Topics

-   Infrastructure as Code (IaC) and its benefits.
-   Declarative vs imperative infrastructure.
-   Infrastructure automation concepts.
-   Terraform architecture, providers, resources, and workflow.
-   Terraform configuration files and syntax.
-   Variables and outputs.
-   Terraform state and resource dependencies.
-   Modules and workspaces.
-   Infrastructure provisioning and change management.
-   `terraform init`, `terraform validate`, `terraform plan`,
    `terraform apply`, and `terraform destroy`.
-   CloudFormation overview.
-   Provisioning AWS resources such as EC2 instances and S3 buckets
    using Terraform.

### Practice focus

Create Terraform configurations, use variables and outputs, inspect
state, plan infrastructure changes, provision resources, and clean up
lab infrastructure.

**Safety reminder:** Review the plan before applying changes. Confirm
which resources will be created, changed, or destroyed.

------------------------------------------------------------------------

## Module 13 --- Configuration Management: Ansible with AI Tools

**Repository folder:**
[`13-ansible-configuration-management/`](./13-ansible-configuration-management/)

### Topics

-   Configuration management and configuration automation.
-   Ansible architecture and agentless automation.
-   SSH-based communication and inventory management.
-   Ad-hoc commands.
-   Playbooks and YAML syntax.
-   Tasks, modules, variables, conditionals, and loops.
-   Handlers and notifications.
-   Modules such as `yum`, `apt`, `service`, and `copy`.
-   Roles and reusable automation components.
-   Application deployment and multi-server automation.
-   Configuration enforcement and infrastructure automation best
    practices.

### Practice focus

Create an inventory, test connectivity, run ad-hoc commands, write
playbooks, organize roles, and automate server or application
configuration.

------------------------------------------------------------------------

## Module 14 --- GitOps

**Repository folder:** [`14-gitops/`](./14-gitops/)

### Topics

-   GitOps concepts and benefits.
-   Declarative deployment models and Git as the source of truth.
-   Continuous delivery concepts and GitOps workflow architecture.
-   Pull-based vs push-based deployment.
-   Argo CD architecture.
-   Application synchronization.
-   Desired state vs actual state.
-   Deployment reconciliation, automated sync, and rollback.

### Practice focus

Store Kubernetes manifests in Git, connect a repository to Argo CD,
deploy an application, and observe synchronization between the desired
and actual states.

------------------------------------------------------------------------

## Module 15 --- Observability

**Repository folder:** [`15-observability/`](./15-observability/)

### A. Prometheus

-   Introduction to Prometheus and its architecture.
-   Metrics collection concepts.
-   Exporters, including Node Exporter and WMI Exporter.
-   Time-series database basics.
-   PromQL introduction.
-   Installing Prometheus, configuring an exporter, collecting system
    metrics, and running basic PromQL queries.

### B. Grafana

-   Introduction to Grafana and dashboard architecture.
-   Data sources.
-   Dashboard panels and visualization.
-   Monitoring dashboard design and infrastructure visualization.
-   Alerting best practices.
-   Installing Grafana.
-   Connecting Prometheus as a data source.
-   Creating dashboards, configuring graphs, and configuring panels.

### Practice focus

Collect metrics, query them, connect Grafana to a data source, create
dashboards, and practise visualizing infrastructure metrics.

------------------------------------------------------------------------

## Suggested Repository Structure for Each Module

As resources are added, use a consistent structure where it fits the
topic:

``` text
module-folder/
├── README.md
├── notes/
├── examples/
├── practicals/
├── assignments/
└── troubleshooting/
```

Technology-specific folders can be added when useful---for example,
`manifests/` for Kubernetes, `dockerfiles/` for Docker, `playbooks/` for
Ansible, and `pipelines/` for CI/CD.

Pseudo-session notes and actual-course resources should remain together
under the relevant module. This avoids duplicating the same topic in
separate course folders.

## Recommended Study Routine

-   **Before class:** Read the relevant topic overview if it is
    available.
-   **During class:** Follow the instructor's examples and note
    important commands.
-   **After class:** Repeat the practical steps in your own lab
    environment.
-   **Before moving on:** Try the practice questions and revisit any
    errors.
-   **For revision:** Use the cheat sheets, troubleshooting examples,
    and interview questions when available.

## Important Notes

-   This roadmap reflects the module names and topics listed in the
    course syllabus. It does not imply that every note, lab, assignment,
    or solution is already available in this repository.
-   The sequence is presented in syllabus order. Follow any updated
    instructions or schedule provided by the instructor.
-   Never commit passwords, cloud access keys, tokens, private keys, or
    other confidential information to Git.
-   Check for possible cloud charges before running AWS labs and delete
    resources when they are no longer needed.

------------------------------------------------------------------------

**Keep learning, keep practising, and build your cloud and DevOps skills
one module at a time.** 🚀
