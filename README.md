# Awesome-Configurable-Business-Dashboard-Builder

## Top Configurable Business Dashboard Builder Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Drag-and-Drop Dashboard Creation, Embedded Analytics & Self-Service BI*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Configurable Business Dashboard Builders**. These tools enable teams to assemble interactive dashboards from multiple data sources without writing code—covering drag-and-drop editors, semantic layers, embedded analytics, and self-service BI that turns raw data into decision-ready visualizations.

**Examples** include Tableau, Microsoft Power BI, Looker, Domo, Sisense, Klipfolio, Geckoboard, Databox, GoodData, and Icertis Dashboard Builder (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted BI, open-source dashboard builders, and community-driven analytics platforms—ideal for organizations seeking data sovereignty and predictable costs over per-seat SaaS subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Tableau](https://www.tableau.com/)** | Industry-standard visual analytics platform with drag-and-drop dashboard creation, extensive chart types, and data source connectivity. Acquired by Salesforce; pricing tiers include Viewer, Explorer, and Creator roles . | Quote-only (per-user Creator/Explorer/Viewer licensing); Tableau Public free for public data | **Tableau Public**: free forever for publicly shared dashboards; no private data; **14-day trial** for full platform |
| **[Microsoft Power BI](https://powerbi.microsoft.com/)** | Microsoft's BI platform with desktop authoring, cloud publishing, and embedded analytics. Integrates deeply with Excel, Azure, and Microsoft 365. Dashboards can be embedded in applications via Power BI Embedded . | Pro: $14/user/month; Premium Per User: $24/user/month; Embedded: capacity-based | **Free**: Power BI Desktop (authoring only); **60-day trial** for Pro/Premium per user |
| **[Looker (Google Cloud)](https://looker.com/)** | BI platform built around a semantic modeling layer (LookML). Enables governed self-service analytics with consistent metric definitions across the organization . | Quote-only (enterprise contract; Google Cloud billing) | No free tier; trial via Google Cloud sales |
| **[Domo](https://www.domo.com/)** | Cloud BI platform with drag-and-drop dashboard builder, ETL, and embedded analytics. Positioned for business users with pre-built connectors and AI assistance . | Quote-only (consumption-based; typically enterprise) | No free tier; demo via sales |
| **[Sisense](https://www.sisense.com/)** | BI platform focused on embedded analytics for product teams. Allows embedding dashboards directly into customer-facing applications with white-labeling . | Quote-only (custom enterprise pricing) | No free tier; demo via sales |
| **[Klipfolio](https://www.klipfolio.com/)** | Dashboard builder focused on real-time business monitoring. Pre-built integrations with marketing, sales, and finance tools. | Quote-only (per-user); free plan discontinued | No free tier; **14-day trial** available |
| **[Geckoboard](https://www.geckoboard.com/)** | TV dashboard builder for teams. Simple drag-and-drop interface with pre-built integrations for KPIs and metrics. | From ~$39/month (billed annually) | **No free tier**; 14-day trial available |
| **[Databox](https://databox.com/)** | Dashboard builder for marketing and sales teams. Connects to 100+ tools and provides pre-built templates for common KPIs. | Free: $0 (3 users, 3 data sources); Starter: $47/month | **Free forever**: 3 users, 3 data sources, 3 dashboards; paid plans for more |
| **[GoodData](https://www.gooddata.com/)** | Embedded analytics platform with dashboard builder, semantic layer, and white-labeling for SaaS products. | Quote-only (consumption-based) | **Community Edition**: free for up to 5 users (self-hosted); **trial** for cloud |
| **[Icertis Dashboard Builder](https://www.icertis.com/)** | Configurable dashboard builder within the Icertis Contract Intelligence platform. Users can add widgets, reports, KPIs, and Power BI reports to role-specific dashboards. Admins can design dashboards for organizational requirements . | Included with Icertis CLM subscription (quote-only) | No separate free tier; trial via Icertis sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache Superset](https://github.com/apache/superset)** | [![Stars](https://img.shields.io/github/stars/apache/superset?style=social&color=white)](https://github.com/apache/superset/stargazers) | Open-source data exploration and BI platform. Drag-and-drop dashboard builder, rich visualization library, SQL Lab for ad-hoc queries, and role-based access. The most widely deployed open-source BI tool . |
| **[Metabase](https://github.com/metabase/metabase)** | [![Stars](https://img.shields.io/github/stars/metabase/metabase?style=social&color=white)](https://github.com/metabase/metabase/stargazers) | User-friendly open-source BI tool designed for non-technical teams. Simple question builder, dashboard creation, and embedded analytics. No SQL required for basic analysis . |
| **[Redash](https://github.com/getredash/redash)** | [![Stars](https://img.shields.io/github/stars/getredash/redash?style=social&color=white)](https://github.com/getredash/redash/stargazers) | Open-source SQL-based dashboard and visualization tool. Focuses on query writing with autocomplete, keyboard shortcuts, and results caching. Supports multiple data sources and alerting . |
| **[Lightdash](https://github.com/lightdash/lightdash)** | [![Stars](https://img.shields.io/github/stars/lightdash/lightdash?style=social&color=white)](https://github.com/lightdash/lightdash/stargazers) | Open-source BI platform built for dbt. Turns dbt models into dashboards without SQL; includes AI analyst co-pilot, version control, and CI/CD integration. Cloud option starts at $3,000/month with 21-day trial . |
| **[DashForge](https://github.com/plexusone/dashforge)** | [![Stars](https://img.shields.io/github/stars/plexusone/dashforge?style=social&color=white)](https://github.com/plexusone/dashforge/stargazers) | JSON-first dashboard framework with drag-and-drop visual builder. Starts simple with static hosting (GitHub Pages), grows into a Metabase-like platform with PostgreSQL, multi-tenancy, SSO, and Cube.js semantic layer. AI-powered widget generation from natural language . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Dashboard Studio (Rust + WASM)](https://github.com/automataIA/dashboard-studio-rs)** | [![Stars](https://img.shields.io/github/stars/automataIA/dashboard-studio-rs?style=social&color=white)](https://github.com/automataIA/dashboard-studio-rs/stargazers) | Privacy-first, client-side data visualization powered by Rust + WebAssembly. Upload CSV data, create dashboards with 11 chart types, drag-and-drop layout, auto-save to localStorage. Zero backend, 100% GDPR-compliant, <500KB bundle . |
| **[LobsterBoard](https://github.com/curbob/LobsterBoard)** | [![Stars](https://img.shields.io/github/stars/curbob/LobsterBoard?style=social&color=white)](https://github.com/curbob/LobsterBoard/stargazers) | Self-hosted drag-and-drop dashboard builder with live system monitoring and 45 widgets. No cloud dependencies; persists layout to config.json. Includes CPU/memory/Docker monitoring, AI cost tracking, and weather widgets . |
| **[Lowdefy](https://github.com/lowdefy/lowdefy)** | [![Stars](https://img.shields.io/github/stars/lowdefy/lowdefy?style=social&color=white)](https://github.com/lowdefy/lowdefy/stargazers) | Config web stack for building internal tools, dashboards, and admin panels with YAML or JSON. Self-hosted Next.js-based framework for CRUD apps and business dashboards . |

**Frameworks for building custom systems**: Combine **Apache Superset** for full-featured BI with SQL Lab and rich visualizations, **Metabase** for non-technical self-service analytics, **Lightdash** for dbt-native metric layers, and **DashForge** for AI-assisted JSON-first dashboards—all deployable via Docker Compose with PostgreSQL.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Dashboard builders connect to production data sources and can expose sensitive business metrics; enforce row-level security, SSO, and audit logging for dashboard access.
- SaaS pricing varies dramatically: some platforms charge per-user (Power BI, Geckoboard), others are quote-only enterprise contracts (Tableau, Looker, Domo). Open-source tools require infrastructure provisioning and ongoing maintenance but eliminate per-seat licensing. Lightdash's cloud starts at $3,000/month, making self-hosting the practical entry point for smaller teams .

---

**Made for business analysts, data teams, operations managers, and developers building analytics infrastructure.**  
Let's make configurable dashboard building more open, accessible, and cost-predictable.
