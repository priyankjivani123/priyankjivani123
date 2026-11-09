<div align="center">

# Hi there, I'm Priyank Jivani 👋
### Senior Magento 2 / Adobe Commerce Backend Developer | MCP & AI Integration Architect

[![Upwork Profile](https://img.shields.io/badge/Upwork-Available%20for%20Hire-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/priyankjivani)
[![Magento 2](https://img.shields.io/badge/Magento%202-Adobe%20Commerce-FF7A00?style=for-the-badge&logo=magento&logoColor=white)](https://business.adobe.com/products/magento/magento-commerce.html)
[![Model Context Protocol](https://img.shields.io/badge/MCP-2024--11--05-blue.svg?style=for-the-badge)](https://modelcontextprotocol.io/)
[![PHP Compatibility](https://img.shields.io/badge/PHP-8.1%20%7C%208.2%20%7C%208.3%20%7C%208.4%20%7C%208.5%20(Audited)-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![Hyvä Themes](https://img.shields.io/badge/Hyv%C3%A4-Specialist-00D1B2?style=for-the-badge)](https://www.hyva.io/)
[![Location](https://img.shields.io/badge/Location-Ahmedabad%2C%20India-blue?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Ahmedabad,+India)

<p align="center">
  <b>4+ Years of Enterprise Magento 2 Backend Engineering</b> • 
  <b>Creator of Magento MCP Ecosystem</b> • 
  <b>Open Source Contributor</b> • 
  <b>E-Commerce Solution Architect</b>
</p>

---

</div>

## 🌟 Flagship Project: Magento Model Context Protocol (MCP) Ecosystem

I am the architect and creator of the **open-source Magento MCP Ecosystem**, connecting **Claude Desktop**, **Cursor IDE**, and autonomous AI agents directly to Magento 2 / Adobe Commerce via standard JSON-RPC 2.0 over STDIO:

* 🤖 **[magento2-mcp-server](https://github.com/priyankjivani123/magento2-mcp-server)**: High-performance standalone Model Context Protocol server exposing 20+ typed tools for Catalog, Orders, Inventory, Customers, Developer Diagnostics, and SEO.
* 🔌 **[magento2-mcp-bridge](https://github.com/priyankjivani123/magento2-mcp-bridge)**: Secure Magento 2 bridge extension (`PriyankJivani_McpBridge`) providing RBAC authorization (`READ_ONLY`, `WRITE`, `DESTRUCTIVE`), dry-run preview engines, and sensitive credential masking.

---

## 👨‍💻 Professional Summary

I am a dedicated **Magento 2 / Adobe Commerce Backend Developer & Solution Architect** with **4+ years of specialized experience** designing, engineering, optimizing, and maintaining scalable e-commerce systems for international merchants, digital agencies, and high-volume online retailers.

My expertise centers around the Magento core architecture: building robust custom extensions, developing declarative database schemas, designing high-throughput REST and GraphQL APIs, optimizing database queries and server-side cache (Varnish, Redis, FPC), and integrating modern frontend architectures such as **Hyvä Themes (Alpine.js & Tailwind CSS)**.

* 🌐 **Specialization:** Magento 2 Open Source, Adobe Commerce Cloud & On-Premise, PHP 8.1–8.5, Hyvä Themes, Performance Optimization, Custom Module Development, Third-Party ERP/CRM API Integrations.
* 📦 **Composer Package Development:** Author of 7 production-grade, open-source Magento 2 extensions installable via Composer VCS.
* 💼 **Availability:** Open for freelance contracts, long-term retainers, and technical consulting on [Upwork](https://www.upwork.com/freelancers/priyankjivani).
* 📍 **Timezone:** IST (UTC+5:30) with flexible overlap for North American, European, and Australian business hours.

---

## 🛠 Technical Skills & Architectural Expertise

| Category | Technologies & Competencies |
| :--- | :--- |
| **E-Commerce Platforms** | **Magento 2.4.x**, Adobe Commerce (Cloud & On-Premise), B2B Commerce, Multi-Store / Multi-Website setups |
| **AI & MCP Protocol** | **Model Context Protocol (MCP)**, AI Store Intelligence, Claude Desktop / Cursor Integrations, Automated Diagnostics |
| **PHP & Framework Architecture** | **PHP 8.1 / 8.2 / 8.3 / 8.4** (with ongoing **PHP 8.5** roadmap auditing), OOP, Dependency Injection (DI), Interceptors (Plugins), Event Observers, Service Contracts, Declarative Schema (`db_schema.xml`), Symfony Console CLI |
| **Frontend & Theme Engines** | **Hyvä Themes** (Alpine.js, Tailwind CSS), Magento Luma (Knockout.js, RequireJS, UI Components, CustomerData sections) |
| **APIs & Headless Commerce** | REST Web APIs (Custom endpoints, ACL, Swagger), GraphQL Queries & Mutations, ERP / CRM / WMS Integrations |
| **Search & Caching Tier** | **Varnish Cache**, Redis (Session & Backend cache), Elasticsearch 7/8, OpenSearch, Full Page Cache (FPC) Warming |
| **Database & Profiling** | MySQL 8.0, MariaDB, Complex EAV joins, Query Optimization, New Relic, Xdebug, Magento Blackfire profiling |
| **DevOps & Standards** | Composer Package Architecture, Git, Docker, Linux (Ubuntu/Debian), Nginx, PSR-12 & Magento Coding Standards (PHPCS, MEQP) |

---

## 🔬 PHP Version Compatibility & Verification Matrix

I rigorously engineer and test all extensions to ensure clean compatibility across PHP versions without deprecated features:

* **PHP 8.1 / 8.2 / 8.3:** Fully tested and officially certified on production Adobe Commerce / Magento Open Source 2.4.4 through 2.4.7-p3.
* **PHP 8.4:** Syntax-checked and forward-compatible. All codebase parameters use explicit nullable types (`?Type $param = null`), avoiding PHP 8.4 deprecation warnings.
* **PHP 8.5:** Extension code is compiled and verified under PHP 8.5 runtime. Production deployment is tracked in preview alignment with upcoming Adobe Commerce core releases.

---

## 🚀 Verified & Installable Magento 2 Extensions (Open-Source)

Every extension is installable via Composer VCS with tagged releases (`1.0.0`), automated PHPUnit test suites, and zero authentication barriers:

| Extension & Repository | Key Features | Architecture & Stack | Quick Composer Installation |
| :--- | :--- | :--- | :--- |
| **[Magento 2 MCP Bridge](https://github.com/priyankjivani123/magento2-mcp-bridge)** | Secure Model Context Protocol bridge for AI store automation, RBAC safeguards, and diagnostics. | `WebAPI REST`, `Service Contracts`, `AI Bridge`, `RBAC` | `composer require priyankjivani/module-mcp-bridge:^1.0.0` |
| **[Customer Testimonials](https://github.com/priyankjivani123/magento2-customer-testimonials)** | Full CRUD social proof module, Admin UI grid/forms, Image uploader, CLI bulk CSV importer. | `REST API`, `Declarative Schema`, `Symfony Console`, `UI Components` | `composer require priyankjivani/module-customer-testimonials:^1.0.0` |
| **[Free Shipping Progress](https://github.com/priyankjivani123/magento2-free-shipping-progress)** | Real-time dynamic cart progress bar driving higher AOV. Native dual support for Luma & Hyvä. | `Hyvä Theme`, `Alpine.js`, `Tailwind CSS`, `Knockout.js`, `CustomerData` | `composer require priyankjivani/module-free-shipping-progress:^1.0.0` |
| **[Cron Scheduler & Monitor](https://github.com/priyankjivani123/magento2-cron-scheduler-monitor)** | Developer diagnostics CLI tool: inspect live cron execution status, detect hung jobs, and trigger specific workers on-demand. | `Magento Cron`, `Symfony Console`, `DevOps Tooling`, `PHP 8` | `composer require priyankjivani/module-cron-scheduler-monitor:^1.0.0` |
| **[Full Page Cache Warmer CLI](https://github.com/priyankjivani123/magento2-cache-warmer-cli)** | Asynchronous multi-curl crawler to pre-warm Varnish and Magento FPC after catalog updates or deployments. | `Varnish`, `FPC`, `Multi-cURL Asynchronous Pool`, `Performance` | `composer require priyankjivani/module-cache-warmer-cli:^1.0.0` |
| **[Admin Product Notes](https://github.com/priyankjivani123/magento2-admin-product-notes)** | Back-office management extension enabling merchant internal notes linked to products, searchable selectors, and REST endpoints. | `Catalog Management`, `Admin UI Grid`, `REST WebAPI`, `Service Contracts` | `composer require priyankjivani/module-admin-product-notes:^1.0.0` |
| **[Order Comment History API](https://github.com/priyankjivani123/magento2-order-comment-history-api)** | Lightweight REST endpoints to read and append order status comments without loading heavy 500+ field Order models. | `REST WebAPI`, `Service Contracts`, `CRM/ERP Integration`, `Headless` | `composer require priyankjivani/module-order-comment-history-api:^1.0.0` |

---

## 📦 How to Install Any Extension via Composer VCS

In your Magento 2 root directory, register the GitHub VCS repository and require the package:

```bash
# Example: Installing the MCP Bridge
composer config repositories.priyankjivani-mcp-bridge vcs https://github.com/priyankjivani123/magento2-mcp-bridge.git
composer require priyankjivani/module-mcp-bridge:^1.0.0

# Enable and upgrade in Magento
bin/magento module:enable PriyankJivani_McpBridge
bin/magento setup:upgrade
bin/magento cache:flush
```

---

## 💼 Magento 2 Development Services Offered

* **Custom Module & Extension Development:** Clean, PSR-12 compliant, modular code engineered to never break core upgradeability.
* **AI & MCP Server Integration:** Connecting AI agents (Claude, Cursor, custom LLM pipelines) safely to Magento catalogs, inventory, and analytics.
* **Hyvä Theme Development:** Accelerating storefront performance and replacing legacy Luma bloat with lightweight Alpine.js and Tailwind CSS.
* **Performance Optimization & Core Web Vitals:** Slashing server TTFB, tuning Varnish/Redis, optimizing heavy SQL queries, and cleaning catalog index bottlenecks.
* **Third-Party & API Integrations:** Connecting stores to external ERPs, CRMs (Salesforce, Zendesk), custom payment gateways, shipping carriers, and PIMs.
* **Troubleshooting & Bug Fixes:** Resolving tricky checkout glitches, indexing deadlocks, cron queue stalls, and third-party extension conflicts.
* **Ongoing Store Maintenance & Upgrades:** Keeping your store secure, performing version upgrades (e.g. 2.4.5 ➔ 2.4.7+), and auditing third-party code.

---

## 📊 GitHub Activity & Statistics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=priyankjivani123&show_icons=true&theme=slate&hide_border=true&count_private=true" alt="Priyank's GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=priyankjivani123&layout=compact&theme=slate&hide_border=true" alt="Top Languages" height="165" />
</div>

---

## 🤝 Developing a Magento 2 Project? Let's Talk!

I help businesses build, customize, optimize, and maintain **Magento 2 / Adobe Commerce** stores.

**Available for:**
* Magento 2 Custom Development & Architecture
* Magento MCP & AI Integrations
* Custom Magento Extensions & Modules
* Bug Fixes, Audits, and Troubleshooting
* Performance Optimization & Core Web Vitals
* Hyvä Theme Development & Customization
* Headless GraphQL & REST API Integrations
* Ongoing Magento Store Maintenance

👉 **Hire me on Upwork:** [Priyank Jivani on Upwork](https://www.upwork.com/freelancers/priyankjivani)  
👉 **GitHub Profile:** [priyankjivani123](https://github.com/priyankjivani123)  
📧 **Direct Contact:** [priyankjivani48@gmail.com](mailto:priyankjivani48@gmail.com)

Contact me for freelance projects and long-term enterprise collaborations.
