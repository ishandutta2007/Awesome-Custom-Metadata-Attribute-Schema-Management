# Awesome-Custom-Metadata-Attribute-Schema-Management

## Top Custom Metadata & Attribute Schema Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Custom Fields, Flexible Schemas & Low-Code Data Model Extension*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Custom Metadata & Attribute Schema Management**. These tools help organizations extend their core data models with custom fields, attributes, and metadata schemas—adapting CRM, CLM, ITSM, and database platforms to fit unique business processes without forking the underlying product.

**Examples** include Salesforce Object Manager, Ironclad Data Manager, Airtable Field Manager, SmartSuite Fields, ServiceNow Schema, and open-source alternatives like Twenty, OpenContracts, and Baserow (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted metadata schemas, open-source custom field systems, and community-driven schema registries—ideal for organizations seeking data sovereignty and transparent schema governance over per-object or per-seat SaaS limits.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global metadata management and extensible data modeling market is estimated at approximately **$14B to $15B** (expanding rapidly toward ~$60B+ by the early 2030s as enterprise data volumes surge). The sector exhibits a **moderately fragmented yet top-heavy dynamic**: while dominant cloud and CRM ecosystems (like Salesforce and ServiceNow) capture significant enterprise share through proprietary schema engines, the market remains contested and diverse across specialized CLM platforms, flexible workflow databases, and an accelerating wave of open-source schema managers catering to data sovereignty needs.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Starting Pricing | Free Tier / Trial Limits | Description |
|---------|-----------------------------------|------------------|--------------------------|-------------|
| **[Salesforce Object Manager](https://www.salesforce.com/)** | **~$205B Market Cap** (~$41.5B ARR) | Platform Starter: **$25/user/month** (billed annually); Platform Plus: **$100/user/month** | **30-day free trial** with full Platform Starter features; no free-for-ever tier | Central console for defining custom objects, fields, and relationships. Custom field metadata is stored as `*.field-meta.xml` files and deployable via SFDX. Provides Fields & Relationships, validation rules, and page layouts. |
| **[ServiceNow Schema](https://www.servicenow.com/)** | **~$110B Market Cap** (~$15.4B ARR) | ITSM Fulfiller: **~$70/user/month** (enterprise contracts baseline ~$20,000–$50,000/yr minimum) | **No production free tier or trial**; free non-production Personal Developer Instances (PDIs) available for developers (reclaimed after 10 days of inactivity) | Table schema and CMDB class management. CI Class Manager provides an interface for modifying table relationships and inheritance hierarchies. Schema Map displays related tables across instances. |
| **[Docusign CLM Attribute Builder](https://www.docusign.com/)** | **~$12B Market Cap** (~$3.36B ARR) | Enterprise contract: **~$3,000/month** (~$36,000/year minimum contract baseline) | **No free tier or trial for CLM** (eSignature 30-day trial excludes CLM metadata/attribute tools) | Attribute definition and management for contract metadata. Admins create attribute groups and fields, link dropdown attributes to multiselect fields in Document Generation forms, and control field properties. |
| **[Workato Data Tables](https://www.workato.com/)** | **$5.7B Valuation** (~$150M+ ARR) | Pay-as-you-go / Pro: **$75/month** (includes 2,500 credits/month) | **Free tier forever**: 50,000 one-time credits with standard data table support (10,000 char/field limit; not relational) | Spreadsheet-like data store for workflow apps with columns (table structure) and rows (data). Supports text, number, date, and link-to-table column types. |
| **[Ironclad Data Manager](https://www.ironcladapp.com/)** | **$3.2B Valuation** (~$200M ARR) | Enterprise contract: **~$2,500/month** (~$30,000/year minimum contract baseline) | **No free tier or public self-serve free trial**; evaluation sandboxes provided via sales demo only | Contract metadata management console for defining custom properties (previously fields, metadata, or attributes). Admins can create new properties, deprecate unused ones, and merge properties of the same data type. |
| **[Airtable Field Manager](https://www.airtable.com/)** | **$2.25B Valuation** (~$480M ARR) | Team plan: **$20/seat/month** (billed annually) or $24/seat/month (monthly) | **Free tier forever**: Up to 1,000 records/base, 1 GB attachment storage, max 5 editors | Field configuration for Airtable bases. Supports 20+ field types including text, number, date, single/multi-select, linked records, attachments, formulas, rollups, and lookups. Field Manager tracks dependencies. |
| **[Quickbase Fields](https://www.quickbase.com/)** | **~$1.0B Valuation** (~$200M+ ARR) | Launch plan: **$99/month** (3 users, 1 builder, 1 app) | **Free tier forever**: 1 app, 1 builder, 3 users, 100 credits/month | Field type configuration for Quickbase operational apps. Supports user fields, file attachments (100 MB max), URL fields, report link fields for table relationships, and formula fields. |
| **[Agiloft Field Studio](https://www.agiloft.com/)** | **~$300M+ Est. Value (KKR Majority)** (~$50M+ ARR) | Essentials plan: **~$500/month** (~$6,000/year baseline; median enterprise rollout ~$25,000+/year) | **Astra Free Tier forever**: Unlimited users with Astra Word add-in; full CLM platform has **no free tier** | No-code field and table configuration for Agiloft CLM. Admins define custom fields, data types, and relationships without development assistance. |
| **[SmartSuite Fields](https://www.smartsuite.com/)** | **~$150M Valuation** (~$10M+ ARR) | Team plan: **$15/seat/month** (billed annually, 3-user minimum: $45/month) | **14-day free trial**: Access to all Professional features without requiring a credit card | Field customization with granular options: help text, default values, field-level permissions, and protected system fields. Changing field types attempts automated value conversion. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Twenty](https://github.com/twentyhq/twenty)** | [![Stars](https://img.shields.io/github/stars/twentyhq/twenty?style=social&color=white)](https://github.com/twentyhq/twenty/stargazers) | **The most complete open-source CRM with custom objects and fields.** ~28,000 GitHub stars. Users can create custom objects (name, icon, description freely assigned) and add custom fields with multiple data types (text, number, date, selected value). Deactivating a field preserves data and API access—it simply disappears from the app UI while integrations continue to function. Self-hostable via Docker; AGPL-3.0 with some MIT packages [citation:18][citation:26]. |
| **[OpenContracts Metadata System](https://github.com/open-source-legal/opencontracts)** | [![Stars](https://img.shields.io/github/stars/open-source-legal/opencontracts?style=social&color=white)](https://github.com/open-source-legal/opencontracts/stargazers) | **Purpose-built contract metadata schema system.** Corpus-scoped metadata columns with 12 data types (STRING, TEXT, BOOLEAN, INTEGER, FLOAT, DATE, DATETIME, URL, EMAIL, CHOICE, MULTI_CHOICE, JSON). Includes validation configs (required, choices), GraphQL API, Excel-like grid editing, and full CRUD on schema. Adds/modifies columns at any time without data loss [citation:16]. |
| **[Baserow](https://github.com/baserow/baserow)** | [![Stars](https://img.shields.io/github/stars/baserow/baserow?style=social&color=white)](https://github.com/baserow/baserow/stargazers) | **Open-source Airtable alternative with extensible field types.** Self-hosted instances have unlimited rows on paid tiers; cloud free plan caps at 3,000 rows. Field types include text, long text, number, boolean, date, and more. **Plugin architecture allows creating custom field types**—the documentation includes a tutorial for building an IntegerField with custom validation logic [citation:5][citation:22][citation:30]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Stencil](https://github.com/goto/stencil)** | [![Stars](https://img.shields.io/github/stars/goto/stencil?style=social&color=white)](https://github.com/goto/stencil/stargazers) | Open-source schema registry for Protobuf, Avro, and JSON. Version history, backward compatibility enforcement on upload, and clients in Go, Java, and JS for dynamic schema deserialization. PostgreSQL-backed with Docker deployment. A **schema registry** rather than a custom-field UI, but directly applicable for managing attribute schemas across services [citation:3]. |
| **[NocoDB](https://github.com/nocodb/nocodb)** | [![Stars](https://img.shields.io/github/stars/nocodb/nocodb?style=social&color=white)](https://github.com/nocodb/nocodb/stargazers) | Turns any SQL database into a smart spreadsheet. Field types include Attachment, Checkbox, Rating, JSON, and Geometry in addition to standard types. Relational fields (LinkToAnotherRecord, Lookup, Rollup) mirror Airtable's linked-record model [citation:21][citation:29]. |
| **[Corteza](https://github.com/cortezaproject/corteza)** | [![Stars](https://img.shields.io/github/stars/cortezaproject/corteza?style=social&color=white)](https://github.com/cortezaproject/corteza/stargazers) | Open-source low-code platform with **unlimited app creation** and data harmonization. Transforms data into standardized JSON for custom data models. 100% free and open-source; export/import complete app configurations and record data without limits [citation:27]. |

**Frameworks for building custom systems**: Combine **Twenty** for CRM custom objects and fields with self-hosting, **OpenContracts** for contract-specific metadata schemas with 12 data types and GraphQL API, and **Baserow** for extensible no-code databases with custom field-type plugins—all deployable via Docker without per-object or per-record SaaS limits. For schema registry needs across microservices, **Stencil** provides versioned Protobuf/Avro/JSON management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Custom metadata and attribute schemas govern how business data is structured and queried; enforce validation rules, data type constraints, and audit trails to prevent schema drift and data corruption.
- **Custom field limits and feature availability vary dramatically.** Salesforce caps Platform Starter at **10 custom objects**; Airtable's Field Manager (dependency tracking before deletion) is **paid-tier only** [citation:9]; Workato Data Tables are explicitly **not relational databases** and have a 10,000-character limit on long text [citation:14]. Open-source alternatives like **Twenty** and **OpenContracts** provide genuine custom schema capabilities but require self-hosting effort. Always validate schema design against your actual query patterns and data volume before committing.

---

**Made for CRM administrators, data architects, CLM configurators, and developers building extensible data platforms.**  
Let's make custom metadata and schema management more open, flexible, and governable.
