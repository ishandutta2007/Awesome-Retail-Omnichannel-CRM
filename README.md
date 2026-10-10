# Awesome-Retail-Omnichannel-CRM

# Top Retail Omnichannel CRM Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Customer Data Unification, Omnichannel Engagement & Self-Hosted Retail Platforms*
**Last updated: October 2026**

This repository tracks notable **commercial retail omnichannel CRM platforms** and **open-source projects** that unify customer data, personalize engagement, and orchestrate commerce across online, in-store, and mobile channels.

**Examples** include Salesforce Retail Cloud, Shopify Plus, BigCommerce Enterprise, commercetools, Dynamic Yield, Bloomreach, SAP Commerce Cloud, Adobe Commerce, Kibo Commerce, and VTEX (the category leaders).

**Open-source emphasis**: Retail omnichannel CRM is a growing open-source domain. **Spree** leads as the most complete open-source commerce platform for DTC, B2B, marketplaces, and omnichannel — with REST APIs, TypeScript SDKs, a React admin dashboard, and production-ready Next.js storefront, all under BSD 3-Clause license . **EspoCRM** delivers a free, self-hosted CRM with contacts, deals, support cases, and email campaigns under AGPLv3 . **LEO CDP** provides an AI-first Customer Data Platform for unified customer profiles, real-time analytics, and predictive segmentation . **Tracardi** offers an API-first composable CDP engine as an open-source alternative to Segment and RudderStack . **Krayin** brings a Laravel-based CRM for complete customer lifecycle management . **Saleor** delivers a GraphQL-native headless commerce platform for omnichannel retail .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Retail Cloud](https://www.salesforce.com/)**
  **Salesforce's retail industry CRM** — unified customer profiles, order management, loyalty programs, and personalized engagement across channels. **Best for enterprise retailers**.

- **[Shopify Plus](https://www.shopify.com/plus)**
  **Enterprise e-commerce platform** — omnichannel selling, customer accounts, and marketing automation with extensive app ecosystem. **Best for high-growth DTC brands**.

- **[BigCommerce Enterprise](https://www.bigcommerce.com/)**
  **Open SaaS e-commerce platform** — headless commerce, B2B features, and omnichannel capabilities. **Best for mid-market and enterprise retailers**.

- **[commercetools](https://commercetools.com/)**
  **Composable commerce platform** — API-first, MACH architecture for omnichannel retail. **Best for enterprises wanting flexibility**.

- **[Dynamic Yield](https://www.dynamicyield.com/)**
  **Personalization and recommendation platform** — real-time optimization for e-commerce. **Best for enterprise personalization**.

- **[Bloomreach](https://www.bloomreach.com/)**
  **Commerce experience platform** — AI-powered product discovery, content, and personalization. **Best for retail personalization**.

- **[SAP Commerce Cloud](https://www.sap.com/)**
  **Enterprise commerce platform** — omnichannel retail with deep SAP ERP integration. **Best for SAP-centric retailers**.

- **[Adobe Commerce](https://business.adobe.com/products/magento/magento-commerce.html)**
  **Enterprise e-commerce platform** (formerly Magento) — B2B and B2C commerce with personalization. **Best for large retailers**.

- **[Kibo Commerce](https://kibocommerce.com/)**
  **Composable commerce platform** — order management, personalization, and subscription capabilities. **Best for omnichannel retailers**.

- **[VTEX](https://vtex.com/)**
  **Composable commerce platform** — marketplace, omnichannel, and B2B capabilities for global retailers. **Best for Latin American and global retailers**.

## Open-Source GitHub Projects

### Commerce & Omnichannel Platforms

- **[Spree](https://github.com/spree/spree)**
  **Open Source Platform for DTC, B2B Commerce, Marketplaces & Omnichannel**, BSD 3-Clause licensed with **16,000+ GitHub stars and 5,000+ forks** . **REST API with publishable keys, scoped secret keys, rate limiting, and OpenAPI 3.0 spec**. **Three TypeScript SDKs**: `@spree/sdk` (Store), `@spree/admin-sdk` (Admin), `@spree/seller-sdk` (Seller). **React Admin Dashboard** built on TanStack Router/Query, shadcn/ui, and Tailwind — extendable with plugins without forking. **Next.js Storefront** with multi-region URL routing, Stripe payments (Apple Pay, Google Pay, Klarna, Affirm), customer accounts, and SEO. **Channels** give each surface (web, mobile, POS, B2B panel, marketplace) its own catalog, pricing, payment methods, and order attribution. **Markets** bundle currency, language, payment methods, and shipping per region with EU Omnibus price history and customs duties built in. **Seller onboarding** with configurable requirements, commission engine, and payout ledger with Stripe Connect. **B2B & Wholesale** with price lists, volume tiers, customer groups, and tax exemptions. **Best for teams wanting a complete open-source commerce platform with omnichannel capabilities** .

- **[Saleor](https://github.com/saleor/saleor)**
  **High-performance, open-source headless e-commerce platform**, GraphQL-native API with **22,400+ GitHub stars** . **Composable & Extensible**: apps, 160+ webhooks, synchronous callbacks, dynamic models, and dashboard UI extensions. **Global & Omnichannel Ready**: native multi-channel, multi-warehouse, multi-currency, and multi-language support. **High Performance**: handles peaks of 1.7M requests in 24h; PWA-ready. **AI-Ready**: emerging integrations for conversational commerce (instant checkout in ChatGPT beta). **Enterprise Security**: SOC 2, GDPR, PCI-DSS compliant (Cloud); OpenTelemetry for distributed tracing. **Developer Tools**: Commerce as code with Configurator CLI, automated CI/CD, tech-agnostic (React, Next.js, Vue, Svelte). **Used by Lush, Breitling, and Rough Trade**. **Best for global brands and omnichannel retail** .

- **[Liberu Ecommerce](https://github.com/liberusoftware/ecommerce-laravel)**
  **Modular, production-ready e-commerce platform built on Laravel 13, PHP 8.5, Filament 5, and Livewire 4**, open-source . **Storefront & Cart**: reactive Livewire 4 shopping cart, multiple shipping methods with server-side rate calculation, guest and authenticated checkout. **Payments**: pluggable gateway factory with built-in Stripe (charges, webhooks, test mode) and PayPal integration. **Dropshipping**: first-class DropXL supplier integration with queued order placement. **Customer Segmentation** based on behaviour, LTV, and purchase history. **AI-Powered Product Recommendations** via collaborative filtering. **A/B Testing Framework** with variant assignment and conversion tracking. **Abandoned Cart Recovery** with email/SMS triggers and discount codes. **Gift Registry, Loyalty & Rewards Programme, B2B Wholesale Pricing, Multi-currency & Tax Management, and Refund & Return Management**. **Best for Laravel developers building custom e-commerce** .

- **[Medusa POS Starter](https://github.com/medusajs/medusa-pos-starter)**
  **Open-source point-of-sale application that connects directly to any Medusa backend**, MIT licensed . **In-Store Experience**: product discovery via search or barcode scanning (device camera), variant selection with live stock levels, cart management, customer profiles (attach existing or create new), and order creation syncing directly with Medusa Admin. **Store Operations**: staff authentication using Medusa Admin credentials, channel and region setup, setup wizard, order history with receipts, and device support via React Native and Expo (iOS and Android). **Developer Experience**: fully API-driven on Medusa's Admin API, composable for payments/printers/custom integrations, cross-platform. **Keeps every product, order, and customer record in sync across all channels**. **Best for retailers wanting to add in-store POS to an existing Medusa e-commerce backend** .

- **[Ready POS for WooCommerce](https://github.com/Johuniq/ready-pos)**
  **Point-of-sale interface plugin for WooCommerce**, GPL-2.0 licensed . **POS Terminal**: fullscreen checkout with product grid, cart, and payment. **Inventory Sync**: POS sales update WooCommerce stock in real time. **Multi-Outlet**: create outlets and registers for each location. **Register Sessions**: track opening cash, sales, and closing reconciliation. **Customer Management**: guest checkout and quick customer search. **Cash & Card Payments**, **Receipt Printing**, **Barcode Scanning** (keyboard-emulation), **Variable Products** with attribute picker, **Multi-Cart** (hold and switch between carts), **Order History**, **Refunds**, **Discounts & Tax**, and **Audit Logging**. All POS orders are WooCommerce orders — inventory updates in real time across online and in-store sales. **Best for WooCommerce stores wanting to add in-person sales** .

### Customer Relationship Management

- **[EspoCRM](https://github.com/espocrm/espocrm)**
  **Free, open-source CRM you host on your own server**, AGPLv3 licensed with **50,000+ companies worldwide** . **Track contacts, manage deals, handle support cases with a built-in customer portal, and run email campaigns**. **No per-user fees, no vendor lock-in, full control over data**. **Customize layouts, fields, workflows, and dashboards without writing code**. **Open architecture and REST API** for deeper changes. **Docker installation available** — runs EspoCRM, NGINX, and MySQL automatically. **System requirements**: PHP 8.3-8.5, MySQL 8.0+/MariaDB 10.3+/PostgreSQL 15.0+. **Best for organizations wanting a modern, self-hosted CRM with full customization** .

- **[Krayin CRM](https://github.com/krayin/laravel-crm)**
  **Free & open-source Laravel CRM solution for SMEs and Enterprises**, MIT licensed with **8,800+ GitHub stars** . **Complete customer lifecycle management**: CRM Dashboard with real-time record monitoring, lead and opportunity management (mark leads as won/lost with live updates), email interaction tracking, Access Control List (ACL) for role-based permissions, Activities Management (meetings, calls, notes), Kanban Visual Leads by stage, Unlimited Custom Fields, Product Creation, and Contact Management. **Modular design** for developer customization. **Best for Laravel developers and SMEs wanting a modern CRM foundation** .

- **[RealTimeX CRM](https://github.com/therealtimex/realtimex-crm)**
  **Full-featured CRM with zero cloud costs and complete privacy**, fork of Atomic CRM with "Bring Your Own Database" configuration . **Organize Contacts**, **Create Tasks & Set Reminders**, **Take Notes**, **Capture Emails** (CC to auto-save as notes), **Manage Deals** (Kanban pipeline), **Import & Export Data**, **Control Access** (Google, Azure, Keycloak, Auth0), **Track Activity History**, **Integrate via API**, **Customize Everything** (custom fields, themes, components), and **Bring Your Own Database** (Supabase connection via UI or environment variables). **Best for teams wanting a privacy-first CRM with zero cloud costs** .

### Customer Data Platforms (CDP)

- **[LEO CDP](https://github.com/trieu/leo-cdp-framework)**
  **Open Source AI-first Customer Data Platform framework**, Apache-2.0 licensed . **Omnichannel Data Collection & Unification**: collect from web, mobile, CRM, POS, e-commerce, customer service, social media, advertising, IoT, and APIs — unify into a single customer profile. **Real-Time Customer 360**: behavioral, transactional, demographic, and engagement data across all touchpoints. **AI-Based Segmentation & Customer Scoring**: RFM Analysis, CLV prediction, churn prediction, purchase propensity, lead scoring, and dynamic audience generation. **Behavioral Tracking & Journey Mapping**: capture interactions in real time, visualize customer journeys. **Predictive Analytics & Customer Insights**: ML and AI models for hidden patterns and actionable insights. **Real-Time Audience Activation**: trigger actions based on behavior, events, attributes, and predictive scores. **Event-Driven Data Processing** with Dagster integration. **Omnichannel Personalization with Agentic AI & LLMs**: AI-generated content, next-best-action recommendations, dynamic journey orchestration, and conversational AI assistants. **Enterprise Security & Governance**: consent management, RBAC, audit logs, on-premise/private cloud deployment, multi-tenant architecture, Docker/Kubernetes support, Prometheus/Grafana monitoring .

- **[Tracardi](https://github.com/Tracardi/tracardi-api)**
  **API-First Composable Open-source Customer Data Platform Engine**, MIT with Common Clause license . **Open-source alternative to Segment, RudderStack, etc.** **Collect Customer Data**: collect, ingest, aggregate, and store from multiple sources in real time. **Model Customer Data**: create rules to model data from your page into user profiles. **Personalize User Experience**: real-time frontend apps, customized messages, marketing segmentation, and in-time messaging. **Unify Profiles**: merge customer data from various sources into a single profile, automate duplicate elimination. **Integrate Internal Systems**: centralized communication and orchestration hub. **Scale E-Commerce Easily**: headless, API-first, decentralized system. **Social Engagement**: connect e-commerce to social media via Tracardi bridges. **Reuse Current Infrastructure**: runs on cloud-managed services. **Docker installation** with `docker-compose up`. **Best for developers building custom CDP infrastructure** .

- **[MessageBirds](https://pypi.org/project/messagebirds/)**
  **Open-source, event-driven Customer Data & Engagement Platform**, Apache-2.0 licensed . **Python client SDK** mirroring the JavaScript SDK in scope — covers the core send-an-event/read-a-profile loop. **EventEnvelope** structure for sending events. **find_profile_by_identity** for reading profiles by identity. **Typed API** in `messagebirds.types` for audiences, governance, channels, templates, and journeys. **Best for Python developers wanting a lightweight CDP foundation** .

### Point-of-Sale & Retail Operations

- **[DonatJS Kasir](https://github.com/donatjs/kasir)**
  **Zero-dependency, JSON-driven Point of Sale module for web applications**, MIT licensed . **Built on DonatJS Core** via a patch file registering a self-contained `kasir` component. **Product catalog management, reactive cart, multi-method payment processing** (Tunai, QRIS, Debit, Transfer), and **browser-native receipt printing** — no external dependency or build step. **Product catalog defined as plain JSON array** or fetched from REST API. **Payment behavior, tax, discount, and UI options configured from a single JSON object**. **Best for SME cashier counters and resource-constrained retail environments** .

- **[Uyuni for Retail](https://www.uyuni-project.org/)**
  **Open-source retail infrastructure management platform**, open-source . **Uyuni Server**: contains infrastructure, network topology, and automation for image deployment and day-to-day operations. **Branch Servers**: located near POS terminals, providing PXE boot, image cache, Salt broker, proxy for software components, and local networking (DHCP/DNS). **POS Terminals**: supports point-of-sale terminals, kiosks, digital scales, self-service systems, and reverse-vending systems with BIOS and UEFI boot. **Hardware Types** group devices by manufacturer and name. **Salt Formulas** simplify configuration with pre-written Salt states. **Saltboot** handles bootstrapping, deployment, and validation of terminals. **Prometheus + Grafana** for monitoring. **Best for retail organizations managing distributed POS infrastructure** .

### Additional Strong Open-Source Options

- **Budy E-commerce** — Simple E-commerce infrastructure providing a Shopify-like experience with configurable payments (Stripe, PayPal, Easypay), shipping, taxes, and discounts .
- **LiteCart** — Lightweight e-commerce platform with Stripe, PayPal, and SpectroCoin payment integrations, Docker/Kubernetes support .
- **Fat Free CRM** — Ruby on Rails CRM platform with 0.28.0 released April 2026 .
- **Twenty** — Modern open-source CRM with Notion-like interface and GraphQL API.
- **Odoo** — Open-source ERP with CRM, e-commerce, POS, and inventory modules.

**Frameworks for building custom retail omnichannel CRM solutions**: Combine **Spree** for a complete open-source commerce platform with channels for web, mobile, POS, and marketplaces . Use **EspoCRM** for the CRM layer with contacts, deals, and support cases . Deploy **LEO CDP** or **Tracardi** for unified customer data, AI-powered segmentation, and real-time personalization . Integrate **Medusa POS** or **Ready POS** for in-store point-of-sale synced with your e-commerce backend . Use **Krayin** for a Laravel-based CRM foundation . Note that true enterprise omnichannel CRM with AI-powered personalization, unified commerce orchestration, and vendor-supported SLAs (Salesforce Retail Cloud, Shopify Plus, Bloomreach) remains primarily commercial territory; open-source stacks provide strong commerce platforms, CRM foundations, and CDP engines that require integration for complete retail omnichannel operations .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Retail omnichannel CRM platforms handle sensitive customer data and must comply with data privacy regulations (GDPR, CCPA, PCI-DSS for payments). Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **Unified customer data is critical** — CDPs like LEO CDP and Tracardi unify customer profiles across channels, enabling real-time personalization and predictive analytics .
- **In-store and online sync must be seamless** — POS solutions like Medusa POS and Ready POS sync inventory and orders in real time across channels .
- **License considerations**: Spree uses BSD 3-Clause , EspoCRM uses AGPLv3 , LEO CDP uses Apache-2.0 , Tracardi uses MIT with Common Clause , Krayin uses MIT , and Medusa POS uses MIT . Verify licensing against your use case before committing.
- The open-source ecosystem provides strong commerce platforms, CRM foundations, and CDP engines, but **AI-powered personalization at scale, unified commerce orchestration, and vendor-supported SLAs** remain primarily commercial offerings .
