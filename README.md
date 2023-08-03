# Curated List of DevOps Tools

A comprehensive collection of essential DevOps tools for development, deployment, monitoring, and more.

✍️ Feel free to enhance the list of DevOps tools by submitting pull requests! Read the [contribution guidelines](https://github.com/techiescamp/devops-tools/blob/main/CONTRIBUTING.md) to know more. 

## Hit the Star! :star:

If you are planning to use this repo for reference, please hit the star. Thanks!

## Table of Contents

- [Development Environment Tools](#development-environment-tools)
- [Source Code Management](#source-code-management)
- [Build Tools](#build-tools)
- [Continuous Integration Tools](#continuous-integration-tools)
- [Artifact Management Tools](#artifact-management-tools)
- [Code Analysis Tools](#code-analysis-tools)
- [Continuous Delivery & GitOps Tools](#continuous-delivery--gitops-tools)
- [Infrastructure Provisioning Tools](#infrastructure-provisioning-tools)
- [Cloud Cost Management Tools](#cloud-cost-management-tools)
- [Configuration Management Tools](#configuration-management-tools)
- [Secret Management Tools](#secret-management-tools)
- [Config/Service Discovery Tools](#configservice-discovery-tools)
- [Containerization Tools](#containerization-tools)
- [Container Orchestration Tools](#container-orchestration-tools)
- [Container Security Tools](#container-security-tools)
- [Policy Management Tools](#policy-management-tools)
- [Service Mesh Tools](#service-mesh-tools)
- [Logging Tools](#logging-tools)
- [Monitoring & Observability Tools](#monitoring--observability-tools)
- [Visualization Tools](#visualization-tools)
- [Internal Developer Platform Tools](#internal-developer-platform-tools)
- [API Tools](#api-tools)
- [Collaboration Tools](#collaboration-tools)


## Development Environment Tools

Development environment tools are essential for maintaining consistency in software configurations and versions. They ensure reproducibility in minutes in case of a crash, increasing developer productivity.

* **[Virtual Box](https://www.virtualbox.org/)** (Open Source): A powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use.
* **[Qemu](https://www.qemu.org/)** (Open Source): A generic and open source machine emulator and virtualizer.
* **[Vagrant](https://www.vagrantup.com/)** (Open Source): A tool for building and managing virtual machine environments in a single workflow.
* **[Docker Desktop](https://www.docker.com/products/docker-desktop)** (Open Source): An application for MacOS and Windows machines for the building and sharing of containerized applications.
* **[Minikube](https://minikube.sigs.k8s.io/)** (Open Source): A tool that makes it easy to run Kubernetes locally.
* **[Minishift](https://www.okd.io/minishift/)** (Open Source): A tool that helps you run OpenShift locally by running a single-node OpenShift cluster inside a VM.
* **[Podman Desktop](https://podman.io/)** (Open Source): A daemonless container engine for developing, managing, and running OCI Containers on your Linux System.

## Source Code Management

In the DevOps world, everything is treated as code (e.g., code, shell script, configurations, etc.). Robust source code management tools are a must.

* **[Github](https://github.com/)** (Free & Paid): A web-based hosting service for version control using Git. It offers all of the distributed version control and source code management (SCM) functionality of Git as well as adding its own features.
* **[Bitbucket](https://bitbucket.org/)** (Free & Paid): A web-based version control repository hosting service owned by Atlassian, for source code and development projects that use either Mercurial or Git revision control systems.
* **[Gitlab](https://about.gitlab.com/)** (Free & Paid): A web-based DevOps lifecycle tool that provides a Git-repository manager providing wiki, issue-tracking and CI/CD pipeline features, using an open-source license.
* **[AWS CodeCommit](https://aws.amazon.com/codecommit/)** (Free & Paid): A fully-managed source control service that makes it easy for companies hosting their own repositories to collaborate on code in a secure and highly scalable ecosystem.
* **[Azure Repos](https://azure.microsoft.com/en-us/services/devops/repos/)** (Free & Paid): Provides Git repositories or Team Foundation Version Control (TFVC) for source control of your code.
* **[Google Cloud Source Repositories](https://cloud.google.com/source-repositories)** (Free & Paid): Fully-featured, scalable, private Git repositories hosted on Google Cloud.

## Build Tools

Build tools are essential for automating package creation or deployable artifacts.

* **[Maven](https://maven.apache.org/)** (Java) (Open Source): A software project management and comprehension tool, primarily used for Java projects.
* **[Gradle](https://gradle.org/)** (Java, Kotlin, Groovy, Scala, Python, C++) (Free & Paid): An open-source build automation system that builds upon the concepts of Apache Ant and Apache Maven.
* **[npm](https://www.npmjs.com/)** (Javascript): A package manager for JavaScript, used to install, share, and distribute code.
* **[Rake](https://ruby.github.io/rake/)** (Ruby) (Open Source): A software task management and build automation tool for Ruby.
* **[MSBuild](https://github.com/dotnet/msbuild)** (.Net) (Open Source): The build platform for .NET and Visual Studio.
* **[Pybuilder](https://pybuilder.io/)** (Python) (Open Source): A software build tool written in pure Python mainly for Python applications.

## Continuous Integration Tools

Continuous Integration provides continuous feedback on code integrations, helping solve issues faster and decreasing time in software release cycles.

* **[Jenkins](https://www.jenkins.io/)** (Open Source): An open-source automation server, helping to automate parts of the build, test, and deployment process.
* **[Github Actions](https://github.com/features/actions)** (Free & Enterprise): A CI/CD solution that integrates with GitHub repositories to run a series of commands automatically.
* **[Gitlab CI](https://docs.gitlab.com/ee/ci/)** (Free & Enterprise): A continuous integration service included with GitLab that builds and tests the software whenever the developer pushes code to the application.
* **[Bamboo](https://www.atlassian.com/software/bamboo)** (Free & Enterprise): A continuous integration and deployment tool that ties automated builds, tests, and releases together in a single workflow.
* **[Travis CI](https://travis-ci.org/)** (Open Source): A cloud-based continuous integration service that automatically builds and tests code changes in GitHub repositories.
* **[TeamCity](https://www.jetbrains.com/teamcity/)** (Free & Enterprise): A build management and continuous integration server from JetBrains.

## Artifact Management Tools

Artifact management tools store and version code/binary that has to be deployed into production. They centralize repositories specifically made for this purpose.

* **[Nexus](https://www.sonatype.com/nexus/repository-oss)** (Free & Enterprise): A repository manager that allows you to proxy, collect, and manage your dependencies.
* **[Jfrog Artifactory](https://jfrog.com/artifactory/)** (Enterprise): An enterprise-grade universal binary repository manager solution that could handle end-to-end artifact management.
* **[npm](https://www.npmjs.com/)** (Free): A package manager for JavaScript, used to install, share, and distribute code.
* **[Nuget](https://www.nuget.org/)** (.Net) (Free): A free and open-source package manager for the Microsoft development platform.

## Code Analysis Tools

Code analysis tools are a crucial component of any DevOps toolkit. They scrutinize the code before deployment, pinpointing potential issues. This allows developers to enhance the quality of the software by making necessary modifications.

Code analysis can be categorized into two types:

* **Static Analysis (SAST)** – This method inspects the source code without executing it, identifying bugs, security vulnerabilities, and quality issues.
* **Dynamic Analysis (DAST)** – This approach involves running the code to uncover performance bottlenecks and behavioral anomalies.

Here are some notable tools in this category:

* **[Sonarqube](https://www.sonarqube.org/)** (Free & Enterprise): SonarQube offers a comprehensive suite for continuous code quality inspection. It automates reviews with static code analysis to detect bugs, code smells, and security vulnerabilities.
* **[Checkmarx](https://www.checkmarx.com/)** (Enterprise): Checkmarx is a leading solution in software security, adept at identifying, tracking, and rectifying both technical and logical security flaws in the source code.
* **[PMD](https://pmd.github.io/)** (Open Source): PMD is a versatile static code analyzer. It can detect a wide range of programming flaws across multiple languages.

## Continuous Delivery & GitOps Tools

Continuous Delivery is more of an approach rather than a toolset, aiming to ensure that software can be reliably and immediately deployed at any time. While there's no specific tool labeled solely for continuous delivery, several process-oriented tools can be leveraged to achieve this goal within your projects.

GitOps, a subset of DevOps, uses Git as a single source of truth for declarative infrastructure and applications. Here are some prominent tools that align with Continuous Delivery and GitOps principles:

* **[Jenkins](https://www.jenkins.io/)** (Open Source): A widely-used open-source automation server that supports building, deploying, and automating any project.
* **[Argo CD](https://argoproj.github.io/argo-cd/)** (Open Source): A declarative, GitOps continuous delivery tool for Kubernetes.
* **[Flux CD](https://fluxcd.io/)** (Open Source): A tool that automates the deployment of containers to Kubernetes, following the GitOps principles.
* **[Go CD](https://www.gocd.org/)** (Open Source): An open-source continuous delivery server designed to model and visualize complex workflows.
* **[Gitlab CD](https://docs.gitlab.com/ee/ci/)** (Free & Enterprise): GitLab's continuous delivery solution, allowing automated deployment and monitoring of applications.
* **[Weave GitOps](https://www.weave.works/oss/gitops/)** (Enterprise): An enterprise-grade GitOps solution, providing a set of best practices for deploying and managing applications and infrastructure.
* **[Jenkins X](https://jenkins-x.io/)** (Open Source): An open-source project that provides automated CI/CD for Kubernetes, with preview environments and promotion across environments.
* **[Tekton](https://tekton.dev/)** (Open Source): A powerful and flexible open-source framework for creating CI/CD systems, allowing developers to build, test, and deploy across cloud providers and on-premises systems.

## Infrastructure Provisioning Tools

Infrastructure provisioning tools play a vital role in automating the setup of computing infrastructure. This includes the creation and management of virtual machines, networks, storage, and various cloud resources. By automating these processes, these tools enable more efficient and consistent infrastructure deployment.

Here are some of the leading tools in this category:

* **[Terraform](https://www.terraform.io/)** (Open Source & Enterprise): Terraform is an open-source tool that allows you to define and provision a datacenter infrastructure using a declarative configuration language. It supports various cloud providers and offers an enterprise version with additional features.
* **[Pulumi](https://www.pulumi.com/)** (Open Source & Enterprise): Pulumi provides a way to create, deploy, and manage infrastructure using programming languages you already know. It offers both open-source and enterprise solutions.
* **[CloudFormation](https://aws.amazon.com/cloudformation/)** (AWS Service): An AWS service that helps you model and set up Amazon Web Services resources. It allows you to use a template to describe all the AWS resources you need, automating the provisioning process.
* **[Azure Resource Manager](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview)** (Azure Service): Azure Resource Manager enables you to work with the resources in your solution as a group. You can deploy, update, or delete all the resources for your solution in a single, coordinated operation.

## Cloud Cost Management Tools

Cloud Cost Management Tools help organizations monitor, analyze, and optimize their cloud spending. By providing insights into resource utilization and cost allocation, these tools enable better budgeting and cost control. Here's a list of tools that can be used for Cloud Cost Management:

* **[InfraCost](https://www.infracost.io/)** (Open Source): InfraCost provides cost estimates for Terraform projects, helping developers understand the cost implications of their infrastructure code.
* **[Kubecost](https://www.kubecost.com/)** (Open Source): Kubecost gives you visibility into your Kubernetes usage and cost, allowing you to monitor and optimize your cluster resources.

## Configuration Management Tools

Configuration management tools are pivotal in both application and infrastructure deployment. They assist in managing the state of servers and applications, ensuring that configurations are applied consistently and idempotently. By automating these configurations, these tools enhance the reliability and efficiency of deployment processes.

Here's a look at some of the widely-used configuration management tools:

* **[Ansible](https://www.ansible.com/)** (Open Source & Enterprise): Ansible is a versatile automation tool that can handle configuration management, application deployment, and task automation. It uses a simple, human-readable language, allowing for easy adoption.
* **[Chef](https://www.chef.io/)** (Open Source & Enterprise): Chef is a powerful automation platform that transforms complex infrastructure into code, automating how infrastructure is configured, deployed, and managed across your network.
* **[Puppet](https://puppet.com/)** (Open Source & Enterprise): Puppet is designed to manage the configuration of Unix-like and Microsoft Windows systems declaratively. It provides a way to automate repetitive tasks, quickly deploy critical applications, and proactively manage infrastructure.
* **[Saltstack](https://www.saltstack.com/)** (Open Source & Enterprise): SaltStack is an intelligent IT automation platform that can manage, secure, and optimize any infrastructure. It's built on a unique and responsive remote execution engine, allowing for control over thousands of systems with no performance degradation.

## Secret Management Tools

Secret management tools are essential for safeguarding sensitive information such as passwords, API keys, and other credentials. They provide a secure way to store, distribute, and manage secrets, ensuring that they are accessible only to authorized entities.

Here are some popular secret management tools:

* **[HashiCorp Vault](https://www.vaultproject.io/)** (Open Source & Enterprise): Vault is a tool for securely accessing secrets such as API keys, passwords, or certificates. It provides a unified interface to any secret while providing tight access control and recording a detailed audit log.
* **[External Secrets Operator](https://github.com/external-secrets/kubernetes-external-secrets)** (Open Source): An extension for Kubernetes that allows you to securely manage secrets stored in managed cloud services
* **[AWS Secrets Manager](https://aws.amazon.com/secrets-manager/)**: A service that helps you protect access to your applications, services, and IT resources without the upfront investment and on-going maintenance costs of operating your own infrastructure.
* **[Google Cloud Secret Manager](https://cloud.google.com/secret-manager/)**: A fully managed service on Google Cloud Platform to handle sensitive data like API keys, passwords, and certificates. It provides robust security and convenient access controls.
* **[Azure Key Vault](https://azure.microsoft.com/en-us/services/key-vault/)**: A cloud service provided by Microsoft to securely manage keys, secrets, and certificates.

## Config/Service Discovery Tools

Config and Service Discovery Tools are vital in distributed systems, allowing applications to manage configuration data dynamically and discover services without hard-coded hostnames or ports. These tools provide a centralized repository for configuration and service information, ensuring consistency and availability.

Here are some popular tools in this category:

* **[Consul](https://www.consul.io/)** (Open Source & Enterprise): Consul is a tool for discovering and configuring services in your infrastructure. It provides key/value storage and multi-datacenter support, ensuring high availability and scalability.
* **[Etcd](https://etcd.io/)** (Open Source): A distributed key-value store that provides a reliable way to store data across a cluster of machines. It's primarily used in distributed systems to hold configuration data that needs to be available to all nodes in the cluster.
* **[Apache ZooKeeper](https://zookeeper.apache.org/)** (Open Source): A centralized service for maintaining configuration information, naming, providing distributed synchronization, and group services.
* **[Eureka](https://github.com/Netflix/eureka)** (Open Source): A REST-based service that is primarily used in the AWS cloud for locating services for the purpose of load balancing and failover of middle-tier servers.

## Containerization Tools

Containerization Tools enable the encapsulation of an application and its dependencies into a 'container.' This ensures that the application runs the same way, regardless of where it's deployed. By isolating the application in a container, these tools provide a consistent environment that's abstracted from the host system.

Here are some popular tools in this category:

* **[Docker](https://www.docker.com/)** (Open Source & Enterprise): Docker is a platform that enables developers to create, deploy, and run applications in containers. It's widely used for its ease of use and integration with various orchestration tools.
* **[Podman](https://podman.io/)** (Open Source): Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux System. It provides a Docker-CLI-compatible command-line front end and can use many of the same commands.
* **[Buildah](https://buildah.io/)** (Open Source): Buildah is a tool that facilitates building OCI container images. It's a complementary tool to Podman and allows for more fine-grained control over image creation and management.
* **[rkt](https://github.com/rkt/rkt)** (Open Source): An application container engine developed for modern production cloud-native environments, emphasizing simplicity, security, and composability.
* **[CRI-O](https://cri-o.io/)** (Open Source): CRI-O is a lightweight container runtime specifically for Kubernetes. It allows Kubernetes to use any OCI-compliant runtime as the container runtime for running pods. It provides an optimized performance for Kubernetes workloads and is known for its simplicity and reliability.


## Container Orchestration Tools

With the widespread adoption of containerization technologies like Docker, Container Orchestration Tools have become indispensable in microservices-based deployments. These tools manage the lifecycle of containers within clusters, automating tasks such as deployment, scaling, networking, and availability.

Here are some of the leading tools in this category:

* **[Kubernetes](https://kubernetes.io/)** (Open Source): Kubernetes is the de facto standard in container orchestration. It automates the deployment, scaling, and management of containerized applications across clusters of hosts.
* **[OpenShift](https://www.openshift.com/)** (Open Source & Enterprise): OpenShift is a Kubernetes-based container platform that provides developer and operational tools. It extends Kubernetes by adding features such as a web console, monitoring, logging, and more.
* **[Nomad](https://www.nomadproject.io/)** (Open Source & Enterprise): Nomad is a flexible and easy-to-use orchestrator to deploy and manage containers and non-containerized applications. It integrates seamlessly with popular DevOps tools and provides a lightweight solution for container orchestration.

## Container Security Tools

* **[Docker Bench](https://github.com/docker/docker-bench-security)** (Open Source): A script that checks for common best-practices around deploying Docker containers in production.
* **[Clair](https://github.com/quay/clair)** (Open Source): A vulnerability analysis tool for containers that inspects containers before they are deployed.
* **[Anchore Engine](https://anchore.com/opensource/)** (Open Source): A service that analyzes and inspects containers for security vulnerabilities and policy issues.
* **[AquaSec](https://www.aquasec.com/)** (Enterprise): A container security platform that provides full lifecycle security for containerized applications.
* **[Notary](https://github.com/theupdateframework/notary)** (Open Source): A project that allows anyone to have trust over arbitrary collections of data.
* **[Falco](https://falco.org/)** (Open Source): A behavioral activity monitor designed to detect anomalous activity in applications.
* **[Trivy](https://github.com/aquasecurity/trivy)** (Open Source): A simple and comprehensive vulnerability scanner for containers.

## Policy Management Tools

Policy Management Tools enable organizations to define, enforce, and manage security policies across their cloud-native environments. They provide a framework for policy definition and evaluation, ensuring compliance with organizational and regulatory requirements.

* **[Open Policy Agent](https://www.openpolicyagent.org/)** (Open Source): A general-purpose policy engine that unifies policy enforcement across the stack.
* **[Kyverno](https://kyverno.io/)** (Open Source): A policy engine designed for Kubernetes, providing validation, mutation, and generation of configurations.
* **[Cloud Custodian](https://cloudcustodian.io/)** (Open Source): A rules engine for managing public cloud accounts and resources.

## Service Mesh Tools

Service Mesh Tools provide a dedicated infrastructure layer for handling service-to-service communication. They make it easy to build and deploy resilient, secure, and observable microservices.

* **[Istio](https://istio.io/)** (Open Source): An open platform to connect, manage, and secure microservices, providing a uniform way to secure, connect, and monitor microservices.
* **[Linkerd](https://linkerd.io/)** (Open Source & Enterprise): A service mesh that gives you observability, reliability, and security without requiring any code changes.
* **[Cilium Service Mesh](https://cilium.io/)**: A next-generation service mesh for transparently securing, observing, and connecting Kubernetes workloads across complex, heterogeneous environments.

## Logging Tools

For any production environment, logging and monitoring for infrastructure & application components are a must-have to avoid system failures and application downtime. Here is the list of tools you could use for your projects:

* **[ELK Stack](https://www.elastic.co/elastic-stack)** (Open Source & Enterprise): A combination of Elasticsearch, Logstash, and Kibana, used for searching, analyzing, and visualizing log data in real-time.
* **[Grafana Loki](https://grafana.com/oss/loki/)** (Open Source and Enterprise): A horizontally scalable, highly available, multi-tenant log aggregation system inspired by Prometheus.
* **[Fluentd](https://www.fluentd.org/)** (Open Source): An open-source data collector for unified logging layers.
* **[Graylog](https://www.graylog.org/)** (Open Source & Enterprise): A leading centralized log management solution for capturing, storing, and enabling real-time analysis of terabytes of machine data.
* **[logz.io](https://logz.io/)** (Enterprise): A cloud-native logging and security platform that enables engineers to use the best open-source tools in the market without the complexity of operating them.
* **[Splunk](https://www.splunk.com/)** (Enterprise): A platform for searching, monitoring, and examining machine-generated big data.
* **[Syslog-ng](https://www.syslog-ng.com/)** (Enterprise): A flexible and highly scalable logging solution enabling you to centralize your log data and sort it in real-time.

## Monitoring & Observability Tools

Monitoring & Observability Tools provide insights into the performance, availability, and overall health of applications, infrastructure, and business processes. They enable proactive monitoring, alerting, and troubleshooting, ensuring optimal performance and reliability.

* **[Prometheus](https://prometheus.io/)** (Open Source): An open-source monitoring and alerting toolkit designed for reliability and scalability.
* **[Thanos](https://thanos.io/)** (Highly Available Prometheus Open Source Tool): A set of components that can be composed into a highly available metric system with unlimited storage capacity.
* **[Cilium](https://cilium.io/)** (Open Source & Enterprise): eBPF-based Networking, Security, and Observability.
* **[Falco](https://falco.org/)** (Open Source & Enterprise): Cloud Native Runtime Security.
* **[Calico](https://www.projectcalico.org/)** (Open Source & Enterprise): Pluggable eBPF-based networking and security for containers and Kubernetes.
* **[Sensu](https://sensu.io/)** (Open Source & Enterprise): A comprehensive monitoring solution for your entire infrastructure and application stack.
* **[Riemann](http://riemann.io/)** (Open Source): A powerful stream processing language that helps you compose, test, and distribute data streams.
* **[Nagios](https://www.nagios.org/)** (Free & Enterprise): A powerful monitoring system that enables organizations to identify and resolve IT infrastructure problems.
* **[Zabbix](https://www.zabbix.com/)** (Open Source & Enterprise): An enterprise-class open-source distributed monitoring solution.
* **[Data Dog](https://www.datadoghq.com/)** (Enterprise): A monitoring and analytics platform for large-scale applications.
* **[New Relic](https://newrelic.com/)** (Enterprise): A cloud-based platform that gives developers, engineers, operations, and management a clear view of what’s happening in today’s complex software environments.
* **[App Dynamics](https://www.appdynamics.com/)** (Enterprise): An application performance management solution that uses machine learning and artificial intelligence to provide real-time visibility and insight into IT environments.
* **[Sumologic](https://www.sumologic.com/)** (Enterprise): A cloud-native, machine data analytics platform that delivers real-time, continuous intelligence.
* **[Dynatrace](https://www.dynatrace.com/)** (Enterprise): An AI-powered, full-stack, automated performance management solution.

## Visualization Tools

* **[Grafana](https://grafana.com/)** (Open Source & Enterprise): A leading open-source platform for monitoring and observability, allowing you to query, visualize, alert on, and understand your metrics.
* **[Kibana](https://www.elastic.co/kibana)** (Open Source & Enterprise): A free and open user interface that lets you visualize your Elasticsearch data and navigate the Elastic Stack.
* **[Tableau](https://www.tableau.com/)** (Enterprise): A leading data visualization and business intelligence platform that helps people see and understand their data.

## Internal Developer Platform Tools

Platform engineering is becoming a core part of every organization that wants to adopt DevOps. Internal developer platforms or IDP tools play a key part in platform engineering. The following are the key tools that can be used for IDP:

* **[Backstage.io by Spotify](https://backstage.io/)** (Open Source): An open platform for building developer portals, providing a unified frontend for all your infrastructure tooling, services, and documentation.
* **[Port.io](https://port.io/)** (Free & Enterprise): A platform that enables teams to build, test, and deploy applications with ease.
* **[Configure8](https://www.configure8.com/)** (Free & Paid): A platform that provides a unified interface for managing infrastructure as code.
* **[Cortex](https://www.cortex.dev/)** (Enterprise): An enterprise-grade platform that simplifies the deployment, scaling, and management of machine learning models.
* **[Opslevel](https://www.opslevel.com/)** (Enterprise): A platform that provides insights and automation for your microservices and cloud resources.

## API Tools

* **[Postman](https://www.postman.com/)** (Free & Enterprise): A collaboration platform for API development.
* **[Hopscotch](https://github.com/janlelis/hopscotch)** (Open Source): A framework to help make integration testing more enjoyable.
* **[SoapUI](https://www.soapui.org/)** (Open Source & Enterprise): The world's leading automated testing tool for SOAP and REST APIs.
* **[Swagger](https://swagger.io/)** (Open Source & Enterprise): A framework for API specification that includes a suite of tools for auto-generating documentation, code generation, and API testing.
* * **[HTTPie](https://github.com/httpie/cli)** (Open Source): HTTPie (pronounced aitch-tee-tee-pie) is a command-line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible
 
  * 
## Collaboration Tools

The following are the collaboration tools that you could use in your DevOps toolchain. These tools support both messaging and video calling:

* **[Slack](https://slack.com/)** (Free & Paid): A collaboration hub that connects your work with the people you work with.
* **[Cisco Webex Teams](https://www.webex.com/team-collaboration.html)** (Free & Paid): A collaboration app that helps you create, meet, message, call, whiteboard, and share, regardless of whether you’re together or apart.
* **[Flock](https://flock.com/)** (Free & Paid): A communication and collaboration platform designed to boost productivity and foster teamwork.
* **[Google Hangouts](https://hangouts.google.com/)** (Free & Paid): A communication platform that includes messaging, video chat, and VOIP features.
* **[Flow Dock](https://www.flowdock.com/)** (Paid): A team collaboration app for desktop, mobile, and web, working seamlessly alongside your existing tools.

## Planning & Project Management Tools

Following are the planning tools that you could use in your DevOps toolchain:

* **[Jira](https://www.atlassian.com/software/jira)** (Free/Paid): A popular project management tool for agile teams.
* **[Trello](https://trello.com/)** (Free/Paid): A collaboration tool that organizes your projects into boards.
* **[Asana](https://asana.com/)** (Free/Paid): A web and mobile application designed to help teams organize, track, and manage their work.
* **[Backlog.com](https://backlog.com/)** (Free/Paid): A project management and collaboration tool for teams that want higher productivity.
* **[Monday.com](https://monday.com/)** (Paid): A work operating system that powers teams to run projects and workflows with confidence.


## IDE Tools

* **[Visual Studio Code](https://code.visualstudio.com/)** (Free): A free source-code editor made by Microsoft.
* **[Sublime Editor](https://www.sublimetext.com/)** (Free): A sophisticated text editor for code, markup, and prose.
* **[Notepad++](https://notepad-plus-plus.org/)** (Free): A free source code editor and Notepad replacement.

## Bug/Issue Tracking Tools

Bug and issue-tracking tools are a must for any team dealing with code. Here is the list of tools you might want to have a look at:

* **[Backlog](https://backlog.com/)** (Free & Paid): A project management and collaboration tool with bug tracking capabilities.
* **[Bugzilla](https://www.bugzilla.org/)** (Open Source): A server software designed to help you manage software development.
* **[Jira](https://www.atlassian.com/software/jira)** (Free & Paid): Also used for bug tracking, workflow, and issue tracking.
* **[Lean Testing](https://leantesting.com/)** (Free): A free bug tracking and test case management platform.
* **[Mantis](https://www.mantisbt.org/)** (Free): A free web-based bug tracking system.

## Test Automation/Performance Testing Tools

Another important pillar in the CI/CD pipeline is test automation tools. The following are the automation/performance testing tools that top our list:

* **[Selenium](https://www.selenium.dev/)**: A suite of tools to automate web browsers.
* **[UFT](https://software.microfocus.com/software/uft)**: Unified Functional Testing tool for automated functional testing.
* **[Appium](http://appium.io/)**: An open-source tool for automating native, mobile web, and hybrid applications.
* **[Jmeter](https://jmeter.apache.org/)**: An open-source software to test performance both on static and dynamic resources.
* **[Blazemeter](https://www.blazemeter.com/)**: A continuous testing platform for performance testing, monitoring, and more.









