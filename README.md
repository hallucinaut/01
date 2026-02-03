# Agent Skills Repository

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/hallucinaut/01?style=social)](https://github.com/hallucinaut/01)
[![GitHub forks](https://img.shields.io/github/forks/hallucinaut/01?style=social)](https://github.com/hallucinaut/01)

## What are Agent Skills?

Agent Skills are structured, comprehensive definitions that enable AI agents to perform specialized tasks across a wide variety of domains. Think of them as "personas" or "expert profiles" that guide AI behavior, defining their role, mission, capabilities, protocols, and constraints.

Each skill includes:

- **Role** - The agent's primary function and expertise
- **Mission** - Clear objectives and purpose
- **Capabilities** - Specific skills and tools the agent can use
- **Protocols** - Standard operating procedures and workflows
- **Constraints** - Rules and limitations
- **Output Format** - How the agent should structure its responses

## Why Agent Skills Matter

Agent Skills provide:

- **Consistency** - Standardized behavior across AI interactions
- **Expertise** - Specialized knowledge in specific domains
- **Reliability** - Predictable and reliable outputs
- **Scalability** - Reusable definitions that can be applied across different AI platforms
- **Customization** - Tailored behaviors for specific use cases

These skills are designed to work with **every AI platform** that supports custom instructions, system prompts, or similar capabilities. Whether you're using Claude, ChatGPT, GPT-4, Claude 3, or any future AI system, these skills will help you get the most out of your AI interactions.

## What's Included

This repository contains **42 comprehensive agent skills** organized into 10 major domains:

### MLOps (5 Skills)
| Agent | Description |
|-------|-------------|
| [ML Engineer Agent](skills/mlops/ml-engineer.md) | Principal Machine Learning Engineer for model development, training, and deployment |
| [MLOps Engineer Agent](skills/mlops/mlops-engineer.md) | End-to-end ML lifecycle management and infrastructure |
| [Model Registry Agent](skills/mlops/model-registry.md) | Model lifecycle, versioning, and governance management |
| [Feature Store Agent](skills/mlops/feature-store.md) | Feature engineering, storage, and serving |
| [ML Observability Agent](skills/mlops/ml-observability.md) | Model monitoring, drift detection, and performance tracking |

### DevOps (5 Skills)
| Agent | Description |
|-------|-------------|
| [DevOps Engineer Agent](skills/devops/devops-engineer.md) | Infrastructure automation and CI/CD pipelines |
| [Site Reliability Engineer (SRE) Agent](skills/devops/sre-agent.md) | System reliability and performance optimization |
| [CI/CD Pipeline Agent](skills/devops/cicd-pipeline.md) | Automated build, test, and deployment processes |
| [Infrastructure as Code (IaC) Agent](skills/devops/infrastructure-as-code.md) | Infrastructure provisioning and management |
| [Kubernetes Engineer Agent](skills/devops/kubernetes-engineer.md) | Kubernetes cluster design and operations |

### DataOps (5 Skills)
| Agent | Description |
|-------|-------------|
| [Data Engineer Agent](skills/dataops/data-engineer.md) | Data pipeline design and implementation |
| [Data Pipeline Agent](skills/dataops/data-pipeline.md) | ETL/ELT automation and orchestration |
| [Data Quality Agent](skills/dataops/data-quality.md) | Data validation, monitoring, and governance |
| [Data Governance Agent](skills/dataops/data-governance.md) | Data policies, compliance, and stewardship |
| [Data Lake Engineer Agent](skills/dataops/data-lake.md) | Scalable data storage and management |

### Web Development (5 Skills)

### Builders (3 Skills)
| Agent | Description |
|-------|-------------|
| [API Builder Agent](skills/builders/api-builder.md) | Design and implement RESTful and GraphQL APIs |
| [App Builder Agent](skills/builders/app-builder.md) | Build end-to-end applications from concept to deployment |
| [Frontend Builder Agent](skills/builders/frontend-builder.md) | Build responsive, accessible, and performant user interfaces |

### Web Development (5 Skills)
| Agent | Description |
|-------|-------------|
| [Frontend Engineer Agent](skills/webdev/frontend-engineer.md) | Responsive, accessible, and performant UI development |
| [Backend Engineer Agent](skills/webdev/backend-engineer.md) | Scalable API design and implementation |
| [Full Stack Engineer Agent](skills/webdev/fullstack-engineer.md) | End-to-end application development |
| [Web Performance Agent](skills/webdev/web-performance.md) | Performance optimization and benchmarking |
| [Web Accessibility Agent](skills/webdev/web-accessibility.md) | WCAG compliance and inclusive design |

### Security (5 Skills)
| Agent | Description |
|-------|-------------|
| [Security Engineer Agent](skills/security/security-engineer.md) | Security controls and infrastructure protection |
| [Penetration Tester Agent](skills/security/penetration-tester.md) | Security assessments and vulnerability identification |
| [Security Analyst Agent](skills/security/security-analyst.md) | Security monitoring and incident response |
| [DevSecOps Engineer Agent](skills/security/devsecops-engineer.md) | Security integration into development workflows |
| [Threat Intelligence Agent](skills/security/threat-intelligence.md) | Threat intelligence collection and analysis |

### Cloud (5 Skills)
| Agent | Description |
|-------|-------------|
| [Cloud Architect Agent](skills/cloud/cloud-architect.md) | Cloud architecture design and implementation |
| [Cloud Engineer Agent](skills/cloud/cloud-engineer.md) | Cloud infrastructure management and operations |
| [AWS Specialist Agent](skills/cloud/aws-specialist.md) | AWS services and best practices |
| [GCP Specialist Agent](skills/cloud/gcp-specialist.md) | Google Cloud Platform expertise |
| [Azure Specialist Agent](skills/cloud/azure-specialist.md) | Microsoft Azure specialization |

### Platform (5 Skills)
| Agent | Description |
|-------|-------------|
| [Platform Engineer Agent](skills/platform/platform-engineer.md) | Internal Developer Platform (IDP) development |
| [Infrastructure Engineer Agent](skills/platform/infrastructure-engineer.md) | Infrastructure design and implementation |
| [Tooling & Automation Agent](skills/platform/tooling-automation.md) | Automation tools and developer utilities |
| [Internal Developer Platform (IDP) Agent](skills/platform/internal-developer-platform.md) | Self-service developer experience |
| [Platform Reliability Engineer (PRE) Agent](skills/platform/platform-reliability-engineer.md) | Platform reliability and performance |

### Utilities (4 Skills)
| Agent | Description |
|-------|-------------|
| [JSON/YAML Converter](skills/utilities/json-yaml-converter.md) | Convert between JSON, YAML, and TOML formats |
| [Regex Generator](skills/utilities/regex-generator.md) | Generate regex patterns for common use cases |
| [Validator Generator](skills/utilities/validator-generator.md) | Generate validation schemas for data validation |

### Builders (3 Skills)
| Agent | Description |
|-------|-------------|
| [API Builder Agent](skills/builders/api-builder.md) | Design and implement RESTful and GraphQL APIs |
| [App Builder Agent](skills/builders/app-builder.md) | Build end-to-end applications from concept to deployment |
| [Frontend Builder Agent](skills/builders/frontend-builder.md) | Build responsive, accessible, and performant user interfaces |

## How to Use Agent Skills

### For AI Platforms Supporting Custom Instructions

1. **Copy the skill file** that matches your needs
2. **Paste it into** your AI platform's custom instructions or system prompt field
3. **Customize as needed** - Modify role, mission, or add domain-specific constraints

### For AI Platforms Supporting Skills/Plugins

1. **Import the skill** following your platform's import mechanism
2. **Activate the skill** in your chat session
3. **Start interacting** with your specialized agent

### Customizing Skills

Each skill can be customized by modifying:
- The agent's role and mission
- Capabilities to match specific requirements
- Protocols to align with organizational processes
- Constraints to match platform limitations
- Output format to match preferred communication style

## Design Philosophy

Agent Skills are designed with:

- **Comprehensiveness** - Complete definitions covering all essential aspects
- **Reusability** - Modular structure that can be combined and adapted
- **Flexibility** - Customizable templates that work across use cases
- **Standards-Compliance** - Following industry best practices and standards
- **Platform-Agnostic** - Designed to work with any AI system

## License

MIT License - Feel free to use, modify, and distribute these skills for any purpose.

---

**Note:** This README was written by an agent as part of demonstrating the power and versatility of Agent Skills. The structure, content, and organization of this document were guided by the principles outlined in the agent skill definitions, showcasing how these skills can be applied beyond technical implementation to documentation and communication as well.
