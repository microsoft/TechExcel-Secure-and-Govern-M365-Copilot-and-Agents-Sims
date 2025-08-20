---
title: Introduction
layout: home
nav_order: 1
---

# TechExcel: Secure and Govern M365 Copilot and Agents

This lab is designed for anyone interested in the app modernization process. Lerners will evaluate Microsoft 365 Copilot and custom agents with Microsoft Purview controls to prevent data exfiltration and oversharing. By the end, leraners will have practical experience assessing label coverage, gating Copilot access, enabling audit & analytics, and applying dynamic protections and governance.

## Architecture
!IMAGE[purview-architecture.png](images/purview-architecture.png)

> [!note]
> The scenarios use Microsoft 365 E5 capabilities across Purview (Information Protection, DLP, Insider Risk Management, Audit, Data Lifecycle Management), SharePoint Online, and Entra Conditional Access.

## Exercises
In this lab you'll perform the following exercises:
1. Inventory labels and analyze Copilot coverage.
1. Restrict Copilot and SharePoint search to an allow‑listed set of sites.
1. Turn on audit, activate Copilot DSPM(Data Security Posture Management) policies, and enable DLP/IRM analytics.
1. Review the default DSPM assessment and mitigate oversharing risks.
1. Apply sensitivity labels, auto‑label content, and block Copilot on sensitive items.
1. Enable adaptive protection and conditional access for risky users.
1. Govern Copilot interactions with retention, audit, eDiscovery, and AI compliance.

## Customer story
**Contoso research** is an R&D‑driven company building next‑gen power solutions. After a recent leak halted a sensitive project, leadership wants to adopt AI safely. They’ve expanded Microsoft 365 and configured Purview, but usage was limited to “lower‑risk” data. They’re concerned about Teams and shadow AI usage. Funding is not a blocker—they’ll pay for controls that prevent leakage. Their goals are to:
1. prevent exfiltration of sensitive data across OneDrive, SharePoint, Exchange, and on‑prem sources.
1. automate classification to catch missed content.
1. ensure Copilot and agent interactions honor security and compliance.
1. provide auditable trails of all AI interactions.

**Key contacts:**
1. CTO (Andre Lawson)
1. CISO (Lisa Taylor)
1. VP Finance (Eugenia Lopez)
1. Security Architect (Juan Morgan)
