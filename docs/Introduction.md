# Introduction

## About

DataConnect Integration Manager provides an intuitive way to configure, schedule, and monitor integrations designed with the DataConnect Integrated Development Environment (IDE) and executed by the DataConnect engine. It is available as a fully hosted subscription service powered by Actian DataCloud or as an on-premise installation that you can fully control within your data center.

Both deployment options have the same user interface and RESTful Application Programmer’s Interface (API) to facilitate portability between environments as your needs change.

## Release Notes

### Release 1.6

The following are the new features in this release of Integration Manager:

- DataFlow native scheduling and execution—Bring your own (BYO) DataFlow engine or cluster. Directly invokes dataflows in addition to the support provided in DataConnect Studio Process Designer workflows.
- Aggregator Service—Merciless event-processing through DataConnect or DataFlow aggregates messages into micro batches for efficient processing.
- High Availability—Quickly stands up multiple worker nodes for additional workload bandwidth or job segregation.
- Streamlined installation and configuration—Integration Manager server can be deployed quickly and run standalone or in fully distributed mode.
- Improved job template and configuration wizards—More intuitive deployment interactions are available for rapid configuration and scheduling of integrations.
- Externalized Worker Service and Messaging Broker—Provides BYO database and messaging services for on-premise and private cloud deployments to enable custom management and reporting.

### Release 1.5 (9/28/2018)

The following are the new features in this release of Integration Manager:

- Containerized services
  - All Integration Manager services are now available as combined or stand-alone Docker images with sample Kubernetes deployment recipes.

### Release 1.4 (9/4/2018)

The following are the new features in this release of Integration Manager:

- Job Notification Service
  - Abort/Error notification for individual job configurations
  - Global/default email addressee notification support
- JobConfig Aliasing Capability
  - Map JobConfig API endpoints to custom URLs
  - Swap out backend integrations without changing client endpoints
- Group Sharing Capability
  - Share job templates with multiple users
  - Fine-grained access controls to support read, write, and execute privileges
- External Identity Provider Support
  - Control user authentication with federated identity providers such as Salesforce.com or Keycloak
- Improved Messaging Backend
  - Support for larger job message payloads up to 2 GB (appropriate system requirements notwithstanding)

### Release 1.3 (6/15/2018)

The following are the new features in this release of Integration Manager:

- Support for Linux Installations
  - Red Hat Enterprise v7
- Support for External Configuration Database
  - MySQL v5
- Job Orchestration
  - Design serial and parallel job orchestrations within Process Designer
  - Job orchestrations are packaged and deployed just like any other integration process
  - Control the order and prerequisites of multiple Job Config executions
  - Split large batch jobs across multiple engines and/or engine pools
- Enhanced and extended portability between Cloud and On-premise APIs

### Release 1.1 (12/15/2017)

**Management Stack**

| Feature Set                        | Summary                                                                                                                                           |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Account Management API             | Basic user administration functionality with admin user roles                                                                                     |
| API Security                       | Full JWT support for authentication and authorization of API access                                                                               |
| Embedded Databases                 | Embedded relational database for job configuration, including embedded database admin portal using H2                                             |
| Embedded Job Queue                 | Embedded queuing system for job execution                                                                                                         |
| Embedded Worker                    | Embedded worker for the DataConnect Integration Engine                                                                                            |
| Enterprise Scheduling Capabilities | Interval and advanced cron scripting support                                                                                                      |
| Installer for Windows              | Installer for complete management stack, including API, database, embedded queuing system, and standalone worker                                  |
| Job Configuration API              | Create, manage, and schedule recurring jobs and related macros. Create and manage templates for mass changes across a customer base or department |
| Job Execution API                  | Run jobs on demand. Create dashboards and mashups of queued, running, and recently completed jobs.                                                |

**Management UI**

| Feature Set                       | Summary                                                                                |
| --------------------------------- | -------------------------------------------------------------------------------------- |
| Hierarchical Job File Management  | File management functionality and inheritance within template or configuration context |
| Hierarchical Job Macro Management | Macro management functionality and inheritance with template or configuration context  |
| Job Configuration Wizard          | Step-by-step wizard for job creation                                                   |
| Job Configurations                | Create, edit, activate/deactivate job configuration settings, macros, and files        |
| Job Template Wizard               | Step-by-step wizard for job template creation                                          |
| Job Templates                     | Management of jobs                                                                     |
| User Administration               | Create, edit, activate/deactivate users                                                |

## Actian Integration Manager API Updates

| API                    | Summary                                                                            |
| ---------------------- | ---------------------------------------------------------------------------------- |
| Job Execution API      | Execute jobs and inspect the status of queued, running, and recently finished jobs |
| Job Configuration API  | Build and maintain hierarchical job configurations                                 |
| Repository Manager API | Manage common package and file repositories within an account                      |
| Macro Manager API      | Manage global macros within an account                                             |
| License Manager API    | View and update licensing information                                              |
| Agent Manager API      | Manage agents within an account                                                    |
| Account Management API | Account and user administration                                                    |

## Dataflow

Actian DataFlow provides a visual end-to-end solution for data preparation, analytics development, and execution on Hadoop. An embedded dataflow engine delivers auto-scaling and parallelism, processing data natively on Hadoop.

DataFlow offers a robust range of capabilities for business analysts to data scientists:

- Create workflows to read and pull together data from all your sources.
- Use prebuilt data preparation and analytics operators already optimized for parallel execution.
- Prepare the data, analyze it, and output it to the visualization tool of your choice.
- Build end-to-end analytics workflows in KNIME.
  For complete information about Actian DataFlow, see the DataFlow documentation.
