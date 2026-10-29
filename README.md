# Awesome-Carbon-Offset-Management

# Awesome-Carbon-Offset-Management
**Top Carbon Offset Management (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Carbon Credit Procurement, Project MRV, Offset Portfolios & Climate Action Platforms*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Carbon Offset Management**. These tools enable organizations to purchase carbon credits, manage offset portfolios, verify project integrity, and integrate climate action into their operations—from fully managed offset providers with vetted project networks to self-hosted registries and estimation tools that give organizations control over carbon accounting and credit issuance.

**Examples** include Shopify Planet, Pachama, Patch, Wren, Climeworks, South Pole, CarbonClick, Ecologi, Cloverly, and Tradewater (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, carbon credit registries, and open climate infrastructure. **Critical note**: True open-source carbon offset management—a turnkey platform for purchasing and retiring verified credits—is extremely sparse. Most projects address **registry infrastructure**, **estimation tools**, or **carbon accounting**, not the full offset procurement workflow that Patch or CarbonClick provide.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Shopify Planet](https://www.shopify.com/)**
  **Carbon removal app for Shopify merchants** enabling carbon-neutral shipping and customer-facing climate action. Merchants pay $0.035–$0.15 per order or let customers contribute $0.25 at checkout; funds purchase carbon removal credits from Shopify-verified providers including Grassroots Carbon, Running Tide, Remora, Heirloom, Planetary, and Charm . **Pricing**: Included with Shopify; per-order or customer-paid models. **Free tier**: None beyond Shopify subscription. **Best for**: Shopify merchants wanting to fund durable carbon removal without managing credit procurement independently.

- **[Pachama](https://pachama.com/)** (Carbon Direct)
  **Forest carbon project monitoring, reporting, and verification (MRV)** platform using satellite data and AI. Acquired by Carbon Direct in 2025; technology now integrated into Carbon Direct's carbon management suite . **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting data-driven verification of nature-based carbon projects before purchasing credits.

- **[Patch](https://patch.io/)**
  **Carbon credit marketplace and API** with the broadest selection of vetted credits, accessible via direct purchase, multi-year offtake, or digital transactions. The Patch API enables order-based emissions estimates, user-driven project selection, and fractional contributions within any application . **Pricing**: Usage-based API; credit prices vary by project and volume. **Free tier**: None. **Best for**: developers and platforms wanting to embed carbon credit purchasing directly into user journeys.

- **[Wren](https://www.wren.co/)**
  **Consumer-facing climate subscription** for calculating and offsetting personal carbon footprints monthly. Funds projects including Amazon rainforest protection and basalt rock carbon storage. Publicly shares transaction ledgers and receipts for transparency . **Pricing**: Monthly subscription; varies by footprint. **Free tier**: First month free for new members. **Best for**: individuals wanting a transparent, subscription-based offsetting service—not enterprise procurement.

- **[Climeworks](https://climeworks.com/)**
  **Direct air capture (DAC) carbon removal** provider with enterprise carbon removal portfolios. Partnered with SAP to secure 37,000 tons of removal credits through 2034 across DAC, biochar, and enhanced rock weathering . **Pricing**: Quote-only; premium pricing for durable removal. **Free tier**: None. **Best for**: enterprises seeking high-durability, engineered carbon removal for residual emissions.

- **[South Pole](https://www.southpole.com/)**
  **Climate consulting and carbon credit procurement** with 500+ experts across 20+ countries. Offers project development, CORSIA-compliant units, and advisory across CSRD, SBTi, and Scope 3 . **Pricing**: Quote-only; advisory and credit fees vary. **Free tier**: None. **Best for**: enterprises needing end-to-end climate strategy including credit sourcing and compliance advisory.

- **[CarbonClick](https://www.carbonclick.com/)**
  **Business carbon offsetting platform** with purchasable and traceable credits. **Free** plan for browsing projects; **Starter** at $99/license/month; **Advanced** at $399/month adds emissions calculation, toolkit, and eCommerce plugins; **Enterprise** custom with unlimited programmes and API access . **Free tier**: Yes, for project browsing only; no credit purchases. **Best for**: SMBs and eCommerce businesses wanting structured offsetting with impact reporting and plug-ins.

- **[Ecologi](https://ecologi.com/)**
  **Climate action subscription** funding tree planting and certified carbon avoidance projects. Personal plans from £4.70/month (2 trees + 2.64t CO₂ avoided annually) to £18.80/month. Publishes carbon credit certificates and tree-planting records via a Public Impact Ledger . **Pricing**: Tiered subscriptions; business plans available. **Free tier**: None. **Best for**: individuals and small businesses wanting simple, transparent climate contributions—**not enterprise offset procurement**.

- **[Cloverly](https://cloverly.com/)**
  **Carbon credit API** for calculating emissions and purchasing offsets programmatically. Microsoft Lists connector supports transaction-based estimates and offset purchases with project details, registry links, and receipt URLs returned in responses . **Pricing**: Usage-based API; credit costs pass-through. **Free tier**: None. **Best for**: developers wanting to embed carbon offsetting into applications via API.

- **[Tradewater](https://tradewater.co/)**
  **Carbon offset credits from refrigerant and methane destruction** projects. B Corp focused on non-CO₂ super pollutants; projects verified under ICVCM Core Carbon Principles. Credits fund collection and destruction of halocarbons and orphaned oil/gas well methane . **Pricing**: Quote-only. **Free tier**: None. **Best for**: buyers prioritizing high-integrity avoidance credits with immediate climate impact.

## Open-Source GitHub Projects

- **[National Carbon Credit Registry](https://github.com/undp/national-carbon-credit-registry)**
  **Open-source toolkit for national carbon credit registries** (AGPL-3.0) — **the most significant open-source project for carbon credit infrastructure**, backed by the United Nations Development Programme. **Features**: Issue, monitor, and trade carbon credits with data integrity; API, web, and data portal components; designed for government deployment. Deployed or deploying in **Namibia, Ghana, Côte d'Ivoire, Costa Rica, and Sri Lanka**; integrating with World Bank software . **Tech stack**: Per UNDP DPG submission. **Deploy**: Self-hosted government infrastructure. **Trade-off**: **National registry infrastructure, not a corporate offset procurement platform**—it is for sovereign carbon credit accounting under Article 6 and national climate commitments, not for businesses buying offsets. **Best for**: governments and public sector entities implementing national carbon credit systems.

- **[CarbonCreditBuy](https://zenodo.org/records/13876575)**
  **Open, self-hostable geospatial platform for estimating tree-based carbon removal** (license per Zenodo record) — **an explainable estimation tool, not a credit issuance or offset procurement system**. **Features**: Land marking via map (boundary, freehand, rectangle, circle, coordinates, GeoJSON/KML/CSV/LAS/LAZ import); deterministic engines combining ESA WorldCover and Copernicus Sentinel-2 data with IPCC 2006 Tier 1 (Tier 2 with measured diameter) gain-loss estimates; low-central-high ranges with confidence grades and provenance; policy engine screening for India, US, and EU; nine deterministic agents for explanations with an optional LLM for rephrasing only . **Tech stack**: Geospatial (per documentation). **Deploy**: Self-hostable. **Trade-off**: **Scenario estimation only**—outputs are explicitly **not certified carbon credits** (`certified: false`). Demo uses synthetic data; field measurement agreement not yet evaluated. **Best for**: farmers, landowners, and researchers wanting to estimate potential tree-based carbon before pursuing certification.

- **[calcium](https://codeberg.org/unkaktus/calcium)**
  **Command wrapper for tracking computing carbon footprint** (license per Codeberg repo) — **a narrow, developer-focused tool for software emissions estimation**. **Features**: Wraps any command with a project tag; logs CPU time to CSV; generates JSON reports by region using ISO 3-letter country codes; carbon intensity data from Ember, Energy Institute, and Our World in Data; TDP lookup for CPU models . **Tech stack**: Go. **Deploy**: CLI binary or `go install`. **Trade-off**: **Estimates software operational footprint**—does not purchase, retire, or manage offsets. No registry integration. **Best for**: developers wanting to measure the carbon footprint of compute workloads for reporting or optimization.

- **[SCOOP Carbon Accounting](https://github.com/scoop-carbon/scoop)**
  **Open-source carbon accounting with metrology rigor** (license per repo) — **an IEEE-affiliated project** supporting standards P7802 and P3469. **Features**: Applies metrology discipline with financial reporting frameworks to carbon accounting; translating scientific principles into practical projects . **Tech stack**: Per repository. **Deploy**: Self-hosted. **Trade-off**: **Carbon accounting infrastructure**, not offset procurement—focused on measurement and reporting, not credit purchasing or retirement. **Best for**: organizations wanting rigorous, standards-aligned carbon accounting.

- **[Open Offset / Carbon Offset Tools](https://github.com/search?q=carbon+offset+open+source)**
  **Note**: A comprehensive search of GitHub for actively maintained open-source carbon offset **management** platforms (with credit purchasing, retirement, and registry integration) yielded **no mature projects**. The projects listed above are the closest matches: registry infrastructure (National Carbon Credit Registry), estimation (CarbonCreditBuy, calcium), and accounting (SCOOP). **Organizations needing to purchase and retire credits will require commercial platforms like Patch or CarbonClick.**

### Additional Strong Open-Source Options

- **OpenLCA** — Open-source life cycle assessment software (MPL-2.0). Calculates environmental footprints including carbon; not an offset management tool. **Best for**: organizations needing LCA for emissions measurement before offsetting.
- **Carbon Footprint Calculator (various)** — Multiple open-source calculators exist on GitHub (typically MIT or GPL). **Note**: Individual/event emissions estimation only; no offset purchasing or retirement . **Best for**: educational or personal use.

**Frameworks for building custom systems**: Combine **National Carbon Credit Registry** for sovereign credit issuance infrastructure (if applicable) with **CarbonCreditBuy** for project-level estimation, **SCOOP** for accounting rigor, and **calcium** for software emissions tracking—creating a carbon measurement and infrastructure stack. **None of these provide credit purchasing or retirement**—that layer requires commercial integration or building against registry APIs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Carbon offset platforms and projects must align with recognized standards (Gold Standard, Verra/VCS, ICVCM Core Carbon Principles, CORSIA) and avoid greenwashing claims. Carbon credits are not a substitute for emissions reduction.
- **The "offset procurement" vs. "registry infrastructure" vs. "estimation/accounting" distinction is critical.** **Shopify Planet, Patch, CarbonClick, Climeworks, South Pole, Tradewater, and Cloverly** are **offset procurement platforms**—they sell or facilitate purchase of verified credits. **National Carbon Credit Registry** is **registry infrastructure**—it issues and tracks credits for governments. **CarbonCreditBuy, calcium, and SCOOP** are **estimation and accounting tools**—they measure emissions or potential removal but do not sell credits. **No open-source project provides turnkey corporate offset procurement.**
- **Open-source carbon offset management is essentially nonexistent as a corporate product.** The National Carbon Credit Registry is the most significant project, but it is **government infrastructure for sovereign carbon accounting**, not a corporate offset purchasing platform . CarbonCreditBuy explicitly disclaims certification (`certified: false`) and uses synthetic demo data . **Organizations wanting to buy and retire credits for corporate net-zero targets will need commercial platforms.**
- **Carbon removal vs. avoidance matters.** Shopify Planet funds **durable carbon removal** (DAC, biochar, enhanced weathering) . Tradewater funds **avoidance** (refrigerant destruction, methane capture) . Climeworks provides **engineered removal** (DAC) . **These are not interchangeable**—removal credits are generally more expensive and durable; avoidance credits are cheaper but do not remove existing atmospheric CO₂. **Understand what you are buying.**
- **Pachama's acquisition by Carbon Direct** consolidates the MRV layer into a broader carbon management suite . **The standalone Pachama platform may not remain available as before**—verify current offerings.
- **Pricing opacity is universal across commercial offset providers.** Shopify Planet has transparent per-order fees; CarbonClick publishes tiered pricing; Ecologi and Wren have consumer subscription pricing. Pachama, Patch, Climeworks, South Pole, Cloverly, and Tradewater require sales contact. **Validate with direct vendor conversations against your credit volume and quality requirements.**
- **Carbon credit quality varies dramatically.** Look for ICVCM Core Carbon Principles labels (as Tradewater claims ), Gold Standard or Verra certification (as Ecologi and South Pole reference ), and transparent MRV (as Pachama provided ). **Cheap credits from questionable projects do not advance climate goals and create reputational risk.**
- Self-hosted open-source solutions require proper infrastructure and ongoing maintenance. **Carbon accounting data and credit transactions are increasingly subject to regulatory scrutiny**—ensure your systems meet emerging disclosure requirements (CSRD, ISSB, SEC climate rules) before relying on them for compliance reporting.

---

**Made for developers, sustainability teams, and organizations building transparent carbon offset solutions.**
Let's make Carbon Offset Management more open, data-driven, and climate-integrity-focused.
