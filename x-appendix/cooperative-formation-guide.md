# Global Cooperative Formation Guide

*(or, How to Build the Membrane in Your Country)*

> **TL;DR:** The Nowland Hub's legal wrapper — the Social/Benefit Worker Cooperative — maps to recognized legal structures in every major economy. This appendix provides the country-specific formation steps, minimum member requirements, audit obligations, patronage dividend mechanics, and self-billing (fintech automation) procedures for each jurisdiction.

---

**Disclaimer:** This guide is a thermodynamic pattern for study, not legal advice. Every Hub must engage qualified local accountants and cooperative-law attorneys before processing its first fiat transaction. Laws change. Verify all details against current statutes.

---

## 🇩🇪 Germany — *Genossenschaft (eG)*

### Formation Requirements
* **Minimum Members:** 3 (natural persons or legal entities — meaning 3 Pod GmbHs can form the eG)
* **Registration:** Commercial Register (*Handelsregister*) + mandatory membership in a cooperative audit federation (*Genossenschaftsverband*, e.g., DGRV, GdW)
* **Articles of Association (*Satzung*):** Must define the cooperative's *Förderzweck* (purpose of promoting members' interests), membership rules, and governance structure
* **Governing Bodies:** Board of Directors (*Vorstand*), Supervisory Board (*Aufsichtsrat*, mandatory for > 20 members), General Assembly (*Generalversammlung*)

### Social/Benefit Status
Register the eG with a **Förderzweck** (social purpose) clause in the articles. This legally mandates the cooperative to create benefit for its members and community — shielding spending on open-source tools, community events, and shared infrastructure as legitimate operating expenses. Germany does not have a separate "Benefit Corporation" label; the Förderzweck clause within the eG achieves the same function.

### Audit Requirements
* **Mandatory** — every eG must be audited by its registered Genossenschaftsverband (audit federation)
* Small cooperatives (< €2M revenue): simplified audit every 2 years
* Larger cooperatives: annual full audit
* **Estimated Annual Cost:** €2,000–5,000 for small eGs; scales with revenue

### Patronage Dividend Mechanics (*Rückvergütung*)
* Surplus distributed to members proportional to their *use* of the cooperative (not capital contribution) — this maps directly to the Syntropy Split
* *Rückvergütung* is **tax-deductible** for the cooperative — it reduces CIT
* Members receive it as taxable income (personal or corporate, depending on member entity type)
* Indivisible reserves (*Unteilbare Rücklagen*) cannot be distributed even on dissolution — they are the permanent commons

### Self-Billing / Fintech Automation
**Gutschriftsverfahren** (Credit Note / Self-Billing) under **§ 14 Abs. 2 UStG**:
* The Hub (as buyer of services) generates the invoice *on behalf of* the Pod/Node (the supplier)
* Both parties must agree to the procedure in writing (included in the B2B service agreement)
* The credit note must contain all standard invoice elements (VAT number, line items, tax rate)
* The supplier must not have issued their own invoice for the same transaction
* VAT is matched quarterly via the standard *Umsatzsteuervoranmeldung*
* **Automation:** The Hub's accounting API generates Gutschriften automatically for each Pod at each payout cycle, eliminating manual invoicing entirely

### Formation Cost Estimate
* Registration fees: ~€200–500
* Genossenschaftsverband admission: ~€500–2,000
* Legal setup (articles, operating agreements): ~€2,000–5,000
* **Total estimated:** €3,000–8,000

---

## 🇮🇹 Italy — *Società Cooperativa*

### Formation Requirements
* **Minimum Members:** 9 for a standard *Società Cooperativa* (natural persons or legal entities). 3 for a *Piccola Società Cooperativa* (small cooperative) — but only natural persons, no corporate members
* **Registration:** Chamber of Commerce (*Camera di Commercio*), Company Register (*Registro delle Imprese*)
* **Notary:** Required for deed of incorporation
* **Mandatory Fund:** 3% of annual net profit must be allocated to the *Fondo Mutualistico* (national mutual fund for cooperative development)

