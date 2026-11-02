# Awesome-Digital-Workplace-Portal

# Awesome-Digital-Workplace-Portal

**Top Digital Workplace Portal (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Employee Intranets, Communications Hubs, Knowledge Bases & Self-Hosted Digital Workplaces*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Workplace Portals**. These tools enable organizations to connect employees with news, tools, people, and knowledge in a unified hub—from fully managed platforms with social feeds and AI integration to self-hosted alternatives that give organizations control over their internal communications and data.



**Examples** include Simpplr, Workvivo, Microsoft Viva Connections, LumApps, Staffbase, Interact Software, Jostle, MangoApps, Unily, and Atlassian Home (the category leaders in commercial space).



**Open-source emphasis**: This section is expanded with every relevant project for self-hosted intranets, digital workplaces, and open communication infrastructure. **Critical note**: The open-source landscape is anchored by **eXo Platform**—a 20-year veteran serving over a million users including the French presidential palace and the US Department of Defense . **HumHub** provides a modern social intranet with 80+ modules , and **Open Intranet** offers a Drupal-based starter kit for quick deployment . No open-source project matches Simpplr's AI-native employee experience or Viva's Microsoft 365 integration, but for core intranet functionality, the options are production-proven.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **Simpplr**

  **AI-powered employee experience platform** with intranet and communications. **Pricing**: **Quote-only, volume-based**; no published price list or named plans; discounts start at **500+ employees**; **14-day trial** (limited spaces) . **Free tier**: Trial only. **Best for**: enterprises wanting an AI-native intranet with strong support and 4 releases/year—**trade-off**: no public pricing; sales-led evaluation.



- **Workvivo**

  **Employee communications and engagement platform**. **Pricing**: **Business plan starts at ~$20,000/year** for 250–2,000 employees; **Enterprise** for 2,000+ employees with dedicated account manager and API access . **Free tier**: None. **Best for**: organizations wanting a social-feed style intranet with strong mobile and live streaming—**trade-off**: minimum ~$20K/year; engagement depends on adoption .



- **Microsoft Viva Connections**

  **Intranet and communications hub inside Microsoft Teams**. **Pricing**: **Included in all Microsoft 365 plans at no additional cost**; Viva Suite (9 modules) at **$12/user/month** . **Free tier**: Included with M365. **Best for**: Microsoft 365 organizations wanting an intranet without additional licensing—**trade-off**: limited standalone features; requires M365 ecosystem.



- **LumApps**

  **Employee experience platform** with 100+ integrations. **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting a centralized hub across multiple business systems.



- **Staffbase**

  **Employee communications and intranet** with frontline worker support. **Pricing**: Quote-only. **Free tier**: None. **Best for**: distributed enterprises with mixed desk and frontline workforces.



- **Interact Software**

  **Intranet software** with social features and analytics. **Pricing**: Quote-only. **Free tier**: None. **Best for**: mid-market to enterprise intranets with strong communications focus.



- **Jostle**

  **Employee intranet** with people directory and news. **Pricing**: Quote-only. **Free tier**: None. **Best for**: SMBs wanting a simple, people-centric intranet.



- **MangoApps**

  **Unified digital workplace** with intranet, collaboration, and training. **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting a single platform for intranet, files, and learning.



- **Unily**

  **Enterprise intranet** with AI and integrations. **Pricing**: Quote-only. **Free tier**: None. **Best for**: large enterprises needing a polished, customizable digital workplace.



- **Atlassian Home**

  **Centralized workspace** within Atlassian ecosystem. **Pricing**: Included with Atlassian Cloud subscriptions. **Free tier**: Limited. **Best for**: Atlassian customers wanting a unified home for Jira, Confluence, and other tools.



## Open-Source GitHub Projects



- **eXo Platform**

  **Open-source digital workplace and intranet** (LGPL) — **the most mature open-source digital workplace**, with **20+ years of development** and **over a million users** worldwide . **Features**: **No-code platform**—easily configured to organizational needs; **AI integration** via Wikit partnership for AI-powered chatbot; **customized mobile and desktop applications**—fully responsive PWA with automatic branding; **social intranet features**—spaces, news, documents, wikis, and collaboration; **secure and private**—on-premise, private cloud, or custom infrastructure . **Tech stack**: Java (Spring Boot), Tomcat, modern JDK21 architecture . **Deploy**: Self-hosted (on-premise, private cloud) or managed. **Trade-off**: **Enterprise-oriented**—requires Java infrastructure and administration; Community version lags behind Cloud releases . **Best for**: large organizations and public sector institutions wanting a proven, secure digital workplace with full data control—especially those with Java expertise and data sovereignty requirements.



- **HumHub**

  **Open-source social intranet and community software** (AGPL-3.0 for Community Edition) — **the most accessible open-source social intranet** with a modern interface and 80+ modules . **Features**: **Social network core**—profiles, spaces, posts, comments, likes, and private messaging; **Content collaboration**—articles, surveys, wikis, galleries, and OnlyOffice integration for real-time document editing ; **Modules ecosystem**—80+ extensions including News, Messenger, Calendar, LDAP, SAML SSO, and Translation Manager ; **Granular permissions**—multi-level system with Admin, Moderator, Editor, and read-only roles ; **Full-text search** across content, spaces, users, and files . **Tech stack**: PHP (Yii2), MySQL/MariaDB. **Deploy**: Self-hosted (Docker) or HumHub Cloud. **Trade-off**: **No native advanced analytics**; social intranet focus rather than full digital workplace . **Best for**: organizations wanting a modern, social intranet that employees actually enjoy using—especially SMBs and mid-market teams that find eXo too heavy.



- **Open Intranet (Drupal)**

  **Drupal-based intranet starter kit** (GPL) — **the fastest path to a Drupal intranet**, maintained by Droptica . **Features**: **Ready-to-use functionality**—news and announcements, events calendar, knowledge base, document management, employee directory, and user management with LDAP integration; **Responsive design**—works across desktop and mobile; **Starter theme** included for branding customization . **Tech stack**: Drupal, PHP, MySQL. **Deploy**: Self-hosted (DDEV for local; standard Drupal deployment for production). **Trade-off**: **Drupal-dependent**—requires Drupal expertise; starter kit, not a finished product. **Best for**: organizations already on Drupal wanting to build an intranet without starting from scratch—especially those with existing Drupal developers.



- **IntranetOS Employee Intranet**

  **WordPress plugin connecting to Microsoft Entra ID** (GPL) — **the most accessible Microsoft-integrated intranet** for WordPress sites . **Features**: **Microsoft Entra ID SSO**—"Sign in with Microsoft" with OAuth2 + PKCE; **Employee sync and directory**—pulls users from Entra ID via Graph delta sync, front-end directory with department filtering; **Engagement pack**—announcements, kudos wall, polls, celebrations (birthdays/anniversaries), FAQ knowledge base, and personal daily dashboard; **Six Gutenberg blocks** for news cards, event grids, quick actions, document accordions, portal carousels, and employee directory cards; **One-click intranet setup** wizard . **Tech stack**: WordPress (PHP). **Deploy**: Self-hosted WordPress + Entra ID app registration. **Trade-off**: **WordPress-dependent**—requires WordPress and Microsoft 365/Entra ID; commercial edition needed for SharePoint/Power BI connectors . **Best for**: Microsoft-centric organizations with WordPress wanting a lightweight intranet with Entra ID SSO and employee engagement features—without per-user fees.



### Additional Strong Open-Source Options



- **dotCMS** — Source-available intranet CMS (BSL). Free for organizations under $5M total finances and non-production use; converts to GPLv3 after 4 years. **Note**: **Source-available, not OSI open source**—verify license compatibility for commercial production use . **Best for**: mid-market enterprises wanting a modern intranet CMS with a defined path to open source.

- **Plone** — Enterprise CMS with strong security (GPL). **Note**: Often used for intranets needing military-grade security and granular permissions . **Best for**: security-sensitive intranets.

- **Nextcloud Hub** — File sync and collaboration with intranet capabilities (AGPL). **Note**: Strong file collaboration; intranet features via apps rather than native. **Best for**: teams wanting file-first collaboration with intranet components.



**Frameworks for building custom systems**: Combine **eXo Platform** for enterprise digital workplace with **HumHub** for social intranet features and **IntranetOS** for Microsoft-integrated lightweight deployment—creating a layered open-source intranet stack. **None of these match Simpplr's AI-native experience or Viva's M365 integration**, but for core intranet functionality, the options are production-proven.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Digital workplace portals handling employee data and internal communications must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for internal content.

- **The "enterprise digital workplace" vs. "social intranet" vs. "starter kit" vs. "WordPress plugin" distinction is critical.** **eXo Platform** is an **enterprise digital workplace**—mature, secure, and feature-complete, with 20+ years of development and million-user deployments . **HumHub** is a **social intranet**—modern, engaging, and accessible, with 80+ modules for extension . **Open Intranet** is a **starter kit**—a foundation to build upon, not a finished product . **IntranetOS** is a **WordPress plugin**—lightweight and Microsoft-integrated, but WordPress-dependent . **Choose based on whether you need enterprise depth, social engagement, a foundation, or lightweight integration.**

- **eXo Platform is the most proven open-source digital workplace**, serving over a million users including the Élysée Palace, Inria, and the US Department of Defense . **The trade-off**: Java infrastructure and administration overhead; Community version lags Cloud releases.

- **HumHub is the most accessible open-source social intranet**—80+ modules, OnlyOffice integration, and a modern social interface . **The trade-off**: limited analytics; social intranet focus rather than full digital workplace.

- **Simpplr's pricing is entirely quote-based**—no public rates, volume discounts at 500+ employees, and a 14-day trial with limited spaces . **Do not expect self-serve evaluation.**

- **Workvivo's Business plan starts at ~$20,000/year** for 250–2,000 employees—a significant minimum for smaller organizations . **Engagement depends on adoption; without active use, the platform can feel quiet** .

- **Microsoft Viva Connections is included in all Microsoft 365 plans**—the most accessible entry point for Microsoft-centric organizations . **The trade-off**: limited standalone features; requires M365 ecosystem.

- **dotCMS is source-available, not OSI open source.** Free use is limited to organizations under $5M total finances and non-production environments; enterprise production requires licensing . **Verify license compatibility before adopting.**

- Self-hosted open-source solutions require proper infrastructure (Java for eXo, PHP for HumHub/WordPress/Drupal), security hardening, and ongoing maintenance. **Employee data and internal communications are sensitive**—ensure your deployment meets your organization's privacy and security requirements before launching.



---



**Made for internal communications teams, IT administrators, and organizations building transparent digital workplace solutions.**

Let's make Digital Workplace Portals more open, data-driven, and employee-connected.
