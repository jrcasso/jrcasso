## Hi there 👋

I tinker around many areas in tech. Over the years my interests have revolved around devops tooling, automation/orchestration, scientific computing, and embedded systems programming - particularly in the context of IoT and home automation. I also like to solder and cannibalize circuits and every now and then. Additionally, I've been dabbling in agentic AI topics and their applications recently.

Anyways, here are some projects I think are either cool or useful. Let me know what you think (and please keep the age of the projects in mind 😂)!

---
### Web Application Templates

These are template codebases that are ready to be copied for your next project. Begin your new web application with a preconfigured local setup that bootstraps in as little two clicks!

| Repository                 | Description |
| - | - |
| [django-app-template](https://github.com/jrcasso/django-app-template)    | A template codebase for new Django applications, complete with a container-native development setup. |
| [go-app-template](https://github.com/jrcasso/go-app-template)    | A template codebase for new Go applications or libraries, complete with a container-native development setup. |
| [rails-app-template](https://github.com/jrcasso/rails-app-template)     | A template codebase for new Rails applications, complete with a container-native development setup. |

### Tools and Data Applications

| Repository                 | Description |
| ---------------------- | ----------- |
| [genesis](https://github.com/jrcasso/genesis)    | An efficient, parallelizable, Docker-based CI/CD pipeline runner. Create and run both simple and complex workflows with a directed acyclic graph configuration using containers, commands, and mounted volumes. This tooling implements another public library of mine, [gograph](https://github.com/jrcasso/gograph), to power an elegant lifecycle loop.|
| [tugboat](https://github.com/jrcasso/tugboat)    | A microservice provisioning automation tool. Automates the creation and configuration of service dependencies for new microservices. |
| [mailbucket](https://github.com/jrcasso/mailbucket)     | An email server that uploads incoming emails to an S3 bucket. Useful for email data processing. |
| [SujuNN](https://github.com/jrcasso/SujuNN)     | A convolutional neural network that identifies N-sided polygons. |

### Libraries, Frameworks, and Collections
| Repository | Language | Description |
|-|-|-|
| [conduit](https://github.com/jrcasso/conduit) | Go | A minimal, concurrent, asynchronous file processing ETL library for AWS S3 |
| [gograph](https://github.com/jrcasso/gograph) | Go | A library providing graph theory primitives and operations |

### Terraform Modules (Infrastructure as Code)

If you're looking to create and maintain a proper engineering-org scale AWS infrastructure with Terraform, these modules will get you ~90% of the way there. These modules follow a DNS zone strategy as devised [here](https://github.com/jrcasso/mean-demo/issues/50), and implement ingress domains with a maintainable, extensible, and practical strategy for service-based application architectures. If you're also interested in microservices (for which these modules are indeed compatible!), be sure to check out the k8s [tugboat](https://github.com/jrcasso/tugboat) project.

| Repository                 | Description |
| ---------------------- | ----------- |
| [terraform-aws-organizations](https://github.com/jrcasso/terraform-aws-organizations) | Deploy infrastructure for an organization with a domain name |
| [terraform-aws-operations](https://github.com/jrcasso/terraform-aws-operations) | Deploy infrastructure for an operation within an organization (e.g. stage, prod) |
| [terraform-aws-applications](https://github.com/jrcasso/terraform-aws-applications) | Deploy infrastructure for an application within an operation
