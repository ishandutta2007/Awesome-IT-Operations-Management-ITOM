# Awesome-IT-Operations-Management-ITOM

## Top IT Operations Management (ITOM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Infrastructure Monitoring, AIOps & Event Correlation*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **IT Operations Management (ITOM)**. These tools enable IT teams to monitor infrastructure health, correlate events across hybrid environments, detect anomalies with AI/ML, and automate remediation—ensuring availability, performance, and efficiency of digital services.



**Examples** include ServiceNow IT Operations Management, Dynatrace, Datadog, New Relic, Splunk, BMC Helix Operations Management, ScienceLogic SL1, LogicMonitor, SolarWinds, and AppDynamics (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted observability, alert management, and AIOps platforms—ideal for organizations building sovereign operations infrastructure without per-host or per-metric licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow IT Operations Management](https://www.servicenow.com/)**  

  ITOM suite on the Now Platform including Service Observability, Health Log Analytics, Metric Intelligence, and Event Management; streams real-time signals from 12,000+ apps, 5,000+ servers, and 30,000 employees into a unified dashboard for predictive insight and root cause analysis; integrates with Dynatrace for closed-loop autonomous remediation .



- **[Dynatrace](https://www.dynatrace.com/)**  

  AI-powered observability platform with Davis AI for deterministic and agentic root cause analysis, predictive detection, and preventive operations; Davis AI now generates natural language problem summaries, specific remediation steps, and even Kubernetes deployment artifacts to prevent issues before they impact users .



- **[Datadog](https://www.datadoghq.com/)**  

  Cloud observability platform with infrastructure monitoring, APM, log management, and AI-powered anomaly detection; DASH 2026 announcements include expanded integrations for Nebius AI Cloud, Google Cloud Run Jobs, Vercel functions, Azure AI Foundry, and n8n agentic workflows .



- **[New Relic](https://newrelic.com/)**  

  Observability platform that moved Service Architecture Intelligence (SAI), predictive alerting, and public dashboards into its Core Observability offering as of June 2026; NRQL Predictions and Predictive Alerting enable proactive anomaly detection before thresholds are breached .



- **[Splunk](https://www.splunk.com/)**  

  IT Service Intelligence (ITSI) 5.0 released June 2026 with new guided installation, AI-powered service and KPI discovery, Event iQ Detect and Diagnose for alert noise reduction, redesigned episode review, and CMDB enrichment from ServiceNow and Jira .



- **[BMC Helix Operations Management](https://www.bmc.com/)**  

  AIOps platform with centralized data lake, AI/ML event correlation for root cause diagnostics, dynamic service modeling, and automated remediation for recurring problems; integrates with BMC Helix AIOps for service-centric infrastructure views .



- **[ScienceLogic SL1](https://sciencelogic.com/)**  

  AIOps observability platform for hybrid cloud operations; detects misconfigurations (e.g., unauthorized Linux accounts, out-of-policy AWS autoscaling), opens enriched ITSM tickets, and recommends one-click remediations with policy enforcement and intelligent runbook actions .



- **[LogicMonitor](https://www.logicmonitor.com/)**  

  AI-first hybrid observability platform with Edwin AI agents; customers report 80%+ noise reduction and up to 67% fewer incidents; LM Uptime and Dynamic Service Insights map technology performance to business services across on-premises, cloud, and edge .



- **[SolarWinds](https://www.solarwinds.com/)**  

  IT Operations Manager with cross-stack management for network, virtualization, storage, and cloud (AWS/Azure); features application-centric dependency mapping, predictive intelligence for capacity planning, and single-click remediation for performance issues .



- **[AppDynamics](https://www.appdynamics.com/)**  

  Application performance monitoring and ITOM platform with real-time visibility into every database, application, and cloud instance; provides end-to-end transaction tracing and infrastructure correlation for root cause analysis in complex hybrid environments .



## Open-Source GitHub Projects



- **[Keep](https://github.com/keephq/keep)**  

  Leading open-source AIOps and alert management platform (Python, ~11,500 GitHub stars); aggregates alerts from multiple monitoring tools, deduplicates and correlates events, and provides a unified interface for incident response with workflow automation and AI-powered enrichment .



- **[Netdata](https://github.com/netdata/netdata)**  

  Real-time infrastructure monitoring platform with 800+ integrations; features automatic dashboard generation, ML-based anomaly detection trained at the edge, automated root cause analysis with anomaly advisor, and support for Linux, Windows, FreeBSD, macOS, Kubernetes, and IoT devices; collects metrics, logs, and network data with per-second resolution .



- **[AutoOps (天枢)](https://github.com/opsre/AutoOps)**  

  Enterprise-grade open-source IT operations automation platform (Go + Vue3); integrates CMDB asset management (hosts across Alibaba/Tencent/Baidu/Huawei clouds and jump servers), Kubernetes cluster management, task scheduling (Shell/Python/Ansible), monitoring center, and operation auditing; designed to break down silos between CI/CD, monitoring, CMDB, and K8s systems .



### Additional Strong Open-Source Options



- **Prometheus + Grafana** — The de facto open-source monitoring and visualization stack; Prometheus collects metrics with a pull model and PromQL query language, while Grafana provides dashboards and alerting across multiple data sources.

- **Zabbix** — Enterprise-class open-source monitoring solution for networks, servers, and applications with agent-based and agentless checks, auto-discovery, and distributed monitoring.

- **Icinga** — Open-source monitoring system with a modular architecture, REST API, and support for distributed setups; a flexible alternative to Nagios with active community development.

- **OpenSearch + OpenSearch Dashboards** — Apache 2.0 licensed fork of Elasticsearch/Kibana for log analytics and observability; can be paired with data shippers for a self-hosted log management pipeline.

- **Uptime Kuma** — Lightweight self-hosted uptime monitoring tool with a clean UI, supporting HTTP/TCP/Ping/DNS/ Push monitors and notifications to 90+ services; suitable for small teams needing simple availability checks.



**Frameworks for building custom systems**: Combine **Keep** for AIOps alert correlation and incident management, **Netdata** for real-time infrastructure metrics with embedded ML anomaly detection, **Prometheus + Grafana** for metrics collection and dashboards, and **AutoOps** for CMDB and automation orchestration in a self-hosted ITOM stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- ITOM platforms handling infrastructure telemetry and operational data must comply with applicable security and privacy regulations; metrics and logs can reveal sensitive system architecture.

- Self-hosted open-source solutions vary in AIOps maturity—Keep and Netdata provide strong foundations for alert correlation and anomaly detection, but full closed-loop remediation typically requires integration with commercial ITSM platforms.

- Verify license terms for commercial use; Keep uses a custom license (check repository), Netdata uses GPL-3.0 for the agent, and AutoOps is an independent open-source project.



---



**Made for IT operations teams, SREs, NOC analysts, and infrastructure engineers.**  

Let's make IT operations management more open, observable, and automated.
