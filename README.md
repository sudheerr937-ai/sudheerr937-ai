# Sudheer Reddy Patlolla

<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=200&section=header&text=Sudheer%20Patlolla&fontSize=50&fontColor=ffffff&fontAlignY=35&desc=RPA%20Developer%20%C2%B7%20Automation%20Engineer%20%C2%B7%20Open%20Source%20Contributor&descAlignY=55&descColor=a0aec0)

![Profile Views](https://komarev.com/ghpvc/?username=sudheerr937-ai&style=for-the-badge&color=0e75b6)
[![GitHub](https://img.shields.io/badge/GitHub-sudheerr937--ai-181717?style=for-the-badge&logo=github)](https://github.com/sudheerr937-ai)
[![UiPath](https://img.shields.io/badge/UiPath-Advanced%20Certified-F26522?style=for-the-badge&logo=uipath&logoColor=white)](https://github.com/sudheerr937-ai)

</div>

---

RPA Developer with 12+ years of experience building intelligent automation solutions for enterprise and government clients. UiPath Advanced Certified. Passionate about open source, cloud-native tools, and automation at scale.

---

## 🔀 Open Source Pull Requests

| Project | PR | Description | Status |
|---|---|---|---|
| [microcks/microcks](https://github.com/microcks/microcks/pull/2038) | #2038 | feat: add TLS support for Microcks HTTP endpoint | 🟡 Open |
| [robotframework/robotframework](https://github.com/robotframework/robotframework/pull/5650) | #5650 | fix: TypeInfoParser crash on PIPE token in type parameters | 🟡 Open |
| [UiPath/skills](https://github.com/UiPath/skills/pull/154) | #154 | fix: Integration Services Slack flow OAuth token bug | 🟡 Open |
| [cncf/glossary](https://github.com/cncf/glossary/pull/3626) | #3626 | feat: AI Chatbot glossary entry | 🟡 Open |

---

## 🌍 Open Source Contributions

### [Microcks](https://github.com/microcks/microcks) — CNCF Sandbox Project
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

Added TLS support for the Microcks HTTP endpoint via Helm chart changes across `deployment.yaml`, `configmap.yaml`, `service.yaml`, and `ingress.yaml`. Implemented conditional port switching (`8080` → `8443`) based on `httpEnableTLS` flag. Validated with `helm lint` and `helm template` locally.

- PR: [microcks/microcks#2038](https://github.com/microcks/microcks/pull/2038)
- Reviewed and approved by contributor `dipak0000812`
- 2 pending codeowner reviews (`yada`, `lbroudoux`)

---

### [Robot Framework](https://github.com/robotframework/robotframework) — 9.8k ⭐
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

Diagnosed and fixed issue [#5650](https://github.com/robotframework/robotframework/issues/5650) — a `TypeInfoParser` crash/hang on `|` (PIPE token) inside type parameters. Added an `else: self.error("Type name missing.")` clause and five targeted edge case tests. Navigated two rounds of maintainer feedback.

- PR: [robotframework/robotframework#5650](https://github.com/robotframework/robotframework/pull/5650)

---

### [UiPath/skills](https://github.com/UiPath/skills) — Official UiPath Repository
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![UiPath](https://img.shields.io/badge/UiPath-F26522?style=flat)

Created PR [#154](https://github.com/UiPath/skills/pull/154) from scratch (six project files) to fix an Integration Services flow bug involving Slack message reading — resolved incorrect `connectionId` format and OAuth token injection issues.

- PR: [UiPath/skills#154](https://github.com/UiPath/skills/pull/154)
- Also investigated issue #127 (description length limits) — confirmed resolved via PR #142

---

### [CNCF Glossary](https://github.com/cncf/glossary) — Cloud Native Computing Foundation
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)

Contributed AI Chatbot glossary entry (PR [#3626](https://github.com/cncf/glossary/pull/3626)) addressing issue #3624. Investigated Spanish localization issues.

- PR: [cncf/glossary#3626](https://github.com/cncf/glossary/pull/3626)

---

## 💼 Projects

### rpawatch — UiPath Orchestrator Monitor
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![AppSignal](https://img.shields.io/badge/AppSignal-E53E3E?style=flat)
![UiPath](https://img.shields.io/badge/UiPath-F26522?style=flat)

Open-source monitoring tool for UiPath Orchestrator — tracks job health, queue stats, and sends observability alerts. Built for government and critical infrastructure teams.

- Real-time job and queue monitoring
- AppSignal integration for alerts and observability
- Designed for high-availability government environments

---

### Government Process Automation — Eligibility & Benefits Workflows
![UiPath](https://img.shields.io/badge/UiPath-F26522?style=flat)
![VB.NET](https://img.shields.io/badge/VB.NET-512BD4?style=flat)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat)

End-to-end RPA automation for state government eligibility determination and benefits processing. Reduced manual processing time significantly across multiple departments.

- Automated eligibility checks across multiple legacy systems
- Exception handling and audit trail logging
- Integrated with state mainframe and web portals

---

### Document Processing Automation — Invoice & Claims
![UiPath](https://img.shields.io/badge/UiPath-F26522?style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat)

Intelligent document processing pipeline for invoice validation and claims management using UiPath Document Understanding and OCR.

- Automated extraction and validation of structured/unstructured documents
- ML-based document classification
- Reduced manual review effort across finance operations

---

### Power Automate — Enterprise Workflow Automation
![PowerAutomate](https://img.shields.io/badge/Power%20Automate-0066FF?style=flat&logo=microsoftpowerautomate&logoColor=white)
![Microsoft365](https://img.shields.io/badge/Microsoft%20365-D83B01?style=flat)

Cloud-based workflow automation using Power Automate for enterprise approval flows, SharePoint integrations, and Teams notifications.

---

## 🛠️ Technical Focus

| Domain | Stack |
|---|---|
| **RPA** | UiPath · Power Automate · Robot Framework |
| **Languages** | Python · Java · VB.NET |
| **Cloud Native** | Kubernetes · Helm · Docker |
| **Monitoring** | AppSignal · UiPath Orchestrator |
| **Exploring** | CNCF ecosystem · API Mocking · Helm charts |

---

## 🚀 Currently

- Contributing to Microcks, Robot Framework, UiPath ecosystem
- Building open-source RPA monitoring tooling — rpawatch
- Pursuing Power Automate certification

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:1a1a2e&height=100&section=footer)

</div>
