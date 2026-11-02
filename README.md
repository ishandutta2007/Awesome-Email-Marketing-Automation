# Awesome-Email-Marketing-Automation

# Awesome-Email-Marketing-Automation
**Top Email Marketing Automation (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Campaign Automation, Visual Builders, Deliverability & Self-Hosted Marketing Platforms*
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Email Marketing Automation**. These tools enable marketers to build campaigns, automate sequences, segment audiences, and track engagement—from fully managed platforms with AI and deep CRM integration to self-hosted alternatives that give organizations complete control over their subscriber data and sending infrastructure.

**Examples** include HubSpot, Mailchimp, Klaviyo, ActiveCampaign, Brevo, ConvertKit, GetResponse, Omnisend, Campaign Monitor, and Constant Contact (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosted email marketing, automation, and open sending infrastructure. **Critical note**: The open-source landscape is genuinely viable—**Mautic** is the most complete marketing automation platform with no per-contact fees , **Listmonk** is the most performant newsletter engine running millions of emails on minimal resources , and **Keila** offers a clean Mailchimp alternative with a visual builder . No open-source project matches HubSpot's CRM integration or Klaviyo's e-commerce depth, but for core email marketing, the options are production-proven.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **HubSpot Email Marketing**
  **Email marketing within HubSpot CRM** with automation and personalization. **Pricing**: Free tier; Marketing Hub Starter from ~$15/month; Professional from ~$890/month. **Free tier**: Yes, limited. **Best for**: HubSpot users wanting email tied to CRM and workflows—**trade-off**: professional tier required for advanced automation.

- **Mailchimp**
  **Email marketing platform** with automation and audience management. **Pricing**: Free tier; paid from ~$13/month. **Free tier**: Yes, limited contacts and sends. **Best for**: SMBs wanting an established platform with broad integrations—**trade-off**: costs scale with contact count.

- **Klaviyo**
  **E-commerce email marketing** with deep Shopify integration. **Pricing**: Free tier up to 250 contacts; paid by contact count. **Free tier**: Yes, limited. **Best for**: e-commerce brands wanting revenue attribution and predictive analytics—**trade-off**: premium pricing for e-commerce features.

- **ActiveCampaign**
  **Email marketing and automation** with CRM and machine learning. **Pricing**: Starter from ~$15/month; Plus from ~$49/month. **Free tier**: Trial available. **Best for**: teams wanting advanced automation without enterprise pricing—**trade-off**: pricing scales with contacts.

- **Brevo (formerly Sendinblue)**
  **Email and SMS marketing** with CRM and transactional email. **Pricing**: Free tier with 300 emails/day; paid from ~$25/month. **Free tier**: Yes, 300 emails/day. **Best for**: SMBs wanting email, SMS, and CRM in one platform—**trade-off**: deliverability varies by plan tier.

- **ConvertKit**
  **Email marketing for creators** with automation and landing pages. **Pricing**: Free up to 1,000 subscribers; paid from ~$15/month. **Free tier**: Yes, limited. **Best for**: creators and newsletter writers wanting simplicity—**trade-off**: fewer e-commerce features than Klaviyo.

- **GetResponse**
  **Email marketing and automation** with webinar and landing page tools. **Pricing**: Free tier; paid from ~$15/month. **Free tier**: Yes, limited. **Best for**: SMBs wanting email plus webinar features—**trade-off**: automation depth varies by tier.

- **Omnisend**
  **E-commerce email and SMS marketing** with automation. **Pricing**: Free tier; paid from ~$16/month. **Free tier**: Yes, limited. **Best for**: e-commerce brands wanting SMS and email together—**trade-off**: Shopify-focused.

- **Campaign Monitor**
  **Email marketing** with drag-and-drop builder and automation. **Pricing**: Quote-only; tiered by subscribers. **Free tier**: Trial available. **Best for**: teams wanting a polished builder with strong templates.

- **Constant Contact**
  **Email marketing for SMBs** with automation and events. **Pricing**: Tiered by contacts; paid from ~$12/month. **Free tier**: Trial available. **Best for**: SMBs wanting email plus event management—**trade-off**: automation less advanced than ActiveCampaign.

## Open-Source GitHub Projects

- **Mautic**
  **Open-source marketing automation platform** (GPL-3.0) — **the most complete open-source alternative to HubSpot Marketing Hub and ActiveCampaign**, with no per-contact pricing from the project itself . **Features**: **Contacts and segments** with lead scoring; **newsletters and email campaigns**; **forms and landing pages**; **multi-step campaigns** triggered by contact behavior; **website visitor tracking**; **cron-driven automation**—segments rebuild every 15 minutes, campaigns fire on schedule . **Deployment**: Self-hosted (VPS, Docker) or Managed Mautic via Dropsolid (Essential from **€247.50/month** for 50K contacts/50K emails, Professional from **€1,237/month**) . **Trade-off**: **Technical operation required**—hosting, email delivery, maintenance, backups, and admin time are your responsibility; shared hosting is not recommended . **Best for**: technical teams wanting full marketing automation control without per-contact SaaS fees—especially those with existing infrastructure and email expertise.

- **Listmonk**
  **High-performance self-hosted newsletter and mailing list manager** (AGPLv3) — **the most performant open-source email engine**, running as a **single binary alongside PostgreSQL** . **Features**: **Manage millions of subscribers** across single and double opt-in lists; **SQL-based segmentation**; **built-in analytics** for campaign performance, bounces, and top links; **Go templating** with 100+ functions for dynamic content; **visual drag-and-drop builder**, WYSIWYG, Markdown, or raw HTML; **multi-threaded, multi-SMTP queues** with throughput and sliding-window rate limiting; **transactional API**; **Messenger webhooks** for SMS, WhatsApp, FCM; **OIDC SSO** with granular roles and API tokens; **S3-compatible media library** . **Performance**: A production instance sending **7+ million emails** used a fraction of a single CPU core with **peak RAM of 57 MB** . **Deploy**: Self-hosted (single binary, Docker) or third-party hosting. **Trade-off**: **No built-in visual automation builder**—campaigns are broadcast-oriented; automation requires external orchestration or the API. **Best for**: teams wanting maximum sending performance and control for newsletters and mailing lists—especially those with large lists and technical resources.

- **Keila**
  **Open-source newsletter and email marketing tool** (AGPLv3) — **the cleanest Mailchimp alternative** for self-hosted email marketing . **Features**: **Double opt-in subscriber management**; **drag-and-drop campaign editor** plus raw HTML mode; **hCaptcha and Friendly Captcha** on public forms; **automatic bounce, complaint, and unsubscribe handling**; **click and open tracking**; **per-sender SMTP configuration** (multiple senders per instance); **API access**; **segmentation by tag or custom field** . **Deployment**: Self-hosted (Docker with PostgreSQL; Oban background queue uses Postgres—no Redis dependency) or Railway one-click . **Trade-off**: **Simpler than Mautic**—no complex multi-step automation or CRM; newer project with smaller ecosystem. **Best for**: individuals, creators, and small teams wanting a clean, privacy-focused Mailchimp replacement without per-subscriber fees—especially those wanting a visual builder with minimal infrastructure.

- **SendDock**
  **Open-source email marketing platform** (Core: free; Pro: $9/month license) — **the most modern self-hosted email platform** with API-first design and multi-project support . **Features**: **Projects** for separate sending domains and subscriber lists; **subscribers** with CSV import, bulk actions, and status segmentation; **Handlebars templates** with visual editor (GrapesJS) and code editor; **campaigns** with scheduling and send-to-segment; **rich-text send**; **free analytics** (tabbed dashboard, weekday × hour click heatmap); **transactional API**; **deliverability essentials** (open pixel, click tracking with HMAC-signed redirects, RFC 8058 one-click unsubscribe, suppressions); **Pro tier adds** deliverability dashboard (SPF/DKIM/DMARC health) and report builder . **Tech stack**: Go, Vue 3, PostgreSQL, Redis. **Deploy**: Self-hosted (Docker, one curl command) or Cloud (free up to 2,000 subs; $19/mo for 10k) . **Trade-off**: **Newer project**—Pro features gated; no built-in automation sequences yet. **Best for**: developers and small teams wanting a modern, API-first email platform with BYO-SMTP—especially those wanting project-level separation for multiple brands.

- **NetSendo**
  **Self-hosted email marketing and automation platform** (open source) — **the most feature-complete self-hosted platform** with email, SMS, workflows, CRM, analytics, and AI integrations . **Features**: **Email and SMS campaigns**; **workflow automation**; **CRM**; **real-time analytics** with WebSocket support (Laravel Reverb); **AI integrations** (Anthropic Claude, Google Gemini); **multi-language** (English, Polish, German, Spanish); **Docker deployment** . **Tech stack**: Laravel, Vue.js, Docker. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: **Newer project** with limited community validation; WebSocket server required for real-time features. **Best for**: teams wanting a comprehensive self-hosted platform with email, SMS, and AI—willing to evaluate a newer but feature-rich option.

- **Helio**
  **Open-source, AI-native growth platform** (AGPL-3.0) — **the most AI-forward open-source marketing platform**, positioning itself as a HubSpot and Mautic alternative . **Features**: **Customer data platform (CDP)** unifying customer data; **audience segmentation**; **cross-channel journeys** on **Temporal** durable workflow engine; **email, SMS, push, WhatsApp** sending; **AI-native features**—natural-language segments and journeys, predictive scoring, brand-voice content generation, **MCP server** for AI agents; modern TypeScript and Python stack . **Deploy**: Self-hosted. **Trade-off**: **Early-stage project**—limited public validation; Temporal dependency adds operational complexity. **Best for**: teams wanting AI-native marketing automation with durable workflows—especially those already using Temporal or wanting MCP integration.

- **Notifuse**
  **Open-source email marketing and transactional email platform** (open source) — **the most modern Mailchimp/Brevo alternative** with visual MJML builder and multi-provider support . **Features**: **Visual drag-and-drop email builder (MJML)**; **campaign management** with A/B testing; **subscriber segmentation**; **multi-provider support** (Amazon SES, Mailgun, Postmark, SendGrid, SparkPost, Mailjet, SMTP); **transactional API** with automatic failover; **workspace isolation** with separate databases per workspace . **Tech stack**: Go, React, PostgreSQL. **Deploy**: Self-hosted (Railway one-click, Docker). **Trade-off**: **Newer project**—less community validation than Mautic or Listmonk; setup wizard required. **Best for**: teams wanting a modern email platform with visual builder and multi-provider failover—especially those wanting workspace-level isolation.

- **Camp**
  **Lightweight open-source email marketing platform** (MIT) — **the simplest self-hosted Mailchimp alternative**, built with Go's standard library for minimal dependencies . **Features**: **Campaign management**; **contact management** with import and segmentation; **analytics** (opens, clicks, engagement); **template system**; **self-hosted** with SQLite . **Tech stack**: Go, SQLite. **Deploy**: Self-hosted (`go mod download`; `make run`). **Trade-off**: **Minimal feature set**—automated sequences, A/B testing, and web UI dashboard are on the roadmap, not shipped . **Best for**: developers wanting a lightweight, dependency-minimal email platform for simple campaigns—not a full marketing automation suite.

### Additional Strong Open-Source Options

- **Postal** — Open-source mail delivery platform (open source). HTTP APIs, SMTP relay, click/open tracking, bounce handling, webhooks, multi-organization support . **Note**: **Mail delivery infrastructure**, not a marketing platform—pair with Mautic or Listmonk for campaign management. **Best for**: teams wanting to self-host their sending infrastructure instead of using SES or SendGrid.
- **OpenEMM** — Open-source email marketing software (AGPL). **Note**: Listed in broader searches but limited current validation surfaced. **Best for**: exploration only.

**Frameworks for building custom systems**: Combine **Mautic** for full marketing automation with **Listmonk** for high-performance newsletter sending and **Keila** for simple campaigns—creating a layered open-source email stack. **Postal** provides the sending infrastructure layer. **None of these match HubSpot's CRM integration or Klaviyo's e-commerce depth**, but for core email marketing, the open-source options are production-proven.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Email marketing platforms handling subscriber data must comply with data protection regulations (GDPR, CCPA, etc.) and anti-spam laws (CAN-SPAM). **Consent, unsubscribe mechanisms, and sender authentication (SPF/DKIM/DMARC) are non-negotiable.**
- **The "full marketing automation" vs. "newsletter engine" vs. "sending infrastructure" distinction is critical.** **Mautic** is **full marketing automation**—contacts, segments, campaigns, forms, landing pages, lead scoring . **Listmonk, Keila, SendDock, Notifuse, and Camp** are **newsletter/campaign engines**—they send broadcasts and manage lists, but lack full multi-step automation . **Postal** is **sending infrastructure**—it delivers mail but does not manage campaigns . **Choose based on whether you need automation, broadcasting, or delivery.**
- **Mautic is the most complete open-source marketing automation platform**—contacts, segments, campaigns, forms, landing pages, and lead scoring, with no per-contact fees . **The trade-off**: technical operation required; hosting, email delivery, and maintenance are your responsibility . Managed Mautic starts at **€247.50/month** for 50K contacts .
- **Listmonk is the performance champion**—7+ million emails sent using a fraction of a single CPU core and **57 MB peak RAM** . **The trade-off**: no built-in visual automation builder; campaigns are broadcast-oriented . **For high-volume newsletters, it is the most efficient open-source option.**
- **Keila is the cleanest Mailchimp replacement**—double opt-in, drag-and-drop editor, bounce handling, and per-sender SMTP, with a Railway one-click deploy . **The trade-off**: simpler than Mautic; no complex automation.
- **SendDock and Notifuse are the most modern self-hosted platforms** with API-first design and visual builders—SendDock at **$9/month Pro license** , Notifuse with multi-provider failover . **The trade-off**: newer projects with less validation.
- **Postal is not a marketing platform**—it is mail delivery infrastructure for teams wanting to self-host sending instead of using SES or SendGrid . **Pair it with Mautic or Listmonk for campaign management.**
- Self-hosted open-source solutions require proper infrastructure (PostgreSQL for most, Redis for SendDock), email authentication (SPF/DKIM/DMARC), IP warming, and ongoing maintenance. **Email deliverability is hard**—self-hosting shifts the entire burden to you. **Ensure your deployment meets anti-spam regulations and your organization's security standards before sending live campaigns.**

---

**Made for marketers, growth teams, and organizations building transparent email marketing solutions.**
Let's make Email Marketing Automation more open, data-driven, and subscriber-respectful.
