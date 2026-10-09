# Awesome Salesforce

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of GitHub repositories for the Salesforce ecosystem: Salesforce Platform, Apex, Lightning Web Components, Salesforce CLI, Data Cloud / Data 360, Agentforce, Marketing Cloud, Commerce Cloud, Mobile SDKs, APIs, and adjacent Salesforce-specific tooling.

## Scope and Tags

This list includes repositories whose primary purpose is Salesforce product development, Salesforce administration, Salesforce data movement, Salesforce-specific SDKs, native packages, sample apps, or learning projects. It intentionally excludes Salesforce-owned repositories that are general AI, infrastructure, security, web, or data-science projects unless the repo is directly about a Salesforce product or runtime.

Tags:

- `Archived` - The GitHub repository is archived or the maintainers mark it as superseded.
- `Stale` - The repository has no code push in more than five years from this review date.

Last researched: 2026-10-08.

## Contents

- [REG-Assets Team Repository Inventory](#reg-assets-team-repository-inventory)
- [Core CLI and Developer Tooling](#core-cli-and-developer-tooling)
- [Apex, LWC, UI, and Flow](#apex-lwc-ui-and-flow)
- [Apex Libraries, Patterns, and Testing](#apex-libraries-patterns-and-testing)
- [DevOps, Packaging, and Release Automation](#devops-packaging-and-release-automation)
- [Data Movement, Metadata, and Admin Productivity](#data-movement-metadata-and-admin-productivity)
- [Data Cloud, Data 360, and CRM Analytics](#data-cloud-data-360-and-crm-analytics)
- [Agentforce, Agent Script, and MCP](#agentforce-agent-script-and-mcp)
- [Marketing Cloud, Personalization, and SFMC](#marketing-cloud-personalization-and-sfmc)
- [Commerce Cloud, Industries, and Mobile](#commerce-cloud-industries-and-mobile)
- [Integration, API Clients, and Eventing](#integration-api-clients-and-eventing)
- [Sample Apps and Learning Projects](#sample-apps-and-learning-projects)
- [Salesforce.org, Nonprofit, and Education Packages](#salesforceorg-nonprofit-and-education-packages)
- [Legacy and Historical Salesforce Repositories](#legacy-and-historical-salesforce-repositories)
- [Curated Lists and Directories](#curated-lists-and-directories)
- [Research References](#research-references)

## REG-Assets Team Repository Inventory

The `reg-assets` team in the `sfdc-qbranch-emu` GitHub organization has access to the following repositories. Inventory last checked through the GitHub API on 2026-10-08.

- [adobe-ajo-sf-mce-nbo-poc](https://github.com/sfdc-qbranch-emu/adobe-ajo-sf-mce-nbo-poc) - Agentic-marketing proof of concept that resolves an external profile, retrieves a next best offer, and sends a Marketing Cloud email.
- [agent-fabric-inbound-lead](https://github.com/sfdc-qbranch-emu/agent-fabric-inbound-lead) - MuleSoft Agent Fabric demo that fans an inbound-lead request across Bedrock and Agentforce agents, creates a Salesforce Lead, and returns a combined result.
- [agentic-architecture-assessment](https://github.com/sfdc-qbranch-emu/agentic-architecture-assessment) - Skills, prompts, and an optional web app for assessing Salesforce org architecture and synthesizing improvement recommendations.
- [agentscript-identity-verification-example](https://github.com/sfdc-qbranch-emu/agentscript-identity-verification-example) - Agent Script service-agent example that gates conversations with reusable one-time-code identity verification.
- [attend-negotiation](https://github.com/sfdc-qbranch-emu/attend-negotiation) - Two-agent Slack negotiation demo that selects one meeting attendee or escalates a genuine tie to humans.
- [BD-PRISM](https://github.com/sfdc-qbranch-emu/BD-PRISM) - Mobile-framed MedTech sales assistant using Data Cloud and Agentforce for rep priorities, account intelligence, and briefings.
- [bedrock-sf-mcp](https://github.com/sfdc-qbranch-emu/bedrock-sf-mcp) - Harness for comparing model backends over Salesforce MCP and testing governance modes around live Agentforce sessions.
- [Branch-Banker-Demo](https://github.com/sfdc-qbranch-emu/Branch-Banker-Demo) - Native Financial Services Cloud demo of AI-assisted branch-banker workflows using the Salesforce Trust Layer and Claude.
- [broker-portal](https://github.com/sfdc-qbranch-emu/broker-portal) - Secure React portal for mortgage brokers to view assigned leads with server-side tenant and field-level access controls.
- [campaign-brief-workflow-package](https://github.com/sfdc-qbranch-emu/campaign-brief-workflow-package) - Slack-first campaign brief intake, Salesforce handoff automation, and interactive approval workflow package.
- [case-email-audit-poc](https://github.com/sfdc-qbranch-emu/case-email-audit-poc) - Prompt Builder and Flow proof of concept that audits inbound Case emails and records an AI verdict, confidence, and rationale.
- [copilot-studio-sf-mcp-agent](https://github.com/sfdc-qbranch-emu/copilot-studio-sf-mcp-agent) - CLI-built Microsoft Copilot Studio agent and reusable connector for read-only Salesforce hosted-MCP tools.
- [dc-campaign-performance-dmo](https://github.com/sfdc-qbranch-emu/dc-campaign-performance-dmo) - SFDX metadata and automation for creating and mapping a campaign-performance Data Cloud DMO through REST APIs.
- [df26-main-keynote-revenue-command-center](https://github.com/sfdc-qbranch-emu/df26-main-keynote-revenue-command-center) - Dreamforce 2026 Revenue Intelligence command center rendered in Claude Desktop over live Salesforce data, with pipeline, deal, and Slack workflows.
- [Digital_Origination_Lending_Demo_Assets](https://github.com/sfdc-qbranch-emu/Digital_Origination_Lending_Demo_Assets) - FSC digital loan-origination demo bundle with LWC, Apex, schema, financial analysis, and simulated document integrations.
- [email-attachment-file-analyzer](https://github.com/sfdc-qbranch-emu/email-attachment-file-analyzer) - Declarative Salesforce solution that analyzes email attachments with a multimodal GenAI prompt and shares the files with related records.
- [enablement-apprat](https://github.com/sfdc-qbranch-emu/enablement-apprat) - Prompt-driven application-rationalization workbook generator based on the PwC TIME framework; this asset is not Salesforce-specific.
- [fa-productivity-meeting-intelligence](https://github.com/sfdc-qbranch-emu/fa-productivity-meeting-intelligence) - Wealth advisor meeting-lifecycle toolkit with Agentforce Financial Services, briefing and wrap-up playbooks, and a realistic demo dataset.
- [Farmers-Agency-Angular-v2](https://github.com/sfdc-qbranch-emu/Farmers-Agency-Angular-v2) - Angular UI Bundle workspace for insurance producers with live Salesforce data, an embedded Agentforce assistant, and contextual Slack collaboration.
- [fins-acc-proactive-agent-demos](https://github.com/sfdc-qbranch-emu/fins-acc-proactive-agent-demos) - Three Financial Services Lightning components that launch proactive Agentforce experiences from opportunity, email, and portfolio signals.
- [fins-af-workshop](https://github.com/sfdc-qbranch-emu/fins-af-workshop) - Financial Services Agentforce workshop assets, agents, prompt templates, automations, sample data, and scratch-org bootstrap.
- [fins-farmers-agency-command-center](https://github.com/sfdc-qbranch-emu/fins-farmers-agency-command-center) - Multi-persona insurance agency command center with Lightning Web Components, Apex, persona apps, and an Agentforce employee assistant.
- [fins-farmers-service-activity-timeline](https://github.com/sfdc-qbranch-emu/fins-farmers-service-activity-timeline) - Salesforce service-work-item timeline with progress tracking and searchable activity across comments, email, files, chat, and messaging.
- [fins-gallagher-win-new-ux](https://github.com/sfdc-qbranch-emu/fins-gallagher-win-new-ux) - React UI Bundle for an insurance producer renewal workspace spanning book overview, renewal planning, and go-to-market strategy.
- [fins_hosted_MCP_workshop](https://github.com/sfdc-qbranch-emu/fins_hosted_MCP_workshop) - Hands-on Financial Services workshop for Salesforce Hosted MCP security, user-scoped identity, OAuth, and telemetry.
- [fins-mobile-meeting-wrapup](https://github.com/sfdc-qbranch-emu/fins-mobile-meeting-wrapup) - Mobile headless-Agentforce workflow that turns photographed handwritten notes into FSC interactions, summaries, opportunities, tasks, and an email draft.
- [fins-progressive-compass](https://github.com/sfdc-qbranch-emu/fins-progressive-compass) - Salesforce-native React insurance service workspace with a grounded Agentforce assistant, Knowledge guidance, and consultant-controlled record updates.
- [fsc_dynamic_insight_cards_826](https://github.com/sfdc-qbranch-emu/fsc_dynamic_insight_cards_826) - Four FSC Lightning insight cards for retail, wealth, business, and service use cases, with synthetic demo data.
- [gallagher-account-contact-opportunity-ux](https://github.com/sfdc-qbranch-emu/gallagher-account-contact-opportunity-ux) - React UI Bundle and Salesforce metadata for a modern insurance Account, Contact, and Opportunity experience with synthetic review data.
- [h360-react-app](https://github.com/sfdc-qbranch-emu/h360-react-app) - Headless Next.js CRM reference app supporting local MCP, hosted MCP, Agentforce, and Salesforce Models API paths.
- [headless-convo](https://github.com/sfdc-qbranch-emu/headless-convo) - Headless financial-services conversation starter with an AI advisor that uses Salesforce records through MCP tools.
- [headless-react-app-in-claude](https://github.com/sfdc-qbranch-emu/headless-react-app-in-claude) - React insurance-sales app rendered inside Claude Desktop over live Salesforce data through a local MCP Apps server.
- [HealthLifeSciencesObjectReference](https://github.com/sfdc-qbranch-emu/HealthLifeSciencesObjectReference) - Agent skills containing Health Cloud and Life Sciences Cloud object, field, and ERD reference material.
- [hls-condition-care-journeys](https://github.com/sfdc-qbranch-emu/hls-condition-care-journeys) - Health Cloud care-management metadata with Data Cloud activation and multichannel condition-care journeys.
- [hls-member-orchestration-salesforce](https://github.com/sfdc-qbranch-emu/hls-member-orchestration-salesforce) - Salesforce half of a tokenized payer member-orchestration reference build with Agentforce care-gap and next-best-action paths.
- [hls-member-orchestration-snowflake](https://github.com/sfdc-qbranch-emu/hls-member-orchestration-snowflake) - Snowflake data, governance, tokenization, and prioritization half of the payer member-orchestration reference build.
- [hls-network-adequacy-demo](https://github.com/sfdc-qbranch-emu/hls-network-adequacy-demo) - Medicare Advantage network-adequacy portal demonstrating Agentforce, Health Cloud, Data Cloud, and a headless 360 architecture.
- [hospitality-salesforce-backend](https://github.com/sfdc-qbranch-emu/hospitality-salesforce-backend) - Salesforce data, automation, Agentforce, and Data Cloud backend for a hospitality guest-experience demo.
- [hospitality-slack-concierge](https://github.com/sfdc-qbranch-emu/hospitality-slack-concierge) - Slack concierge demo that routes hotel tasks and writes completed work and preferences back to Salesforce.
- [hxl-widget-gallery](https://github.com/sfdc-qbranch-emu/hxl-widget-gallery) - Headless Experience Layer widget gallery for rendering Salesforce-backed cards across Slackbot, Claude, ChatGPT, and Agentforce.
- [in-person-meeting-assistant](https://github.com/sfdc-qbranch-emu/in-person-meeting-assistant) - Salesforce mobile meeting assistant that turns in-person transcripts into structured summaries and supports an Agentforce handoff.
- [Insurance-Agent-Demo](https://github.com/sfdc-qbranch-emu/Insurance-Agent-Demo) - Native FSC insurance-agent demo with AI priority coaching, policy and claims insights, and meeting briefings.
- [Julius-K---Mobile-Work-Queue](https://github.com/sfdc-qbranch-emu/Julius-K---Mobile-Work-Queue) - Indirect-lending demo package with a mobile work queue, dealer workflows, autonomous follow-up, and an Agentforce qualifier.
- [LAMBO](https://github.com/sfdc-qbranch-emu/LAMBO) - Compliance-first, load-aware orchestration for coordinating coding models, Agentforce, deterministic tools, and human approvals with evidence-honest telemetry.
- [marketing-cloud-engagement-custom-mcp](https://github.com/sfdc-qbranch-emu/marketing-cloud-engagement-custom-mcp) - HTTP MCP server exposing Marketing Cloud Engagement demo capabilities to MCP-compatible clients.
- [Medicaid-Redetermination-Concierge](https://github.com/sfdc-qbranch-emu/Medicaid-Redetermination-Concierge) - Health-plan demo combining Agentforce, SMS, Document AI, Experience Cloud, and rules-driven Medicaid work-hours redetermination.
- [Mock-FINS-Backend](https://github.com/sfdc-qbranch-emu/Mock-FINS-Backend) - Heroku-deployable financial-services demo backend with MCP and HTTP APIs, deterministic data, and optional Postgres integration.
- [mortgage-lead-scoring](https://github.com/sfdc-qbranch-emu/mortgage-lead-scoring) - Data Cloud and Agentforce demo for deterministic mortgage prospect scoring, ingestion, and lead routing.
- [poc-account-strategist-agent](https://github.com/sfdc-qbranch-emu/poc-account-strategist-agent) - Agentforce account-strategy proof of concept combining CRM activity, risks, Data Cloud revenue, and external news.
- [POC-Readiness-Checklist](https://github.com/sfdc-qbranch-emu/POC-Readiness-Checklist) - AI-evaluable readiness rubric for qualification, governance, environments, tooling, and go/no-go decisions before a proof of concept.
- [reg-agentforce-session-ontology-explorer](https://github.com/sfdc-qbranch-emu/reg-agentforce-session-ontology-explorer) - Salesforce-hosted React explorer for viewing Agentforce sessions as execution traces, ontology projections, evidence, and RDF.
- [REG-Assets](https://github.com/sfdc-qbranch-emu/REG-Assets) - Official catalog of vetted Financial Services and Healthcare & Life Sciences demos, accelerators, and reusable assets from Regulated Industries architects.
- [retail-loyalty-datacloud-with-journeys](https://github.com/sfdc-qbranch-emu/retail-loyalty-datacloud-with-journeys) - Retail loyalty data model, synthetic data, Data Cloud segments, and Marketing Cloud journey automation.
- [Salesforce-Architecture-View](https://github.com/sfdc-qbranch-emu/Salesforce-Architecture-View) - Interactive architecture briefing covering Salesforce data, agents, applications, integration, security, delivery, and product-specific system views.
- [sfdx-external-chat](https://github.com/sfdc-qbranch-emu/sfdx-external-chat) - Config-driven two-way chat between any Salesforce record and an external service using REST, Platform Events, and LWC.
- [sf-demo-react-ui](https://github.com/sfdc-qbranch-emu/sf-demo-react-ui) - React dashboard combining Salesforce AI, Agentforce, member, prior-authorization, and Data Cloud demo experiences.
- [sf-mcp-ai-chat-app](https://github.com/sfdc-qbranch-emu/sf-mcp-ai-chat-app) - React chat app that uses the Claude Agent SDK and Salesforce Hosted MCP Servers to ground natural-language org operations in live queries and APIs.
- [sfdc-to-mermaid-erd](https://github.com/sfdc-qbranch-emu/sfdc-to-mermaid-erd) - MCP server that converts Salesforce and Data Cloud metadata into Mermaid ER diagrams and Tableau semantic models.
- [slackbot-flexible-hierarchy-fsc](https://github.com/sfdc-qbranch-emu/slackbot-flexible-hierarchy-fsc) - Slackbot-driven Financial Services Cloud solution that creates flexible hierarchies from images and validates them with scheduled Apex.
- [synthetic-human-load-generator](https://github.com/sfdc-qbranch-emu/synthetic-human-load-generator) - Web and CLI load generator for creating realistic Agentforce conversations and populating Agentforce Observability.
- [unified-data-foundation-c360](https://github.com/sfdc-qbranch-emu/unified-data-foundation-c360) - FSC and Data Cloud banking foundation that unifies synthetic customer data and activates four real-time outreach signals.
- [WealthDemoAssets](https://github.com/sfdc-qbranch-emu/WealthDemoAssets) - FSC wealth-management reference skills, reusable household demo-data loader, and standalone Agentforce task-management agent.

## Core CLI and Developer Tooling

- [salesforcecli/cli](https://github.com/salesforcecli/cli) - The current `sf` command-line interface for Salesforce development, automation, and CI workflows.
- [salesforcecli/sf-plugins-core](https://github.com/salesforcecli/sf-plugins-core) - Shared libraries and conventions for building Salesforce CLI plugins.
- [salesforcecli/plugin-apex](https://github.com/salesforcecli/plugin-apex) - Salesforce CLI commands for Apex execution, tests, logs, and related Apex workflows.
- [salesforcecli/plugin-auth](https://github.com/salesforcecli/plugin-auth) - Salesforce CLI authentication commands for org login, JWT, device login, and auth management.
- [salesforcecli/plugin-data](https://github.com/salesforcecli/plugin-data) - Salesforce CLI data commands for SOQL, CRUD, tree import/export, and bulk operations.
- [salesforcecli/plugin-deploy-retrieve](https://github.com/salesforcecli/plugin-deploy-retrieve) - Salesforce CLI commands for metadata deployment, retrieval, validation, and quick deploys.
- [salesforcecli/plugin-org](https://github.com/salesforcecli/plugin-org) - Salesforce CLI commands for scratch orgs, sandboxes, snapshots, and org lifecycle work.
- [salesforcecli/plugin-packaging](https://github.com/salesforcecli/plugin-packaging) - Salesforce CLI package and package-version commands for first and second generation packaging.
- [salesforcecli/plugin-schema](https://github.com/salesforcecli/plugin-schema) - Salesforce CLI commands for describing and inspecting org schema.
- [salesforcecli/plugin-source](https://github.com/salesforcecli/plugin-source) - Salesforce CLI source commands for metadata conversion, tracking, pull, push, deploy, and retrieve.
- [salesforcecli/plugin-templates](https://github.com/salesforcecli/plugin-templates) - Template-backed generators for Salesforce projects and metadata.
- [salesforcecli/plugin-lightning-dev](https://github.com/salesforcecli/plugin-lightning-dev) - Local development tooling for Lightning Experience, Salesforce mobile, and Experience Cloud.
- [salesforcecli/plugin-lwc-test](https://github.com/salesforcecli/plugin-lwc-test) - Salesforce CLI tools for running Lightning Web Component unit tests.
- [salesforcecli/plugin-devops-center](https://github.com/salesforcecli/plugin-devops-center) - CLI access to Salesforce DevOps Center operations.
- [forcedotcom/salesforcedx-vscode](https://github.com/forcedotcom/salesforcedx-vscode) - Salesforce Extensions for Visual Studio Code.
- [forcedotcom/source-deploy-retrieve](https://github.com/forcedotcom/source-deploy-retrieve) - JavaScript toolkit for Salesforce metadata deploy and retrieve operations.
- [forcedotcom/sfdx-core](https://github.com/forcedotcom/sfdx-core) - Core Node.js library used by Salesforce CLI plugins and Salesforce DX tooling.
- [forcedotcom/salesforcedx-templates](https://github.com/forcedotcom/salesforcedx-templates) - Official Salesforce DX project and metadata templates.
- [forcedotcom/salesforcedx-docker](https://github.com/forcedotcom/salesforcedx-docker) - Official Docker image and Dockerfile support for Salesforce DX tooling.
- [forcedotcom/schemas](https://github.com/forcedotcom/schemas) - JSON schema definitions for Salesforce DX project files and related Salesforce metadata configuration.
- [forcedotcom/postman-salesforce-apis](https://github.com/forcedotcom/postman-salesforce-apis) - Official Postman collection for Salesforce APIs.
- [forcedotcom/code-analyzer](https://github.com/forcedotcom/code-analyzer) - Salesforce Code Analyzer for scanning Apex, LWC, and Salesforce project source.
- [forcedotcom/run-code-analyzer](https://github.com/forcedotcom/run-code-analyzer) - GitHub Action for running Salesforce Code Analyzer in CI.
- [rediga/Salesforce-Code-Review-Agent](https://github.com/rediga/Salesforce-Code-Review-Agent) - Cursor agent, skill, rules, and Bugbot configuration for reviewing Apex, LWC, Flow, security, tests, and governor-limit risks.
- [forcedotcom/sfdx-code-analyzer-vscode](https://github.com/forcedotcom/sfdx-code-analyzer-vscode) - VS Code extension surface for Salesforce Code Analyzer diagnostics.
- [forcedotcom/debug-log-analyzer](https://github.com/forcedotcom/debug-log-analyzer) - VS Code extension for analyzing Apex debug logs with flame charts, call trees, governor-limit tracking, and SOQL/DML insights.
- [forcedotcom/lightning-language-server](https://github.com/forcedotcom/lightning-language-server) - Aura and LWC language servers used by Salesforce developer tooling.
- [forcedotcom/apex-tmLanguage](https://github.com/forcedotcom/apex-tmLanguage) - TextMate grammar for Apex syntax highlighting.
- [forcedotcom/soql-language-server](https://github.com/forcedotcom/soql-language-server) - Language server support for SOQL editing experiences.
- [forcedotcom/soql-tooling](https://github.com/forcedotcom/soql-tooling) - SOQL language tooling, including language-server and query-builder capabilities.

## Apex, LWC, UI, and Flow

- [salesforce/lwc](https://github.com/salesforce/lwc) - The Lightning Web Components engine and framework.
- [salesforce-ux/design-system](https://github.com/salesforce-ux/design-system) - Salesforce Lightning Design System source and assets.
- [salesforce/design-system-react](https://github.com/salesforce/design-system-react) - React components that implement Salesforce Lightning Design System patterns.
- [salesforce/base-components-recipes](https://github.com/salesforce/base-components-recipes) - Examples of Salesforce base Lightning Web Components in practical app patterns.
- [salesforce/sfdx-lwc-jest](https://github.com/salesforce/sfdx-lwc-jest) - Jest test runner and utilities for LWC projects in Salesforce DX workspaces.
- [salesforce/eslint-plugin-lwc](https://github.com/salesforce/eslint-plugin-lwc) - Official ESLint rules for Lightning Web Components.
- [salesforce/eslint-config-lwc](https://github.com/salesforce/eslint-config-lwc) - Opinionated ESLint configurations for LWC projects.
- [salesforce/lwc-codemod](https://github.com/salesforce/lwc-codemod) - Codemods for automated Lightning Web Component migrations.
- [salesforce/near-membrane](https://github.com/salesforce/near-membrane) - JavaScript membrane library that powers Salesforce Lightning Locker-style isolation.
- [salesforce/observable-membrane](https://github.com/salesforce/observable-membrane) - Proxy-based observable membrane used in the LWC reactive programming model.
- [trailheadapps/lwc-recipes](https://github.com/trailheadapps/lwc-recipes) - Concise, production-minded Lightning Web Component examples for Salesforce Platform.
- [trailheadapps/lwc-recipes-oss](https://github.com/trailheadapps/lwc-recipes-oss) - LWC recipes for learning Lightning Web Components outside of an org runtime.
- [trailheadapps/apex-recipes](https://github.com/trailheadapps/apex-recipes) - Focused Apex examples covering common Salesforce server-side patterns.
- [trailheadapps/visualforce-to-lwc](https://github.com/trailheadapps/visualforce-to-lwc) - Migration examples for moving Visualforce patterns to Lightning Web Components.
- [trailheadapps/automation-components](https://github.com/trailheadapps/automation-components) - Reusable invocable actions, Flow screen components, and local actions.
- [UnofficialSF/LightningFlowComponents](https://github.com/UnofficialSF/LightningFlowComponents) - Community Flow extensions for Salesforce Flow and Orchestrator.
- [tsalb/lwc-utils](https://github.com/tsalb/lwc-utils) - Reusable Lightning Web Components for rich Screen Flow and data-dense Salesforce UI work.
- [pozil/sfdc-ui-lookup-lwc](https://github.com/pozil/sfdc-ui-lookup-lwc) - Reusable Salesforce lookup component built with Lightning Web Components.
- [deejay-hub/timeline-lwc](https://github.com/deejay-hub/timeline-lwc) - Timeline Lightning Web Component for visualizing Salesforce record events.
- [lwc-soql-builder/lwc-soql-builder](https://github.com/lwc-soql-builder/lwc-soql-builder) - SOQL execution and query-building tool implemented with LWC Open Source.
- [SalesforceLabs/LightningWebChartJS](https://github.com/SalesforceLabs/LightningWebChartJS) - Chart.js based Lightning Web Component for charts in Salesforce.
- [SalesforceLabs/ActivityTimelineLWC](https://github.com/SalesforceLabs/ActivityTimelineLWC) - Lightning Web Component implementation of the SLDS activity timeline.
- [SalesforceLabs/EnhancedLightningGrid](https://github.com/SalesforceLabs/EnhancedLightningGrid) - Sortable and filterable grid component for Lightning Experience.
- [SalesforceLabs/GanttChart](https://github.com/SalesforceLabs/GanttChart) - Sample Gantt chart component built with Lightning Web Components.
- [SalesforceLabs/FileExplorer](https://github.com/SalesforceLabs/FileExplorer) - Lightning file hierarchy explorer for files attached to Salesforce records.
- [SalesforceLabs/FlowEmailComposer](https://github.com/SalesforceLabs/FlowEmailComposer) - Flow-friendly email composer component with template and merge-field support.
- [SFDO-Community/Salesforce-Indicators](https://github.com/SFDO-Community/Salesforce-Indicators) - Indicator Lightning Web Component for Salesforce status and signal displays.
- [amitshq/salesforce-lwc-production-toolkit](https://github.com/amitshq/salesforce-lwc-production-toolkit) - Tested LWC and Apex toolkit for server-side datatables, modals, state handling, bulk operations, files, and reusable utilities.

## Apex Libraries, Patterns, and Testing

- [apex-enterprise-patterns/fflib-apex-common](https://github.com/apex-enterprise-patterns/fflib-apex-common) - Common Apex library for Apex Enterprise Patterns, selectors, domains, and services.
- [apex-enterprise-patterns/fflib-apex-mocks](https://github.com/apex-enterprise-patterns/fflib-apex-mocks) - Apex mocking framework for true Salesforce unit testing.
- [apex-enterprise-patterns/fflib-apex-common-samplecode](https://github.com/apex-enterprise-patterns/fflib-apex-common-samplecode) - Sample application that demonstrates Apex Enterprise Patterns in context.
- [apex-enterprise-patterns/force-di](https://github.com/apex-enterprise-patterns/force-di) - Dependency injection library for Apex, triggers, Visualforce, and Lightning.
- [salesforce/apex-mockery](https://github.com/salesforce/apex-mockery) - Lightweight native Apex mocking library.
- [kevinohara80/sfdc-trigger-framework](https://github.com/kevinohara80/sfdc-trigger-framework) - Minimal Apex trigger framework for Salesforce.
- [mitchspano/trigger-actions-framework](https://github.com/mitchspano/trigger-actions-framework) - Metadata-driven framework for partitioning, ordering, and bypassing Salesforce trigger logic.
- [jongpie/NebulaLogger](https://github.com/jongpie/NebulaLogger) - Native Salesforce observability and logging framework for Apex, Flow, LWC, OmniStudio, and integrations.
- [SFDO-Community/declarative-lookup-rollup-summaries](https://github.com/SFDO-Community/declarative-lookup-rollup-summaries) - Declarative Lookup Rollup Summaries package for no-code cross-object rollups.
- [jamessimone/apex-rollup](https://github.com/jamessimone/apex-rollup) - Configurable Apex rollup engine with invocable, trigger, and scheduled execution modes.
- [ipavlic/apex-fp](https://github.com/ipavlic/apex-fp) - Functional programming helpers for Apex.
- [PropicSignifi/Query.apex](https://github.com/PropicSignifi/Query.apex) - Dynamic SOQL and SOSL query builder for Salesforce Apex.
- [benahm/TestDataFactory](https://github.com/benahm/TestDataFactory) - Apex test data factory library for Salesforce tests.
- [Forceea/Forceea-data-factory](https://github.com/Forceea/Forceea-data-factory) - Native Salesforce data factory for generating structured Apex test data.
- [superfell/json2apex](https://github.com/superfell/json2apex) - Generator for strongly typed Apex classes from JSON structures.
- [certinia/apex-mdapi](https://github.com/certinia/apex-mdapi) - Apex wrapper for the Salesforce Metadata API.
- [cesarParra/apexdocs](https://github.com/cesarParra/apexdocs) - Documentation generator for Apex classes.
- [pkozuchowski/Apex-Opensource-Library](https://github.com/pkozuchowski/Apex-Opensource-Library) - Collection of reusable Salesforce Apex utilities.
- [dangmai/prettier-plugin-apex](https://github.com/dangmai/prettier-plugin-apex) - Prettier formatter plugin for Apex.
- [forcedotcom/force-dot-com-esapi](https://github.com/forcedotcom/force-dot-com-esapi) - Enterprise Security API library for Apex on Force.com.
- [SalesforceFoundation/ApexDoc](https://github.com/SalesforceFoundation/ApexDoc) - Apex documentation generator from Salesforce Foundation. `Archived`

## DevOps, Packaging, and Release Automation

- [SFDO-Tooling/CumulusCI](https://github.com/SFDO-Tooling/CumulusCI) - Portable automation framework for Salesforce projects and managed packages.
- [SFDO-Tooling/Snowfakery](https://github.com/SFDO-Tooling/Snowfakery) - Relational fake-data generator commonly used with Salesforce test and demo data.
- [SFDO-Tooling/Metecho](https://github.com/SFDO-Tooling/Metecho) - Web collaboration tool for Salesforce project contributions and review apps.
- [SFDO-Tooling/MetaCI](https://github.com/SFDO-Tooling/MetaCI) - Salesforce-specific CI app for repositories that use CumulusCI.
- [SFDO-Tooling/MetaDeploy](https://github.com/SFDO-Tooling/MetaDeploy) - Salesforce.org managed package installer and deployment orchestration app.
- [dxatscale/sfpowerkit](https://github.com/dxatscale/sfpowerkit) - Salesforce DX plugin for development, packaging, dependency, and org operations at scale.
- [hardisgroupcom/sfdx-hardis](https://github.com/hardisgroupcom/sfdx-hardis) - Opinionated Salesforce CLI toolbox for CI/CD, org monitoring, backups, and documentation.
- [hardisgroupcom/vscode-sfdx-hardis](https://github.com/hardisgroupcom/vscode-sfdx-hardis) - VS Code companion extension for the SFDX Hardis Salesforce toolbox.
- [hardisgroupcom/sfdx-hardis-training](https://github.com/hardisgroupcom/sfdx-hardis-training) - Free, lab-based Salesforce DevOps learning paths covering Git, scratch orgs, CI/CD, contributions, and release management.
- [ronny-schlidt/sf-cockpit](https://github.com/ronny-schlidt/sf-cockpit) - Terminal UI for Salesforce ISVs to investigate package push-upgrade failures, inspect subscribers, manage versions, deploy, and run tests.
- [muselab-d2x/d2x](https://github.com/muselab-d2x/d2x) - Development-to-delivery framework for repeatable Salesforce project delivery.
- [sfdx-isv/sfdx-falcon-template](https://github.com/sfdx-isv/sfdx-falcon-template) - Salesforce DX project template for complex ISV and managed-package projects.
- [dxatscale/dxatscale-template](https://github.com/dxatscale/dxatscale-template) - Starter template for Salesforce DX at Scale CI/CD pipelines.
- [github/octoforce-actions](https://github.com/github/octoforce-actions) - GitHub Actions template for Salesforce CI/CD.
- [forcedotcom/salesforcedx-actions](https://github.com/forcedotcom/salesforcedx-actions) - GitHub Actions helpers for Salesforce DX workflows.
- [forcedotcom/sfdx-jenkins-org](https://github.com/forcedotcom/sfdx-jenkins-org) - Jenkins example for Salesforce org development.
- [forcedotcom/sfdx-jenkins-package](https://github.com/forcedotcom/sfdx-jenkins-package) - Jenkins example for Salesforce package development.
- [forcedotcom/sfdx-gitlab-org](https://github.com/forcedotcom/sfdx-gitlab-org) - GitLab pipeline example for Salesforce org development.
- [forcedotcom/sfdx-gitlab-package](https://github.com/forcedotcom/sfdx-gitlab-package) - GitLab pipeline example for Salesforce package development.
- [forcedotcom/sfdx-bitbucket-org](https://github.com/forcedotcom/sfdx-bitbucket-org) - Bitbucket Pipelines example for Salesforce org development.
- [forcedotcom/sfdx-bitbucket-package](https://github.com/forcedotcom/sfdx-bitbucket-package) - Bitbucket Pipelines example for Salesforce package development.
- [forcedotcom/sfdx-circleci-org](https://github.com/forcedotcom/sfdx-circleci-org) - CircleCI example for Salesforce org development.
- [forcedotcom/sfdx-circleci-package](https://github.com/forcedotcom/sfdx-circleci-package) - CircleCI example for Salesforce package development.

## Data Movement, Metadata, and Admin Productivity

- [forcedotcom/dataloader](https://github.com/forcedotcom/dataloader) - Official Salesforce Data Loader source.
- [SalesforceLabs/LightningDataLoader](https://github.com/SalesforceLabs/LightningDataLoader) - Guided Lightning Web Component for CSV imports with reusable mappings, deduplication, batch progress, and error exports.
- [forcedotcom/SFDX-Data-Move-Utility](https://github.com/forcedotcom/SFDX-Data-Move-Utility) - Salesforce data migration tool for related records across orgs and CSV files.
- [forcedotcom/SFDX-Data-Move-Utility-Desktop-App](https://github.com/forcedotcom/SFDX-Data-Move-Utility-Desktop-App) - Desktop GUI for SFDMU Salesforce data migration projects.
- [forcedotcom/Data-Migration-Tool](https://github.com/forcedotcom/Data-Migration-Tool) - Salesforce metadata migration tooling for deploy and retrieve automation.
- [forceworkbench/forceworkbench](https://github.com/forceworkbench/forceworkbench) - Web-based tool suite for interacting with Salesforce APIs.
- [tprouvot/Salesforce-Inspector-reloaded](https://github.com/tprouvot/Salesforce-Inspector-reloaded) - Browser extension for Salesforce metadata, data export/import, and productivity overlays.
- [jetstreamapp/jetstream](https://github.com/jetstreamapp/jetstream) - Modern web app for Salesforce data, metadata, permissions, deployments, and org inspection.
- [SalesforceLabs/OrgCheck](https://github.com/SalesforceLabs/OrgCheck) - Salesforce app for org health, configuration, and technical-debt analysis.
- [forcedotcom/CustomMetadataLoader](https://github.com/forcedotcom/CustomMetadataLoader) - Tool for bulk creating and updating Salesforce Custom Metadata records from CSV.
- [pgonzaleznetwork/sfdc-soup](https://github.com/pgonzaleznetwork/sfdc-soup) - API and tooling for understanding Salesforce metadata dependencies.
- [superfell/SoqlX](https://github.com/superfell/SoqlX) - Desktop SOQL query and Salesforce object explorer.
- [rsoesemann/salesforce-plantuml](https://github.com/rsoesemann/salesforce-plantuml) - Salesforce app for generating UML and ER diagrams from org metadata.
- [stevebuik/Graphvizforce-Lightning](https://github.com/stevebuik/Graphvizforce-Lightning) - Salesforce ER diagram and SOQL generation tool using Graphviz.
- [forcedotcom/AuraEnabledScanner](https://github.com/forcedotcom/AuraEnabledScanner) - Scanner for Apex methods exposed through `@AuraEnabled`.
- [forcedotcom/dependencies-cli](https://github.com/forcedotcom/dependencies-cli) - Salesforce CLI plugin for metadata dependency tooling.
- [forcedotcom/user-access-visualization](https://github.com/forcedotcom/user-access-visualization) - Salesforce user access visualization tool.
- [vignaesh01/sfdx-package-generator](https://github.com/vignaesh01/sfdx-package-generator) - VS Code extension for generating Salesforce `package.xml` files.
- [nvuillam/sfdx-essentials](https://github.com/nvuillam/sfdx-essentials) - Salesforce DX toolbox with convenience commands layered on top of Salesforce CLI.
- [dineshkothuru/org-lens](https://github.com/dineshkothuru/org-lens) - Read-only Chrome extension for Salesforce schema, permissions, automation, dependencies, comparisons, and documentation exports.
- [vikascohen/Salesforce-ER-Modeller-Studio](https://github.com/vikascohen/Salesforce-ER-Modeller-Studio) - Salesforce-native ER modeling and architecture intelligence workspace with a data dictionary, dependency analysis, and field-change impact views.

## Data Cloud, Data 360, and CRM Analytics

- [forcedotcom/d360-mcp-server](https://github.com/forcedotcom/d360-mcp-server) - Official Salesforce Data 360 MCP server for AI-assisted Data 360 access.
- [forcedotcom/datacloud-mcp-query](https://github.com/forcedotcom/datacloud-mcp-query) - MCP query tooling for Salesforce Data Cloud / Data 360.
- [forcedotcom/datacloud-jdbc](https://github.com/forcedotcom/datacloud-jdbc) - JDBC driver for Salesforce Data Cloud / Data 360.
- [forcedotcom/Salesforce-CDP-jdbc](https://github.com/forcedotcom/Salesforce-CDP-jdbc) - JDBC driver for Salesforce CDP, the earlier Data Cloud naming lineage.
- [forcedotcom/salesforce-cdp-connector](https://github.com/forcedotcom/salesforce-cdp-connector) - Connector assets for Salesforce CDP / Data Cloud integrations.
- [forcedotcom/datacloud-customcode-python-sdk](https://github.com/forcedotcom/datacloud-customcode-python-sdk) - Python SDK for Salesforce Data Cloud custom code workflows.
- [salesforce/cdp-web-sdk](https://github.com/salesforce/cdp-web-sdk) - Web SDK for Salesforce CDP / Data Cloud event collection.
- [salesforce-marketingcloud/cdp-calculated-insights](https://github.com/salesforce-marketingcloud/cdp-calculated-insights) - Example SQL queries for Data Cloud calculated insights.
- [salesforce-marketingcloud/mobile-sdk-cdp-ios](https://github.com/salesforce-marketingcloud/mobile-sdk-cdp-ios) - iOS SDK pieces for sending mobile engagement data to Salesforce CDP / Data Cloud.
- [salesforce-marketingcloud/mobile-sdk-cdp-android](https://github.com/salesforce-marketingcloud/mobile-sdk-cdp-android) - Android SDK pieces for Salesforce CDP / Data Cloud mobile event collection.
- [SalesforceLabs/datacloud-error-handling-for-flow](https://github.com/SalesforceLabs/datacloud-error-handling-for-flow) - Flow-centered sample for handling Data Cloud errors in Salesforce automation.
- [trailheadapps/coral-cloud](https://github.com/trailheadapps/coral-cloud) - Sample app that showcases Data Cloud, Agentforce, and Prompt Builder together.
- [forcedotcom/e11y-df24-dc-three-things](https://github.com/forcedotcom/e11y-df24-dc-three-things) - Proof of concept for a second-generation managed package around Data Cloud.
- [salesforcecli/plugin-analytics](https://github.com/salesforcecli/plugin-analytics) - Salesforce CLI plugin for CRM Analytics applications, assets, and services.
- [forcedotcom/analyticsdx-vscode](https://github.com/forcedotcom/analyticsdx-vscode) - VS Code extension support for Salesforce Analytics development.
- [forcedotcom/Analytics-Cloud-Dataset-Utils](https://github.com/forcedotcom/Analytics-Cloud-Dataset-Utils) - Utilities for loading and managing CRM Analytics datasets.
- [forcedotcom/CRMA-dataset-creator](https://github.com/forcedotcom/CRMA-dataset-creator) - Lightweight client for creating CRM Analytics datasets through the External Data API.
- [forcedotcom/sfdx-analytics](https://github.com/forcedotcom/sfdx-analytics) - Einstein Analytics sample application templates.

## Agentforce, Agent Script, and MCP

- [salesforce/agentscript](https://github.com/salesforce/agentscript) - Schema-driven language for configuring agent orchestration systems.
- [trailheadapps/agent-script-recipes](https://github.com/trailheadapps/agent-script-recipes) - Short Agent Script examples for Agentforce-style agent orchestration.
- [salesforce/agent-sdk](https://github.com/salesforce/agent-sdk) - Python SDK for creating, managing, and running agents with Agentforce.
- [forcedotcom/sf-skills](https://github.com/forcedotcom/sf-skills) - Salesforce-curated agent skills for building Salesforce applications.
- [salesforce/salesforce-skills](https://github.com/salesforce/salesforce-skills) - Salesforce role-based Claude Cowork plugins for sales research, pipeline, forecasting, outreach, and governed CRM updates.
- [salesforce/agentforce-knowledge-readiness](https://github.com/salesforce/agentforce-knowledge-readiness) - Native Lightning accelerator that scores Knowledge articles for Agentforce readiness and proposes human-reviewed draft fixes.
- [salesforce/Resume_Parser](https://github.com/salesforce/Resume_Parser) - Agentforce in-chat résumé wizard that parses uploaded files, supports human review, and writes structured work experience to Salesforce records.
- [salesforcecli/plugin-agentforce-byoc](https://github.com/salesforcecli/plugin-agentforce-byoc) - Salesforce CLI plugin for packaging and deploying Python functions and registering them as Agentforce BYOC actions.
- [salesforcecli/mcp](https://github.com/salesforcecli/mcp) - MCP server for interacting with Salesforce instances.
- [salesforcecli/sf-grid-mcp](https://github.com/salesforcecli/sf-grid-mcp) - Beta MCP server that lets AI clients create and manage Agentforce Grid workbooks through the Grid Connect API.
- [forcedotcom/mcp-hosted](https://github.com/forcedotcom/mcp-hosted) - Official documentation, examples, issue tracker, and community hub for Salesforce Hosted MCP Servers.
- [forcedotcom/mobile-mcp-tools](https://github.com/forcedotcom/mobile-mcp-tools) - MCP servers and tools for Salesforce mobile use cases.
- [forcedotcom/AgentLens](https://github.com/forcedotcom/AgentLens) - Offline visual debugger for Agentforce traces with agent graphs, state-machine views, and a step-by-step execution inspector.
- [forcedotcom/lwc-agentscript-viewer](https://github.com/forcedotcom/lwc-agentscript-viewer) - Reference LWC for packaging, displaying, syntax-highlighting, and copying Agent Script templates for customers.
- [trevorscott/AgentPlatformTracingSlackbotInstructions](https://github.com/trevorscott/AgentPlatformTracingSlackbotInstructions) - Experimental Slackbot instructions and SOQL patterns for querying Agent Platform Tracing data in Data 360.
- [forcedotcom/vscode-agents](https://github.com/forcedotcom/vscode-agents) - VS Code extension for working with Salesforce agents.
- [forcedotcom/agents](https://github.com/forcedotcom/agents) - Salesforce agent metadata and tooling repository.
- [forcedotcom/Einstein-GPT-for-Developers](https://github.com/forcedotcom/Einstein-GPT-for-Developers) - Einstein GPT for Developers samples and support material.
- [forcedotcom/afdx-pro-code-testdrive](https://github.com/forcedotcom/afdx-pro-code-testdrive) - Agentforce DX pro-code test drive for a Coral Cloud Resort agentic app.
- [salesforce/help-agent-accelerator](https://github.com/salesforce/help-agent-accelerator) - Agentforce inline chat experience accelerator.
- [salesforce/AgentforceMobileSDK-iOS](https://github.com/salesforce/AgentforceMobileSDK-iOS) - iOS SDK for Agentforce mobile experiences.
- [salesforce/AgentforceMobileSDK-Android](https://github.com/salesforce/AgentforceMobileSDK-Android) - Android SDK for Agentforce mobile experiences.
- [salesforce/AgentforceMobileSDK-ReactNative](https://github.com/salesforce/AgentforceMobileSDK-ReactNative) - React Native SDK for Agentforce mobile experiences.
- [iamsonal/aiAgentStudio](https://github.com/iamsonal/aiAgentStudio) - Community framework for building AI agents natively in Salesforce.

## Marketing Cloud, Personalization, and SFMC

- [salesforce-marketingcloud/sfmc-postman](https://github.com/salesforce-marketingcloud/sfmc-postman) - Postman collections for Salesforce Marketing Cloud APIs.
- [salesforce-marketingcloud/sfmc-example-jb-custom-activity](https://github.com/salesforce-marketingcloud/sfmc-example-jb-custom-activity) - Journey Builder custom activity examples.
- [salesforce-marketingcloud/blocksdk](https://github.com/salesforce-marketingcloud/blocksdk) - Public SDK for Salesforce Marketing Cloud Content Builder blocks.
- [salesforce-marketingcloud/FuelSDK-Java](https://github.com/salesforce-marketingcloud/FuelSDK-Java) - Official Java SDK for Salesforce Marketing Cloud APIs.
- [salesforce-marketingcloud/FuelSDK-PHP](https://github.com/salesforce-marketingcloud/FuelSDK-PHP) - Official PHP SDK for Salesforce Marketing Cloud APIs.
- [salesforce-marketingcloud/FuelSDK-Python](https://github.com/salesforce-marketingcloud/FuelSDK-Python) - Official Python SDK for Salesforce Marketing Cloud APIs.
- [salesforce-marketingcloud/FuelSDK-Ruby](https://github.com/salesforce-marketingcloud/FuelSDK-Ruby) - Official Ruby SDK for Salesforce Marketing Cloud APIs.
- [salesforce-marketingcloud/FuelSDK-CSharp](https://github.com/salesforce-marketingcloud/FuelSDK-CSharp) - Official C# SDK for Salesforce Marketing Cloud APIs.
- [salesforce-marketingcloud/FuelSDK-Node-REST](https://github.com/salesforce-marketingcloud/FuelSDK-Node-REST) - Node REST client for Salesforce Marketing Cloud APIs.
- [salesforce-marketingcloud/FuelSDK-Node-SOAP](https://github.com/salesforce-marketingcloud/FuelSDK-Node-SOAP) - Node SOAP client for Salesforce Marketing Cloud APIs.
- [salesforce-marketingcloud/FuelSDK-Node](https://github.com/salesforce-marketingcloud/FuelSDK-Node) - Older Node SDK entry point for Salesforce Marketing Cloud.
- [salesforce-marketingcloud/MarketingCloudSDK-iOS](https://github.com/salesforce-marketingcloud/MarketingCloudSDK-iOS) - Official Marketing Cloud MobilePush SDK for iOS.
- [salesforce-marketingcloud/MarketingCloudSDK-Android](https://github.com/salesforce-marketingcloud/MarketingCloudSDK-Android) - Official Marketing Cloud MobilePush SDK for Android.
- [salesforce-marketingcloud/react-native-marketingcloudsdk](https://github.com/salesforce-marketingcloud/react-native-marketingcloudsdk) - Official React Native plugin for Marketing Cloud MobilePush.
- [salesforce-marketingcloud/react-native-unified-plugins](https://github.com/salesforce-marketingcloud/react-native-unified-plugins) - Modular React Native New Architecture plugins for Marketing Cloud identity, events, push, in-app messaging, and engagement.
- [salesforce-marketingcloud/MC-Cordova-Plugin](https://github.com/salesforce-marketingcloud/MC-Cordova-Plugin) - Official Cordova plugin for Marketing Cloud MobilePush.
- [salesforce-marketingcloud/sdk-flutter-plugin](https://github.com/salesforce-marketingcloud/sdk-flutter-plugin) - Official Flutter plugin for Marketing Cloud MobilePush.
- [salesforce-marketingcloud/flutter-unified-plugins](https://github.com/salesforce-marketingcloud/flutter-unified-plugins) - Modular Flutter plugins for Marketing Cloud identity, events, push, in-app messaging, and engagement.
- [salesforce-marketingcloud/Personalization-IOS](https://github.com/salesforce-marketingcloud/Personalization-IOS) - Official Salesforce Personalization SDK for iOS.
- [salesforce-marketingcloud/Personalization-Android](https://github.com/salesforce-marketingcloud/Personalization-Android) - Official Salesforce Personalization SDK for Android.
- [salesforce-marketingcloud/flutter-salesforce-personalization](https://github.com/salesforce-marketingcloud/flutter-salesforce-personalization) - Flutter plugin for rendering and tracking Salesforce Personalization content from the native mobile SDKs.
- [salesforce-marketingcloud/react-native-salesforce-personalization](https://github.com/salesforce-marketingcloud/react-native-salesforce-personalization) - React Native plugin for Salesforce Personalization content zones, recommendations, identity, consent, and events.
- [salesforce-marketingcloud/cocoapods-specs](https://github.com/salesforce-marketingcloud/cocoapods-specs) - Public CocoaPods specifications used to resolve and install Salesforce Marketing Cloud iOS SDK pods.
- [salesforce-marketingcloud/amp-demos](https://github.com/salesforce-marketingcloud/amp-demos) - AMPscript and Marketing Cloud demo assets.
- [salesforce-marketingcloud/SFDC-MC-REST-Style-Guide](https://github.com/salesforce-marketingcloud/SFDC-MC-REST-Style-Guide) - REST style guidance for Salesforce Marketing Cloud API work.
- [SalesforceLabs/ampscript-core](https://github.com/SalesforceLabs/ampscript-core) - Open-source implementation of Marketing Cloud AMPscript.
- [sfmcdg/Salesforce-Marketing-Cloud-Developer-Edition-Recipes](https://github.com/sfmcdg/Salesforce-Marketing-Cloud-Developer-Edition-Recipes) - Recipe-style examples for Salesforce Marketing Cloud Developer Edition.
- [Accenture/sfmc-devtools](https://github.com/Accenture/sfmc-devtools) - CLI and developer tooling for copying, deploying, and working offline with SFMC assets.
- [JoernBerkefeld/SFMC-Cookbook](https://github.com/JoernBerkefeld/SFMC-Cookbook) - Developer cookbook for Salesforce Marketing Cloud patterns.
- [Bizcuit/vscode-ampscript](https://github.com/Bizcuit/vscode-ampscript) - VS Code extension for AMPscript syntax, snippets, and Marketing Cloud connectivity.
- [email360/ssjs-lib](https://github.com/email360/ssjs-lib) - Server-side JavaScript utility library for Salesforce Marketing Cloud.
- [jdeblank/sfmc_dev](https://github.com/jdeblank/sfmc_dev) - Programmatic examples for SSJS, WSProxy, AMPscript, and SQL in SFMC.
- [basetime/bldr-sfmc](https://github.com/basetime/bldr-sfmc) - CLI development tool for Salesforce Marketing Cloud.
- [JoernBerkefeld/eslint-config-ssjs](https://github.com/JoernBerkefeld/eslint-config-ssjs) - ESLint preset for Salesforce Marketing Cloud server-side JavaScript.

## Commerce Cloud, Industries, and Mobile

- [SalesforceCommerceCloud/pwa-kit](https://github.com/SalesforceCommerceCloud/pwa-kit) - Progressive web app storefront framework for Salesforce B2C Commerce.
- [SalesforceCommerceCloud/b2c-developer-tooling](https://github.com/SalesforceCommerceCloud/b2c-developer-tooling) - B2C CLI, Agentforce Commerce B2C skills, MCP, and tooling SDKs.
- [SalesforceCommerceCloud/sfcc-ci](https://github.com/SalesforceCommerceCloud/sfcc-ci) - CLI for Salesforce B2C Commerce Cloud development and deployment.
- [SalesforceCommerceCloud/commerce-sdk](https://github.com/SalesforceCommerceCloud/commerce-sdk) - SDK assets for Salesforce Commerce APIs.
- [SalesforceCommerceCloud/commerce-sdk-isomorphic](https://github.com/SalesforceCommerceCloud/commerce-sdk-isomorphic) - Browser and Node.js JavaScript client for Salesforce B2C Commerce APIs.
- [SalesforceCommerceCloud/sfcc-sample-apps](https://github.com/SalesforceCommerceCloud/sfcc-sample-apps) - Sample applications for Salesforce Commerce Cloud.
- [SalesforceCommerceCloud/create-commerce-app](https://github.com/SalesforceCommerceCloud/create-commerce-app) - Scaffolding tool for Salesforce Commerce Cloud storefront apps.
- [SalesforceCommerceCloud/storefront-next-template](https://github.com/SalesforceCommerceCloud/storefront-next-template) - Next-generation Salesforce Commerce storefront template.
- [SalesforceCommerceCloud/storefront-next-luxury](https://github.com/SalesforceCommerceCloud/storefront-next-luxury) - Luxury-retail Storefront Next template built with React Router 7, React 19, and Salesforce B2C Commerce APIs.
- [SalesforceCommerceCloud/plugin_b2c_d360_personalization](https://github.com/SalesforceCommerceCloud/plugin_b2c_d360_personalization) - Experimental SFRA cartridge that hydrates Data 360 personalization decisions with live B2C Commerce price, promotion, availability, and image data.
- [SalesforceLabs/revenue-cloud-foundations](https://github.com/SalesforceLabs/revenue-cloud-foundations) - Revenue Cloud skills, documentation, implementation patterns, sample datasets, and automation for configuring and validating Salesforce environments.
- [trailheadapps/commerce-b2b-headless](https://github.com/trailheadapps/commerce-b2b-headless) - Beta reference React storefront for B2B Commerce built as a headless Multi-Framework UI Bundle.
- [SalesforceCommerceCloud/b2c-crm-sync](https://github.com/SalesforceCommerceCloud/b2c-crm-sync) - Reference integration between B2C Commerce and Salesforce Customer 360.
- [SalesforceLabs/Salesforce-CPQ-Advanced-Approvals-Slack-App](https://github.com/SalesforceLabs/Salesforce-CPQ-Advanced-Approvals-Slack-App) - Salesforce CPQ Advanced Approvals integration with Slack notifications, approval actions, and App Home views.
- [forcedotcom/b2b-commerce-on-lightning-quickstart](https://github.com/forcedotcom/b2b-commerce-on-lightning-quickstart) - Quickstart project for B2B Commerce on Lightning.
- [forcedotcom/b2b-commerce-open-source-components](https://github.com/forcedotcom/b2b-commerce-open-source-components) - Open-source components for B2B Commerce implementations.
- [forcedotcom/commerce-on-lightning-components](https://github.com/forcedotcom/commerce-on-lightning-components) - Reference source for Commerce on Lightning components.
- [forcedotcom/commerce-on-lightning](https://github.com/forcedotcom/commerce-on-lightning) - Salesforce CLI plugin for setting up B2B or B2C stores.
- [forcedotcom/commerce-extensibility](https://github.com/forcedotcom/commerce-extensibility) - Commerce extensibility examples and assets.
- [forcedotcom/comdagen](https://github.com/forcedotcom/comdagen) - Commerce data generator for Salesforce Commerce Cloud site imports.
- [forcedotcom/SalesforceMobileSDK-iOS](https://github.com/forcedotcom/SalesforceMobileSDK-iOS) - Official Salesforce Mobile SDK for iOS.
- [forcedotcom/SalesforceMobileSDK-Android](https://github.com/forcedotcom/SalesforceMobileSDK-Android) - Official Salesforce Mobile SDK for Android.
- [forcedotcom/SalesforceMobileSDK-ReactNative](https://github.com/forcedotcom/SalesforceMobileSDK-ReactNative) - React Native support for Salesforce Mobile SDK.
- [forcedotcom/SalesforceMobileSDK-CordovaPlugin](https://github.com/forcedotcom/SalesforceMobileSDK-CordovaPlugin) - Cordova plugin for Salesforce Mobile SDK.
- [forcedotcom/SalesforceMobileSDK-Samples](https://github.com/forcedotcom/SalesforceMobileSDK-Samples) - Sample apps for Salesforce Mobile SDK development.
- [forcedotcom/SalesforceMobileSDK-Templates](https://github.com/forcedotcom/SalesforceMobileSDK-Templates) - Templates for generating Salesforce Mobile SDK applications.
- [forcedotcom/LWC-Mobile-Samples](https://github.com/forcedotcom/LWC-Mobile-Samples) - Mobile sample applications and code for LWC development.
- [forcedotcom/mobile-ui-elements](https://github.com/forcedotcom/mobile-ui-elements) - Custom elements for Salesforce mobile applications.
- [salesforce/offline-app-developer-starter-kit](https://github.com/salesforce/offline-app-developer-starter-kit) - Starter kit for Salesforce offline app development.

## Integration, API Clients, and Eventing

- [jsforce/jsforce](https://github.com/jsforce/jsforce) - JavaScript library for Salesforce APIs in Node.js and browsers.
- [simple-salesforce/simple-salesforce](https://github.com/simple-salesforce/simple-salesforce) - Simple Python client for the Salesforce REST API.
- [restforce/restforce](https://github.com/restforce/restforce) - Ruby client for the Salesforce REST API.
- [django-salesforce/django-salesforce](https://github.com/django-salesforce/django-salesforce) - Salesforce integration for Django ORM using Salesforce REST APIs.
- [kevinohara80/nforce](https://github.com/kevinohara80/nforce) - Node.js REST API wrapper for Force.com and Salesforce APIs. `Archived`
- [forcedotcom/wsc](https://github.com/forcedotcom/wsc) - Web Service Connector libraries for Salesforce SOAP API integrations.
- [forcedotcom/pub-sub-api](https://github.com/forcedotcom/pub-sub-api) - Sample project for getting started with the Salesforce Pub/Sub API.
- [forcedotcom/EMP-Connector](https://github.com/forcedotcom/EMP-Connector) - Simplified CometD connector for Salesforce event streaming.
- [forcedotcom/WSDL2Apex](https://github.com/forcedotcom/WSDL2Apex) - Tooling for generating Apex from WSDL definitions.
- [forcedotcom/go-soql](https://github.com/forcedotcom/go-soql) - Go tag library for generating SOQL queries.
- [forcedotcom/SalesforcePy](https://github.com/forcedotcom/SalesforcePy) - Lightweight Python helper for Salesforce REST API calls.
- [forcedotcom/SalesforceCanvasFrameworkSDK](https://github.com/forcedotcom/SalesforceCanvasFrameworkSDK) - SDK for Force.com Canvas integrations.
- [forcedotcom/SalesforceCanvasJavascriptSDK](https://github.com/forcedotcom/SalesforceCanvasJavascriptSDK) - JavaScript SDK for Force.com Canvas apps.
- [forcedotcom/ConnectApiHelper](https://github.com/forcedotcom/ConnectApiHelper) - Apex helper for Chatter rich posts, mentions, inline images, and Connect API use.
- [forcedotcom/einstein-bot-sdk-java](https://github.com/forcedotcom/einstein-bot-sdk-java) - Java SDK for Salesforce Einstein Bot integrations.
- [SalesforceFoundation/salesforce-streaming-client](https://github.com/SalesforceFoundation/salesforce-streaming-client) - Python client for Salesforce Streaming API.
- [developerforce/Force.com-JavaScript-REST-Toolkit](https://github.com/developerforce/Force.com-JavaScript-REST-Toolkit) - Minimal JavaScript REST toolkit for Force.com apps. `Archived`
- [developerforce/Force.com-Toolkit-for-PHP](https://github.com/developerforce/Force.com-Toolkit-for-PHP) - PHP toolkit for Force.com and Salesforce APIs. `Archived`
- [superfell/Beatbox](https://github.com/superfell/Beatbox) - Python SOAP API client for Salesforce.

## Sample Apps and Learning Projects

- [trailheadapps/dreamhouse-lwc](https://github.com/trailheadapps/dreamhouse-lwc) - Real-estate sample app for Lightning Web Components on Salesforce Platform.
- [trailheadapps/ebikes-lwc](https://github.com/trailheadapps/ebikes-lwc) - Retail sample app for LWC and Experience Cloud.
- [trailheadapps/ecars](https://github.com/trailheadapps/ecars) - Electric car manufacturer sample app for Salesforce Platform runtime and compute capabilities.
- [trailheadapps/easy-spaces-lwc](https://github.com/trailheadapps/easy-spaces-lwc) - Event-management sample app for LWC on Salesforce Platform.
- [trailheadapps/az-insurance](https://github.com/trailheadapps/az-insurance) - Experience Cloud and Lightning Web Runtime sample for customer, partner, and marketing experiences.
- [trailheadapps/purealoe](https://github.com/trailheadapps/purealoe) - Agriculture and retail sample app for Salesforce Platform.
- [trailheadapps/dreaminvest-lwc](https://github.com/trailheadapps/dreaminvest-lwc) - Financial-services sample app built with Lightning Web Components.
- [trailheadapps/ready-to-fly](https://github.com/trailheadapps/ready-to-fly) - Sample app that demonstrates Salesforce and Slack integration.
- [trailheadapps/redwoods-insurance](https://github.com/trailheadapps/redwoods-insurance) - Insurance console and mobile sample app for claim handling.
- [trailheadapps/build-apps-with-lwc](https://github.com/trailheadapps/build-apps-with-lwc) - Ursus Park sample app for the Trailhead LWC project.
- [trailheadapps/dreamhouse-sfdx](https://github.com/trailheadapps/dreamhouse-sfdx) - Salesforce DX version of the Dreamhouse real-estate sample app.
- [trailheadapps/ebikes-manufacturing](https://github.com/trailheadapps/ebikes-manufacturing) - LWR site sample for E-Bikes manufacturing scenarios.
- [forcedotcom/quiz-host-app](https://github.com/forcedotcom/quiz-host-app) - Salesforce-built multiplayer quiz host app.
- [forcedotcom/quiz-player-app](https://github.com/forcedotcom/quiz-player-app) - Salesforce-built multiplayer quiz player app.
- [forcedotcom/RecordViewer](https://github.com/forcedotcom/RecordViewer) - UI API and Node.js sample app for viewing Salesforce records.
- [forcedotcom/RecordViewerNative](https://github.com/forcedotcom/RecordViewerNative) - UI API and React Native sample app for Salesforce records.
- [developerforce/troubleshoot-lwc](https://github.com/developerforce/troubleshoot-lwc) - Trailhead support repo for troubleshooting Lightning Web Components.

## Salesforce.org, Nonprofit, and Education Packages

- [SalesforceFoundation/NPSP](https://github.com/SalesforceFoundation/NPSP) - Source for the Salesforce.org Nonprofit Success Pack.
- [SalesforceFoundation/PMM](https://github.com/SalesforceFoundation/PMM) - Program Management Module for Salesforce nonprofit and social-sector programs.
- [SalesforceFoundation/OutboundFundsModule](https://github.com/SalesforceFoundation/OutboundFundsModule) - Open Source Commons package for managing grants, scholarships, and other outbound funds.
- [SalesforceFoundation/Volunteers-for-Salesforce](https://github.com/SalesforceFoundation/Volunteers-for-Salesforce) - Volunteers for Salesforce managed package.
- [SalesforceFoundation/EDA](https://github.com/SalesforceFoundation/EDA) - Education Data Architecture for Salesforce. `Archived`
- [SalesforceFoundation/Relationships](https://github.com/SalesforceFoundation/Relationships) - Nonprofit Success Pack Relationships package.
- [SalesforceFoundation/Households](https://github.com/SalesforceFoundation/Households) - Nonprofit Success Pack Households package.
- [SalesforceFoundation/Recurring_Donations](https://github.com/SalesforceFoundation/Recurring_Donations) - Recurring Donations package for the Nonprofit Success Pack.
- [SalesforceFoundation/Contacts_and_Organizations](https://github.com/SalesforceFoundation/Contacts_and_Organizations) - Contacts and Organizations package for the Nonprofit Success Pack.
- [SalesforceFoundation/Affiliations](https://github.com/SalesforceFoundation/Affiliations) - Affiliations package for the Nonprofit Success Pack.
- [SalesforceLabs/ActionPlansV4](https://github.com/SalesforceLabs/ActionPlansV4) - Action Plans package for reusable Salesforce task templates.
- [SalesforceLabs/ProjectManagementTool](https://github.com/SalesforceLabs/ProjectManagementTool) - Salesforce-native project management application.
- [SalesforceLabs/Milestones-PM](https://github.com/SalesforceLabs/Milestones-PM) - Lightweight Force.com project and task management app.
- [SalesforceLabs/AnimalShelterStarter](https://github.com/SalesforceLabs/AnimalShelterStarter) - Salesforce starter app for animal shelter operations.

## Legacy and Historical Salesforce Repositories

- [forcedotcom/aura](https://github.com/forcedotcom/aura) - Source for the Aura framework, now archived in favor of newer Lightning guidance. `Archived`
- [forcedotcom/idecore](https://github.com/forcedotcom/idecore) - Core plug-ins for the legacy Force.com IDE. `Archived`
- [developerforce/open-cti-demo-adapter](https://github.com/developerforce/open-cti-demo-adapter) - Legacy demo adapter for Salesforce Open CTI integrations. `Archived`
- [developerforce/LEXComponentsBundle](https://github.com/developerforce/LEXComponentsBundle) - Legacy Lightning Experience component bundle examples. `Archived`
- [developerforce/DataWeaveInApex](https://github.com/developerforce/DataWeaveInApex) - Examples for working with DataWeave scripts from Apex. `Archived`
- [SalesforceLabs/Salesforce-CRM-Dashboards](https://github.com/SalesforceLabs/Salesforce-CRM-Dashboards) - Historical Salesforce Labs CRM dashboard package. `Archived` `Stale`

## Curated Lists and Directories

- [svierk/awesome-lwc-collection](https://github.com/svierk/awesome-lwc-collection) - Curated collection of ready-to-use Lightning Web Components.
- [Confirm4Crit/awesome-lwc](https://github.com/Confirm4Crit/awesome-lwc) - Curated list of on-platform LWC resources and code examples.
- [mshanemc/awesome-sfdx-plugins](https://github.com/mshanemc/awesome-sfdx-plugins) - Curated directory of Salesforce DX and Salesforce CLI plugins.
- [sfmcdg/awesome-salesforce-marketingcloud](https://github.com/sfmcdg/awesome-salesforce-marketingcloud) - Salesforce Marketing Cloud resources maintained by the SFMC Developer Group.
- [ttntm/awesome-sfmc](https://github.com/ttntm/awesome-sfmc) - Curated Salesforce Marketing Cloud links, tools, and references.

## Research References

- [Salesforce CLI GitHub organization](https://github.com/salesforcecli) - Official Salesforce CLI and plugin repositories.
- [forcedotcom GitHub organization](https://github.com/forcedotcom) - Official Salesforce Platform, DX, Mobile SDK, Commerce, and Data Cloud repositories.
- [Trailhead sample apps](https://github.com/trailheadapps) - Official Salesforce sample applications and recipe repositories.
- [Salesforce Marketing Cloud GitHub organization](https://github.com/salesforce-marketingcloud) - Official Marketing Cloud SDKs, API examples, and MobilePush repositories.
- [Salesforce Commerce Cloud GitHub organization](https://github.com/SalesforceCommerceCloud) - Official B2C Commerce storefront, CLI, SDK, and sample app repositories.
- [Salesforce Developers Blog: Trailhead sample apps and recipes](https://developer.salesforce.com/blogs) - Used to cross-check official sample app and recipe positioning.
- [Salesforce Developers: Data 360 MCP server developer preview](https://developer.salesforce.com/blogs/2026/05/introducing-the-data-360-mcp-server-developer-preview) - Reference for the Data 360 MCP direction and official repository.
- [Salesforce Developers: Summer '26 developer guide](https://developer.salesforce.com/blogs/2026/06/the-salesforce-developers-guide-to-the-summer-26-release) - Cross-check for Hosted MCP Servers, Agent Script, Salesforce agent skills, and current developer tooling.
- [Salesforce Developers: Winter '27 developer guide](https://developer.salesforce.com/blogs/2026/10/developers-guide-to-the-winter-27-release) - Current cross-check for Agentforce, MCP, Agent Script, CLI, Web Console, and platform-development changes.
- [Salesforce Developers: Storefront Next](https://developer.salesforce.com/docs/commerce/sfnext/guide/sfnext-get-started.html) - Official architecture and development guidance for the current Storefront Next repositories and templates.
- [Salesforce Developers: Headless 360 MCP Server Beta](https://developer.salesforce.com/blogs/2026/07/announcing-the-headless-360-mcp-server-beta) - Reference for the current purpose of the hosted MCP repository and Headless 360 server.
- [Salesforce Developers: Migrate Legacy Agents to the New Agentforce Builder](https://developer.salesforce.com/blogs/2026/08/migrate-legacy-agents-to-the-new-agentforce-builder) - Current guidance for Agent Script migration, Agentforce DX, regression testing, and the new builder lifecycle.
- [Salesforce Developers: AgentLens](https://developer.salesforce.com/blogs/2026/05/agentlens-debug-agentforce-with-interactive-visualizations) - Official background for the Agentforce trace visualizer and its intended development-time use.
- [Salesforce Developers: Agent Platform Tracing](https://developer.salesforce.com/blogs/2026/05/agent-platform-tracing-debug-agentforce-with-trace-trees-soql-and-slack) - Official background for the tracing Slackbot instruction repository.
- [Salesforce Developers: Apex Recipes](https://developer.salesforce.com/blogs/2020/08/apex-recipes-a-new-resource-for-salesforce-developers) - Official background for the Apex Recipes repository.
- [Salesforce Developers: Lightning Web Components recipes](https://developer.salesforce.com/blogs/2019/03/lightning-web-components-recipes-patterns-and-best-practices) - Official background for LWC Recipes.
- [Salesforce Ben](https://www.salesforceben.com/) - Used as an ecosystem reference for community tooling coverage such as Salesforce Inspector Reloaded, Nebula Logger, and admin/developer productivity tools.