### Social/Benefit Status
Add **Società Benefit** status — a single entity with dual legal qualification. The cooperative's articles include specific *beneficio comune* (common benefit) objectives. An annual *Relazione di Impatto* (Impact Report) is published. This shields community-benefit spending as a legally mandated operating purpose.

### Audit Requirements
* Cooperatives with > €1M revenue or > 60 members: mandatory statutory audit
* Smaller cooperatives: subject to periodic inspections by the Ministry of Economic Development (*MISE*)
* **Estimated Annual Cost:** €3,000–8,000 for audit; €500–1,500 for MISE inspection preparation

### Patronage Dividend Mechanics (*Ristorni*)
* Surplus is distributed as *Ristorni* (patronage refunds) proportional to each member's **use** of the cooperative
* **Worker cooperatives:** Ristorni distributed as *wage integration* — taxed as employment income for the member
* **Consumer/user cooperatives:** Ristorni treated as price reductions — taxed differently
* IRES (corporate tax) exemptions apply on indivisible reserves (*Riserve Indivisibili*) — surplus allocated to indivisible reserves is not subject to IRES
* Indivisible reserves cannot be distributed even on dissolution — they transfer to the national mutual fund

### Self-Billing / Fintech Automation
**Autofattura** via the mandatory **SDI** (Sistema di Interscambio) e-invoicing system:
* All B2B invoices in Italy must pass through the SDI — the government's centralized electronic invoicing exchange
* Self-billing (*Autofattura*) is permitted for specific transaction types (reverse charge, intra-community, etc.)
* The Hub generates electronic invoices (format XML FatturaPA) on behalf of Pods via API integration with the SDI
* All invoices are automatically stored and validated by the Italian Revenue Agency (*Agenzia delle Entrate*)
* **Automation:** Full API integration with certified SDI intermediaries (e.g., Aruba, TeamSystem) enables automated credit note generation

### Formation Cost Estimate
* Notary fees: ~€1,500–3,000
* Registration fees: ~€300–500
* Legal setup: ~€2,000–4,000
* **Total estimated:** €4,000–8,000

---

## 🇫🇷 France — *SCOP / SCIC*

