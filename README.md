# Awesome-Serverless-Visual-Workflow-Orchestration

## Top Serverless Visual Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Visual Workflow Design, Durable Execution & Self-Hosted Automation*  

**Last updated: October 2026**



This repository tracks notable **commercial workflow orchestration platforms** and **open-source projects** that let teams design, execute, and monitor multi-step business processes — from visual drag-and-drop builders to durable code-first execution engines.



**Examples** include AWS Step Functions, Temporal Cloud, Camunda Platform 8, Zapier, Make, Workato, n8n Cloud, Azure Logic Apps, Google Cloud Workflows, and Inngest (the category leaders).



**Open-source emphasis**: Workflow orchestration is one of the strongest open-source domains. **n8n** leads with 100,000+ GitHub stars and 400+ integrations. **Temporal** provides durable execution for mission-critical workflows. **Camunda** brings BPMN-based process orchestration. **Windmill** and **Kestra** offer developer-first alternatives. **Node-RED** and **Huginn** cover event-driven automation. **Dify**, **Flowise**, and **LangFlow** add AI/LLM orchestration. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Step Functions](https://aws.amazon.com/step-functions/)**  

  **AWS's serverless workflow orchestration** — visual state machines for coordinating Lambda, ECS, and AWS services. **No infrastructure to manage** — pay per state transition . **Best for AWS-native workflows** .



- **[Temporal Cloud](https://temporal.io/)**  

  **Managed durable execution platform** — code-first workflows that survive crashes and outages . **The enterprise standard for mission-critical orchestration** . **Best for complex, long-running workflows** .



- **[Camunda Platform 8](https://camunda.com/)**  

  **BPMN-based process orchestration** — visual modeling, execution, and monitoring . **The enterprise standard for business process automation** . **Best for BPMN workflows** .



- **[Zapier](https://zapier.com/)**  

  **The most popular no-code automation platform** — 6,000+ app integrations . **Best for simple app-to-app automation** .



- **[Make](https://www.make.com/)**  

  **Visual automation platform** — 2,000+ apps with advanced logic and error handling . **Best for complex no-code workflows** .



- **[Workato](https://www.workato.com/)**  

  **Enterprise automation platform** — 1,000+ apps with governance and security . **Best for enterprise automation** .



- **[n8n Cloud](https://n8n.io/)**  

  **Managed version of the leading open-source workflow platform** — see Open-Source section for details.



- **[Azure Logic Apps](https://azure.microsoft.com/en-us/products/logic-apps/)**  

  **Microsoft's workflow automation** — 400+ connectors with Azure integration . **Best for Microsoft-centric organizations** .



- **[Google Cloud Workflows](https://cloud.google.com/workflows)**  

  **Google's serverless workflow engine** — YAML-based orchestration of Google Cloud services . **Best for GCP-native workflows** .



- **[Inngest](https://www.inngest.com/)**  

  **Event-driven workflow platform for serverless functions** — automatic retries, step functions, and fan-out . **Best for modern event-driven workflows** .



## Open-Source GitHub Projects



### General Workflow Automation



- **[n8n](https://github.com/n8n-io/n8n)**  

  **The most popular self-hostable workflow automation platform**, Sustainable Use License (fair-code, not OSI) with **100,000+ GitHub stars** . **400+ integrations, visual editor, JavaScript/Python code nodes, and AI nodes built on LangChain** . **The de facto open-source Zapier alternative** — used by thousands of teams . **Note**: Internal use is free, but hosting for customers requires a commercial license . **Best for general-purpose workflow automation** .



- **[Windmill](https://github.com/windmill-labs/windmill)**  

  **Developer-first automation platform**, AGPLv3 licensed with **10,000+ GitHub stars** . **Write scripts in Python, TypeScript, Go, Bash, or SQL** . **Auto-generates UIs from function parameters** — with built-in approval flows and Git sync . **Ideal for teams wanting code + real ops, not a pure node canvas** . **Best for developer-centric automation** .



- **[Kestra](https://github.com/kestra-io/kestra)**  

  **Declarative orchestration platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **YAML-based workflow definition** — language-agnostic . **Event-driven and scheduled workflows** with 500+ plugins . **Best for declarative, data-oriented orchestration** .



- **[Node-RED](https://github.com/node-red/node-red)**  

  **Flow-based programming for event-driven applications**, Apache-2.0 licensed with **20,000+ GitHub stars** . **Visual wiring of devices, APIs, and services** . **The standard for IoT automation** — used by IBM, Siemens, and thousands of makers . **Best for IoT and event-driven automation** .



- **[Huginn](https://github.com/huginn/huginn)**  

  **Agent-based automation for web monitoring**, MIT licensed with **45,000+ GitHub stars** . **Monitor websites, scrape data, and trigger actions** . **The original open-source IFTTT alternative** — mature but development has slowed . **Best for web monitoring and scraping** .



- **[Activepieces](https://github.com/activepieces/activepieces)**  

  **MIT-licensed AI-native automation platform**, MIT licensed with **23,000+ GitHub stars** . **Clean UI with 200+ integrations and MCP server support** . **The most direct open-source alternative to n8n with OSI-approved licensing** . **Best for teams needing MIT licensing** .



### Durable Execution



- **[Temporal](https://github.com/temporalio/temporal)**  

  **The leading durable execution platform**, MIT licensed with **15,000+ GitHub stars** . **Workflows survive crashes and resume from exact failure points** . **Supports Go, Java, Python, TypeScript, PHP, .NET SDKs** . **The reference for mission-critical workflow orchestration** — used by Stripe, Netflix, and Snap . **Best for long-running, reliable workflows** .



- **[Cadence](https://github.com/uber/cadence)**  

  **Uber's durable execution engine** (predecessor to Temporal), MIT licensed . **High-scale workflow orchestration** . **Best for large-scale workflow systems** .



- **[Restate](https://github.com/restatedev/restate)**  

  **Durable execution for microservices**, BSL licensed . **Lightweight alternative to Temporal** . **Best for simple durable workflows** .



### BPMN & Process Orchestration



- **[Camunda Platform 7](https://github.com/camunda/camunda-bpm-platform)**  

  **Open-source BPMN workflow engine**, Apache-2.0 licensed . **Visual modeling, execution, and monitoring** . **The de facto open-source BPMN engine** . **Best for BPMN workflows** .



- **[Flowable](https://github.com/flowable/flowable-engine)**  

  **Open-source BPMN and DMN engine**, Apache-2.0 licensed . **Lightweight and embeddable** . **Best for Java-centric BPMN** .



- **[Activiti](https://github.com/Activiti/Activiti)**  

  **Open-source BPMN engine** (foundation for Flowable and Camunda), Apache-2.0 licensed . **Best for legacy BPMN deployments** .



### AI/LLM Workflow Orchestration



- **[Dify](https://github.com/langgenius/dify)**  

  **Open-source LLM app development platform**, Apache-2.0 licensed with **150,000+ GitHub stars** . **Visual workflow builder for AI agents, RAG, and prompt orchestration** . **Best for AI-powered workflows** .



- **[Flowise](https://github.com/FlowiseAI/Flowise)**  

  **Drag-and-drop LLM app builder**, Apache-2.0 licensed with **152,000+ GitHub stars** . **LangChain-based with visual node editor** . **Best for AI workflow prototyping** .



- **[LangFlow](https://github.com/langflow-ai/langflow)**  

  **Visual framework for multi-agent and RAG applications**, MIT licensed with **152,000+ GitHub stars** . **Python-based with LangChain integration** . **Best for AI engineers** .



- **[Sim](https://github.com/simstudioai/sim)**  

  **Open-source AI agent orchestration workspace**, Apache-2.0 licensed with **29,000+ GitHub stars** . **Visual workflow builder with 1,000+ integrations** . **Best for AI agent workflows** .



### Additional Strong Open-Source Options



- **Prefect** — Python-native data workflow orchestration .

- **Apache Airflow** — Workflow orchestration for data pipelines .

- **Dagster** — Data orchestration with asset graph .

- **Argo Workflows** — Kubernetes-native workflow engine .

- **Conductor (Netflix)** — Microservices orchestration .

- **Zeebe** — Camunda's cloud-native workflow engine .

- **Automatisch** — Simple open-source Zapier alternative .

- **Beehive** — Event-driven automation .

- **StackStorm** — Event-driven automation for DevOps .



**Frameworks for building custom workflow orchestration**: Choose based on use case. **n8n** for general-purpose automation with 400+ integrations . **Temporal** for durable execution of mission-critical workflows . **Camunda** for BPMN process orchestration . **Windmill** for developer-first code-based automation . **Kestra** for declarative YAML workflows . **Node-RED** for IoT and event-driven automation . **Dify**, **Flowise**, or **LangFlow** for AI/LLM workflows . Note that true enterprise workflow orchestration with managed infrastructure, global scale, and vendor-supported SLAs (Step Functions, Temporal Cloud, Camunda Platform 8) remains primarily commercial territory; open-source stacks provide strong visual design, durable execution, and integration foundations that require integration for complete enterprise deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow orchestration platforms execute business logic and may handle sensitive data. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **License considerations**: n8n uses Sustainable Use License (fair-code, not OSI), Windmill uses AGPLv3, and Temporal uses MIT. Verify licensing against your use case before committing .

- **Durable execution requires state management** — Temporal and Cadence persist workflow state. Self-hosted deployments require database and storage planning .

- **AI workflow platforms evolve rapidly** — Dify, Flowise, and LangFlow are actively developed with frequent releases. Evaluate stability before production use.

- The open-source ecosystem provides strong visual design, durable execution, and integration foundations, but **managed infrastructure, global scale, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for automation engineers, platform teams, and organizations seeking workflow orchestration sovereignty.**  

Let's make serverless visual workflow orchestration more open, transparent, and reliable.