### Formation Requirements
* **SCOP (Société Coopérative et Participative):** Minimum 2 members (employees). Employees must hold at least **51% of capital** and **65% of voting rights**.
* **SCIC (Société Coopérative d'Intérêt Collectif):** Minimum 3 members from at least 3 different categories (e.g., workers, beneficiaries, public entities). Multi-stakeholder by design.
* **Registration:** Commercial Register (*Registre du Commerce et des Sociétés*) + Préfecture notification
* **The SCIC is the recommended Social/Benefit wrapper** for the Nowland Hub — its multi-stakeholder governance naturally maps to the Pod/Node/Community member categories

### Social/Benefit Status
The SCIC is inherently a social-purpose cooperative — no additional label needed. Its articles must include objectives of *intérêt collectif* (collective interest). For SCOPs, consider adding *Entreprise Solidaire d'Utilité Sociale* (ESUS) accreditation for additional tax advantages.

### Audit Requirements
* Mandatory statutory audit for cooperatives exceeding €8M revenue or 50 employees
* Smaller cooperatives: simplified accounting obligations
* **Estimated Annual Cost:** €3,000–6,000 for mandatory audit

### Patronage Dividend Mechanics (*Ristournes*)
* Surplus distributed as *Ristournes* — exempt from CIT when allocated to employee participation reserves
* **SCOP minimum allocation:** 25% to employee profit-sharing (*Participation*), 16% minimum to indivisible reserve, up to 57.5% to indivisible reserve in total
* Indivisible reserves are permanent — they cannot be distributed to members
* The remaining surplus (after reserves and participation) can be distributed as dividends, capped at the *Taux Moyen de Rendement des Obligations* (average bond yield rate)

### Self-Billing / Fintech Automation
**Autofacturation** procedure:
* French law permits self-billing when both parties agree in writing
* The buyer (Hub) generates the invoice on behalf of the supplier (Pod/Node)
* The credit note must include all standard VAT invoice elements
* Mandatory electronic invoicing (*Facturation Électronique*) is being phased in from 2026 via the *Portail Public de Facturation* (PPF) or a *Plateforme de Dématérialisation Partenaire* (PDP)
* **Automation:** Integration with a PDP enables automated B2B document flow across the Hub→Pod→Node cascade

### Formation Cost Estimate
* Registration fees: ~€200–400
* Legal setup: ~€2,000–5,000
* Accountant setup: ~€1,000–2,000
* **Total estimated:** €3,500–7,500

---

## 🇪🇸 Spain — *Sociedad Cooperativa*

### Formation Requirements
* **Minimum Members:** Varies by autonomous community (typically 3 founding members for worker cooperatives)
* **Registration:** Cooperative Register of the relevant autonomous community (*Registro de Cooperativas*)
* **Articles of Association (*Estatutos Sociales*):** Define cooperative purpose, membership rules, and surplus distribution

### Social/Benefit Status
Register as a **Cooperativa de Iniciativa Social** — a cooperative explicitly dedicated to social integration, community services, or public benefit. This shields community-goods spending as a legally mandated purpose and may qualify for additional tax exemptions.

### Audit Requirements
* Mandatory audit for cooperatives exceeding size thresholds (varies by autonomous community)
* Smaller cooperatives: simplified accounting with annual accounts filed at the Cooperative Register
* **Estimated Annual Cost:** €2,000–5,000 for audit

### Patronage Dividend Mechanics
* Surplus allocated to mandatory reserves: typically 20% to *Fondo de Reserva Obligatorio* (mandatory reserve fund) + 5% to *Fondo de Educación y Promoción* (education and promotion fund)
* Remaining surplus distributed to members proportional to their cooperative activity
* Cooperative surplus is partially exempt from *Impuesto de Sociedades* (corporate tax) when allocated to the education and social funds
* The Mondragon federation provides a proven template for inter-cooperative surplus redistribution

### Self-Billing / Fintech Automation
**Autofactura** under **SII** (Suministro Inmediato de Información):
* Spain's SII system requires real-time reporting of all invoices to the tax authority (*Agencia Tributaria*) within 4 days
* Self-billing is permitted when both parties agree and the supplier does not object within a defined period
* **Automation:** Integration with SII-compliant software enables real-time automated invoicing and reporting

### Formation Cost Estimate
* Registration fees: ~€100–300
* Legal setup: ~€1,500–3,500
* Accountant setup: ~€500–1,500
* **Total estimated:** €2,000–5,500

---

## 🇬🇧 United Kingdom — *Co-operative Society / CIC*

### Formation Requirements
* **Co-operative Society:** Minimum 3 members. Registered with the Financial Conduct Authority (FCA) under the Co-operative and Community Benefit Societies Act 2014.
* **Community Interest Company (CIC):** Minimum 1 director + 1 shareholder. Registered with Companies House and the CIC Regulator.
* **The CIC is the recommended Social/Benefit wrapper** — it includes a statutory **Asset Lock** preventing extraction of community assets.

### Social/Benefit Status
The CIC provides built-in social-purpose status:
* **Asset Lock:** Community assets cannot be transferred out except to another asset-locked body — preventing hostile takeover
* **Dividend Cap:** Currently 35% of distributable profits — ensures surplus primarily serves the community
* **Annual CIC Report:** Filed with the CIC Regulator demonstrating community benefit activities
* Alternative: register as a Community Benefit Society (BenCom) under the FCA for maximum cooperative purity

### Audit Requirements
* CICs and Co-operative Societies: statutory audit required above size thresholds (£10.2M turnover or £5.1M assets)
* Below threshold: audit exemption available, but annual accounts must still be filed
* **Estimated Annual Cost:** £2,000–5,000 for statutory audit; £500–1,500 for accountant filing

### Patronage Dividend Mechanics
* Co-operative Societies: surplus distributed proportional to member *activity* (trading surplus) — tax-deductible for the cooperative
* CICs: dividends capped at 35% of distributable profits; remainder retained for community purposes
* Both structures protect indivisible reserves from distribution

### Self-Billing / Fintech Automation
**HMRC Self-Billing Agreements:**
* The buyer (Hub) and supplier (Pod/Node) enter a formal Self-Billing Agreement
* The agreement must be notified to HMRC and reviewed every 12 months
* The Hub generates VAT invoices on behalf of the supplier — both parties retain copies
* The supplier must not issue their own VAT invoice for the same supply
* **Automation:** MTD (Making Tax Digital) compliant accounting software can generate self-billing documents automatically via API

### Formation Cost Estimate
* FCA registration (Co-op Society): ~£350
* CIC registration (Companies House): ~£27 + CIC application £0
* Legal setup: ~£1,500–3,000
* **Total estimated:** £2,000–4,000

---

## 🇺🇸 United States — *Worker Cooperative (Subchapter T)*

### Formation Requirements
* **Minimum Members:** Varies by state (typically 3–5 incorporating members)
* **Registration:** File Articles of Incorporation with the state Secretary of State. Elect **Subchapter T** tax treatment with the IRS.
* **Best States for Cooperatives:** California, Wisconsin, Colorado, Massachusetts, Vermont (strongest cooperative-specific statutes)
* **Bylaws:** Define membership, patronage allocation formula, democratic governance (one member, one vote)

### Social/Benefit Status
Register as a **Public Benefit Corporation (PBC)** — available in most states (Delaware PBC is the gold standard). The PBC charter requires directors to balance stockholder interests with public benefit and stakeholder interests. This is a single entity with dual purpose.

### Audit Requirements
* No mandatory audit for cooperatives under federal law — but many state cooperative statutes require annual financial reporting to members
* Cooperatives with > $10M revenue: external audit strongly recommended for Subchapter T compliance
* **Estimated Annual Cost:** $3,000–10,000 for CPA audit

### Patronage Dividend Mechanics
* Under **Subchapter T (IRC §§ 1381–1388):** Patronage Dividends are the cooperative's primary distribution mechanism
* Patronage Dividends are **tax-deductible** for the cooperative — they reduce federal corporate income tax to nearly zero
* Members receive Patronage Dividends as taxable income (personal or corporate)
* At least 20% of Patronage Dividends must be paid in cash (*Qualified Written Notices of Allocation*)
* The remaining 80% can be retained by the cooperative as *Retained Patronage Allocations* — bookkeeping credits owed to the member

### Self-Billing / Fintech Automation
**Automated 1099 / ACH Reporting:**
* No federal self-billing framework exists (no VAT system). Instead, the Hub issues **1099-NEC forms** to each Pod/Node entity for annual B2B payments
* Payments are routed via **ACH (Automated Clearing House)** transfers
* Payroll/contractor management APIs (Gusto, Deel, Mercury) can automate both 1099 generation and ACH disbursement
* State sales tax (where applicable) is handled separately based on nexus rules
* **Automation:** The Hub's accounting stack (e.g., QuickBooks + Gusto API) automates contractor payments, 1099 filing, and Patronage Dividend allocation

### Formation Cost Estimate
* State filing fees: ~$50–500
* Legal setup (articles, bylaws, PBC designation): ~$3,000–8,000
* CPA setup for Subchapter T: ~$2,000–5,000
* **Total estimated:** $5,000–14,000

---

## 🇸🇬 Singapore — *Co-operative Society*

### Formation Requirements
* **Minimum Members:** 5 persons (natural persons only for primary societies; legal entities for secondary/tertiary)
* **Registration:** Registry of Co-operative Societies under the Ministry of Culture, Community and Youth (MCCY)
* **Bylaws:** Must comply with the Co-operative Societies Act and Rules

### Social/Benefit Status
Singapore does not have a formal "Benefit Corporation" label. Social purpose is documented through the cooperative's stated objects in the bylaws. Consider applying for the **Singapore Centre for Social Enterprise (raiSE)** accreditation for visibility and network access.

### Audit Requirements
* Mandatory annual audit by a registered public accountant
* Annual returns filed with the Registry of Co-operative Societies
* **Estimated Annual Cost:** SGD 3,000–8,000

### Patronage Dividend Mechanics
* Surplus distributed proportional to member patronage (use of cooperative services)
* Mandatory allocation to reserve fund (at least 20% of net surplus until reserve equals paid-up capital)
* Dividends capped at a percentage set in bylaws (typically 8–10% of paid-up capital)

### Self-Billing / Fintech Automation
**InvoiceNow via the Peppol Network:**
* Singapore mandates the Peppol e-invoicing network for government procurement and is expanding to B2B
* InvoiceNow enables automated, standardized e-invoicing between registered entities
* **Automation:** Hub registers on the Peppol network via an Access Point provider and routes all B2B invoices electronically

### Formation Cost Estimate
* Registration fees: ~SGD 200–500
* Legal setup: ~SGD 2,000–5,000
* **Total estimated:** SGD 3,000–6,000

---

## 🇯🇵 Japan — *Rōdōsha Kyōdō Kumiai* (Worker Cooperative)

### Formation Requirements
* **Minimum Members:** 3 (all must be workers of the cooperative)
* **Registration:** Under the Worker Cooperative Act (2022) — Japan's first dedicated worker cooperative law
* **This is a new legal framework** — the Act was passed in 2020 and took effect in October 2022. Regulatory guidance and case law are still evolving.

### Social/Benefit Status
Japan does not have a formal "Benefit Corporation" designation. Social purpose is embedded in the cooperative's articles. Consider applying for **Social Business** certification from the Cabinet Office or relevant ministry for additional credibility.

### Audit Requirements
* Cooperatives with > ¥100M revenue: mandatory statutory audit
* Smaller cooperatives: simplified financial reporting
* Annual financial statements must be made available to all members
* **Estimated Annual Cost:** ¥300,000–800,000 for audit

### Patronage Dividend Mechanics
* Surplus distributed to members proportional to their labor contribution
* Mandatory allocation to reserves (percentage defined in articles)
* Tax treatment of distributions is evolving as the framework matures

### Self-Billing / Fintech Automation
**Qualified Invoice System (適格請求書 / *Tekikaku Seikyūsho*):**
* Introduced October 2023 as part of Japan's consumption tax reform
* Only registered *Qualified Invoice Issuers* can issue invoices that allow buyers to claim consumption tax credits
* Self-billing requires agreement between buyer and supplier; the buyer issues a *Qualified Invoice* on behalf of the supplier
* **Automation:** Integration with certified e-invoicing providers (e.g., freee, Money Forward) enables automated invoice generation and tax reporting

### Formation Cost Estimate
* Registration fees: ~¥30,000–50,000
* Legal setup: ~¥200,000–500,000
* **Total estimated:** ¥250,000–600,000 (~$1,700–4,000)

---

## 🇨🇦 Canada — *Worker Co-operative*

### Formation Requirements
* **Minimum Members:** Varies by province (typically 3–5 incorporating members)
* **Registration:** Under provincial co-operative acts (e.g., Ontario Co-operative Corporations Act, BC Cooperative Association Act, Québec Cooperatives Act) or federal incorporation under the Canada Cooperatives Act
* **Best Provinces for Cooperatives:** Québec (strongest cooperative ecosystem — Desjardins Group), British Columbia (C3 legislation), and Nova Scotia (CIC legislation)
* **Bylaws:** Define membership, surplus allocation formula, democratic governance (one member, one vote)

### Social/Benefit Status
* **British Columbia:** Register as a **Community Contribution Company (C3)** — includes a statutory asset lock and dividend cap (max 40% of profits), preventing extraction. This is Canada's closest equivalent to the UK CIC.
* **Nova Scotia:** Register as a **Community Interest Company (CIC)** — modeled directly on the UK CIC framework.
* **Other provinces:** Social purpose is documented in the cooperative's bylaws and articles. No formal "Benefit Corporation" label exists federally, but the cooperative structure itself provides strong mutual-benefit protections.

### Audit Requirements
* Federal cooperatives: annual financial statements must be provided to members; mandatory audit above certain size thresholds
* Provincial requirements vary — Québec cooperatives are subject to inspection by the *Ministère de l'Économie, de l'Innovation et de l'Énergie*
* **Estimated Annual Cost:** CAD 3,000–8,000 for external audit

### Patronage Dividend Mechanics
* Surplus distributed as **patronage dividends** proportional to each member's use of the cooperative — tax-deductible for the cooperative under the *Income Tax Act*
* Members receive patronage dividends as taxable income
* Mandatory allocation to reserves (percentage defined in bylaws/articles)
* Indivisible reserves cannot be distributed on dissolution — they transfer to another cooperative or community organization

### Self-Billing / Fintech Automation
**Standard CRA Invoicing with GST/HST:**
* Canada does not have a formal self-billing framework like the EU Gutschriftsverfahren
* B2B credit notes are widely accepted in practice — the Hub generates credit notes on behalf of Pods/Nodes
* GST/HST is reported via standard CRA filings (quarterly or annual)
* **Automation:** Integration with Canadian accounting platforms (e.g., Xero, Wave, QuickBooks Canada) automates B2B invoicing, GST/HST calculation, and T4A/T5 slip generation for patronage dividend reporting
* Canada's strong credit union movement (Desjardins, Vancity, Alterna) provides proven cooperative banking infrastructure for Hub accounts

### Formation Cost Estimate
* Provincial filing fees: ~CAD 100–500
* Legal setup (articles, bylaws): ~CAD 2,000–5,000
* Accountant setup for patronage dividend compliance: ~CAD 1,500–3,000
* **Total estimated:** CAD 4,000–9,000

---

## Cross-Jurisdiction Summary Table

| Country | Min. Members | Hub Entity | Social Status | Self-Billing Term | Estimated Setup Cost |
|---|---|---|---|---|---|
| 🇺🇸 USA | 3–5 (varies by state) | Worker Coop (Subchapter T) | PBC | 1099/ACH automation | $5k–14k |
| 🇬🇧 UK | 3 (Co-op) / 1 (CIC) | Co-op Society / CIC | CIC (Asset Lock) | HMRC Self-Billing | £2k–4k |
| 🇩🇪 Germany | 3 | eG | Förderzweck eG | Gutschriftsverfahren | €3k–8k |
| 🇫🇷 France | 2 (SCOP) / 3 (SCIC) | SCOP / SCIC | SCIC inherent | Autofacturation | €3.5k–7.5k |
| 🇮🇹 Italy | 9 (3 for Piccola) | Società Cooperativa | Società Benefit | Autofattura (SDI) | €4k–8k |
| 🇪🇸 Spain | 3 (typical) | Sociedad Cooperativa | Cooperativa de Iniciativa Social | Autofactura (SII) | €2k–5.5k |
| 🇨🇦 Canada | 3–5 (varies by province) | Worker Co-operative | C3 (BC) / CIC (NS) | CRA invoicing / credit notes | CAD 4k–9k |
| 🇸🇬 Singapore | 5 | Co-operative Society | raiSE accreditation | InvoiceNow (Peppol) | SGD 3k–6k |
| 🇯🇵 Japan | 3 | Rōdōsha Kyōdō Kumiai | (evolving) | 適格請求書 (QIS) | ¥250k–600k |

---

> ### The Core Principle
> **The Membrane is open-source.** Build the local DNA, stress-test it with professionals, and share the proven structure with the network. Every Hub that publishes its validated legal template on the Stigmergic Board makes the next Hub's formation faster, cheaper, and more resilient. The cooperative formation process is itself a Syntropic act — the friction you invest today becomes the deflationary infrastructure that every future builder inherits.
