# DOSCOTCH GLOBAL TAX ADVISORY
## Federal Income Tax Module: Assessment Lens
### US Federal Income Tax | Private C Corporation
### Internal instrument. Not client-facing. Never presented as a scored document.

**Version:** 1.0 | **Entity scope:** Private C corporation (or private consolidated group of C corporations); flow-through and public company fact patterns are out of scope of this module | **Suite reference:** Federal Income Tax Module, file 1 of 3 (Assessment Lens; IDR Section; Interview Module) | **Governed by:** D1 Findings Register schema, Priority Rating definitions, and Finding Type definitions, which apply unmodified

---

## MODULE SCOPE AND OPERATING RULES

This module supplies federal income tax content for the eight-dimension diagnostic framework established in D1. It does not replace D1. The Findings Register, its schema, its usage rules, and the Planning Opportunity Log filter are defined once in D1 and are not restated here. Every rule in D1 applies to records generated through this module.

**Scope of this module:**

1. United States federal income tax only. The assumed client is a C corporation, or a group of C corporations filing a consolidated federal return, held by a private equity sponsor.
2. The client is assumed to have audited financial statements. The ASC 740 income tax provision is therefore in scope, including the interaction with the financial statement auditors.
3. State income and franchise taxes are OUT of module scope. They are covered by the State Income Tax Module. Where fieldwork under this module surfaces a state income tax observation, capture it as a register record (Tax type: income; Jurisdiction: the state) and flag it in the Evidence reference field as outside the current module's assessment scope. Do not assess it here; do not ignore it.
4. International items are OUT of module scope. Forms 5471, 5472, 1118, GILTI, subpart F, foreign tax credits, transfer pricing, and treaty positions are covered by the Federal International Module. The same capture-and-flag rule applies: the existence of an unaddressed international filing obligation is recorded when observed, but the assessment of it belongs to the international module.
5. Sales and use, property, franchise, and other indirect taxes remain with the SUT module and the D-suite as built.

**Register conventions for this module:**

- Tax type(s): income. Jurisdiction(s): Federal, unless the record is a flagged state or international observation per rules 3 and 4.
- Source values use this module's ID series: IDR-FED-D#-## for document requests, Q-FED-D#-## for interview questions, Q-EA-## for the external advisor module.
- One F-### series for the whole engagement. Federal income findings do not get their own numbering; the register is one register.

**Controls standard.** Content is written to a private company standard. Where the client has public debt or is otherwise an SEC reporter, the Dimension 2 and Dimension 8 content should be read against SOX 404 requirements, and the absence of formal ICFR documentation for the tax provision moves ratings up, not down.

---

# THE ASSESSMENT LENS

---

## DIMENSION 1: GOVERNANCE AND OVERSIGHT

**Layer 1 (internal).** The structures, policies, and decision rights that direct the federal income tax function: ownership of the provision and the return, signing authority on filed returns, approval rights over tax elections and accounting method changes, escalation protocols for IRS contact, executive and audit-level visibility into the effective tax rate and material positions, and formal oversight of the external return preparer and any provision assistance engagement.

**Layer 2 (CFO translation).** Who is accountable for the numbers on your federal tax return and in your tax provision, and would that accountability hold up if your auditor, the IRS, or your sponsor asked who approved a position.

**What good looks like at a PE-backed portfolio company:**
- A single named owner of federal income tax with a written mandate, even where the return is fully outsourced. Outsourcing the preparation never outsources the accountability; the return is signed under penalties of perjury by a client officer, and that officer knows what they are signing.
- Decision rights documented in brief: who approves an election, a method change, an amended return, or a settlement with the IRS, and at what dollar or judgment threshold the CFO and the sponsor must be involved.
- The effective tax rate and cash tax posture appear in recurring reporting to the CFO and sponsor, even if one page. A PE sponsor models cash taxes into returns; a function that cannot explain its own rate cannot be trusted with the model.
- The preparer and provision engagement letters are reviewed at least annually against the current structure, because acquisitions and reorganizations routinely outrun a preparer's engaged scope.
- Escalation thresholds are defined and written: any IRS notice, any exam opening, any proposed adjustment above $[X], and any question touching the sponsor's structure go to the CFO immediately.

**Diagnostic questions (consultant answers these):**
1. Is there a single named owner of federal income tax, and does that person know they own it, or does ownership effectively sit with the outside preparer?
2. Who signed the most recent Form 1120, and can that person explain the material positions on it?
3. Are any decision rights documented for elections, method changes, amended returns, or exam settlements? Does the delegation of authority matrix address income tax at all?
4. Does the effective tax rate or cash tax forecast appear anywhere in recurring CFO, board, or sponsor reporting?
5. Who last read the preparer's engagement letter, and does its entity list match the current legal entity structure?
6. What is the documented path when IRS correspondence arrives? If undocumented, what is the tribal path?
7. Has ownership of income tax changed hands in the last three years, and was there a formal handoff of open items, carryforward support, and elections history?

**Typical findings and calibration:**
- No named internal owner; the outside preparer is treated as the de facto tax department, and no one inside can state the company's material federal positions. **Red, Risk Exposure.** The signing officer is certifying a return no one inside the company understands; accountability has been abdicated, not delegated. Pairs with the Dimension 5 review-capability finding; record both if the observations are distinct (mandate versus capability).
- The preparer's engagement letter has not been updated since [Year] and omits entities acquired since then. **Red, Risk Exposure.** The gap between believed scope and engaged scope is where missed filings come from; this is the income tax version of the SUT boundary finding.
- IRS notices are routed to a shared inbox or the registered agent with no escalation protocol and no log. **Red, Risk Exposure.** Federal notice timelines are short, and a missed 90-day letter converts a disputable adjustment into an assessed liability.
- The ETR and cash tax posture never appear in sponsor or CFO reporting; tax surfaces only at return time. **Yellow, Risk Exposure.** Address in build through the dashboard and readout cadence; not bleeding today.
- No written policies exist for elections, method changes, or records retention; institutional knowledge of positions taken lives with the preparer. **Yellow, Risk Exposure.** Goes red where the preparer relationship is ending or the engagement team has turned over, because the knowledge walks.

---

## DIMENSION 2: PROCESS AND CONTROLS

**Layer 1 (internal).** The repeatability and control design of the recurring federal income tax processes: the annual and any interim ASC 740 provision cycle, the return preparation and filing cycle, the return-to-provision true-up, extension and estimated payment management, preparation and review segregation, approval steps, and evidence retention for both the provision and the return.

**Layer 2 (CFO translation).** If the person who runs your tax provision and coordinates your return left tomorrow, would either still happen correctly and on time, and could you show your auditor the evidence that they did.

**What good looks like:**
- The provision cycle is documented as a runbook integrated with the close calendar: trigger, data inputs, who prepares, who reviews, what the auditors receive, and what evidence is retained.
- The return cycle has the same discipline: a preparer deliverable calendar, a defined client review step before filing, and a signoff that is more than a signature on an e-file authorization.
- The return-to-provision true-up is performed every year, documented, and its drivers are explained, because a recurring unexplained true-up means either the provision or the return is wrong.
- Estimated payments are calculated on a documented basis (annualized income or prior-year safe harbor, chosen deliberately), scheduled, and confirmed paid; extensions are filed on a calendar, not in a scramble, with extension payments computed rather than guessed.
- Preparation and review are separated for the provision, the return, and every payment; no single person both computes and approves.

**Diagnostic questions:**
1. Is the provision process documented anywhere, or does it live in one person's spreadsheet and memory? How late in the close does it land, and is it a bottleneck?
2. Who reviews the provision before it goes to the auditors, and what does review actually consist of?
3. Is the client's review of the outside-prepared return substantive, or is it a same-day signature on the e-file authorization?
4. Is a return-to-provision true-up performed and documented each year? What has it run in the last three years, and can anyone explain the drivers?
5. How are estimated payments computed, and by whom? Has the company incurred underpayment penalties in the last three years?
6. How are extensions managed, and how is the extension payment computed?
7. If the auditors or the IRS asked for evidence of last year's provision review or return review, what would exist?
8. Where does the process depend on a single person with no backup?

**Typical findings and calibration:**
- The filed return is signed and e-filed the day it arrives from the preparer with no substantive client review. **Red, Risk Exposure.** The review step is the client's only control over an outsourced return; its absence means the preparer is effectively self-reviewing. Pairs with Dimension 5.
- No return-to-provision true-up is performed, or it is performed but the difference is booked without explanation. **Red, Risk Exposure.** An unexplained true-up is an unexplained error in the financial statements or the return; both demand immediate attention.
- Estimated payments are set by rough guess rather than a documented method; underpayment penalties have been incurred in two of the last three years. **Yellow, Risk Exposure.** Recurring penalties are the visible symptom; the missing computation discipline is the condition. Goes red where cash tax forecasting also feeds sponsor reporting, because the same weak number is being reported upward.
- The provision is prepared and reviewed by the same person, with the auditors functioning as the de facto reviewer. **Yellow, Risk Exposure.** Auditors testing the number is not the same as the company controlling it, and audit adjustments to the tax provision are among the most common late-close surprises. Goes red for an SEC reporter or where the auditors have proposed provision adjustments in consecutive years.
- The provision workbook rebuilds the same trial balance mappings manually every year, consuming days of close time; the output has been consistently correct. **Yellow, Operational Efficiency.** This is the calibration example for pure efficiency in this module: verified correct, costly only in time.

---

## DIMENSION 3: DATA INTEGRITY

**Layer 1 (internal).** The accuracy, completeness, and auditability of data feeding the provision and the return: trial balance to provision to return traceability, book-tax difference support, fixed asset data and tax depreciation records, deferred tax rollforwards proved against balance sheet accounts, carryforward attribute support (NOLs, credits, interest limitation), and the quality of the data package handed to the external preparer.

**Layer 2 (CFO translation).** Can the numbers on your tax return and in your tax provision be traced back to your books, item by item, and would that trail survive both your auditor and an IRS exam.

**What good looks like:**
- Every material line of the return reconciles to the provision and to the general ledger, and the reconciliation is retained as a workpaper, not reperformed from scratch when someone asks.
- Every material book-tax difference has current support: a schedule, a policy, and an owner, not a number rolled forward because it was there last year.
- The deferred tax balance is proved: a rollforward ties opening to closing, and the closing balance ties to a supportable inventory of temporary differences, not a plug.
- Tax depreciation is maintained in a system or workpaper set that reconciles to the fixed asset ledger; book-tax basis differences in fixed assets are supportable at the asset class level.
- Carryforward attributes (NOLs, credit carryforwards, disallowed interest under 163(j)) are supported by a schedule tracing each vintage to the return year that generated it, including the effect of any ownership changes.
- The data package sent to the preparer is a defined, repeatable extract with a checklist, not a bespoke scramble reassembled every year.

**Diagnostic questions:**
1. Can the most recent filed return be tied to the provision and the GL, and has anyone inside the company ever actually done it?
2. Which book-tax differences are computed fresh each year, and which are rolled forward on inertia? Who owns each material difference?
3. Has the deferred tax balance ever been proved to an inventory of temporary differences, or is it a rolled-forward plug? When the auditors last tested it, what happened?
4. Where does tax depreciation live, does it reconcile to the fixed asset ledger, and who maintains it after acquisitions bring in new asset bases?
5. Is there a schedule supporting every NOL and credit carryforward by vintage, and does it reflect the sponsor's acquisition and any other ownership changes?
6. What does the preparer actually receive each year, in what form, and how much of it does the preparer's team rework or chase?

**Typical findings and calibration:**
- The deferred tax balance has never been proved to an inventory of temporary differences; it is a rolled-forward plug that the auditors test around rather than through. **Red, Risk Exposure.** The balance sheet is carrying a number no one can support; this is a financial statement exposure today, not a hypothetical.
- NOL carryforwards are carried at face value with no vintage schedule and no analysis of the limitation arising from the sponsor's acquisition. **Red, Risk Exposure.** An attribute the company cannot support at the claimed amount is an exposure in exam and a diligence finding at exit. Calibration note: the missing 382 analysis is this record; whether a paid 382 study is warranted is a build-phase question, not a Planning Opportunity.
- Material book-tax differences are rolled forward each year without reperformance; at least one schedule's support traces to a departed employee or a prior preparer. **Yellow, Risk Exposure.** Goes red the moment a rolled-forward difference is material to the rate or is implicated in a known error.
- Fixed asset tax basis records for an acquired business were never obtained at close; tax depreciation for those assets is estimated. **Yellow, Risk Exposure.** Records both the data gap here and, where diligence also failed, a Dimension 7 record; two observations, two records.
- The preparer data package is reassembled from scratch each year by one person over several weeks, duplicating schedules the provision workbook already contains. **Yellow, Operational Efficiency.**

---

## DIMENSION 4: TECHNOLOGY UTILIZATION

**Layer 1 (internal).** The fit and governance of the technology supporting the provision and compliance cycle: provision software or the controlled absence of it, tax depreciation software, the preparer's portal and data exchange tools, workbook version control and access, and the data flow from source systems into the provision with its manual intervention points.

**Layer 2 (CFO translation).** Is your tax provision built on tooling you control and could hand to a successor, or on a fragile spreadsheet only one person can operate, and who would know if it silently broke.

**What good looks like:**
- A deliberate tooling decision has been made and documented: provision software where complexity warrants it, or a well-controlled workbook where it does not. Either is defensible; drift is not.
- Whatever the tool, it has a named owner, version control, restricted access, and documentation sufficient for a successor to operate it.
- Tax depreciation runs in a maintained system reconciled to the fixed asset ledger, not in a legacy workbook whose formulas no current employee wrote.
- Data enters the provision through defined extracts from the ERP and consolidation system, with manual intervention points known, listed, and minimized.
- Formula changes and mapping changes in the provision workbook are reviewed by someone other than the person who made them, at least annually.

**Diagnostic questions:**
1. What tooling produces the provision today, who owns it, and was the choice ever deliberate?
2. If the provision is a workbook: who built it, is version control real, who else can operate it, and when did a second person last review its formulas and mappings end to end?
3. Where does tax depreciation run, who maintains it, and does it reconcile to the fixed asset ledger?
4. What are the manual touch points between the ERP and the finished provision, and which have caused errors before?
5. Who can access and modify the provision files, and is any change history retained?
6. What does the preparer's technology expect from the client, and how much rework happens at that interface?

**Typical findings and calibration:**
- The provision runs in a workbook built by a departed employee; formulas are undocumented, a known hardcode exists, and no one currently on staff can explain the state rate mapping tabs. **Red, Risk Exposure.** The company is reporting a financial statement number produced by logic it cannot explain; this is the income tax parallel of filing on an engine no one can articulate.
- No review of provision workbook formula or mapping changes occurs; changes are made live during close by the preparer of the provision. **Yellow, Risk Exposure.** Goes red when an error traced to an unreviewed change has already occurred or the entity is an SEC reporter.
- Tax depreciation runs in software licensed and maintained by the preparer; the client holds no copy of the asset-level tax basis data. **Yellow, Risk Exposure.** A provider-held record the client cannot produce is a continuity and transition exposure; route the data request through the external advisor interview, and record a finding sourced to both if the preparer cannot produce it either.
- Provision software is licensed but abandoned after a failed implementation; the license renews annually while the workbook does the work. **Yellow, Operational Efficiency.** Record the unused license as efficiency and any workbook control gap as a separate risk record. Two observations, two records.
- Access to the provision workbook is open to the whole finance shared drive. **Yellow, Risk Exposure.**

---

## DIMENSION 5: TALENT, STAFFING AND EXPERTISE

**Layer 1 (internal).** The sufficiency of internal capability relative to what the federal function requires: capacity and technical depth in ASC 740 and federal compliance oversight, the ability to review and challenge preparer and provision output, key-person dependency, the development path for any intended internal owner, and the match between the outsourcing perimeter and internal oversight capacity.

**Layer 2 (CFO translation).** Is there anyone inside your company who can tell you whether your tax provision and your federal return are actually right, or are you taking your preparer's word for both.

**What good looks like:**
- A named internal owner with protected time and income tax written into their role, even if fractional.
- The internal owner can review the provision and challenge the preparer's return at a working level, or a defined channel exists to someone who can, independent of the preparer being reviewed.
- ASC 740 competence exists somewhere the company can reach on its own terms: in-house, a retained advisor, or a structured support arrangement, and not solely inside the audit firm or the preparer.
- Documented backup exists for the provision and the compliance calendar; neither fails on one person's absence.
- Where the CFO intends to ramp an internal person into ownership, a development plan with milestones exists, and its ASC 740 component is realistic about how specialized that skill is.

**Diagnostic questions:**
1. Who actually spends time on federal income tax, what fraction of their role, and what is their background in it, specifically in ASC 740?
2. Can anyone inside the company evaluate the preparer's return or the provision computation, or is the preparer effectively reviewing itself?
3. When the preparer sends a question requiring a judgment call (an election, a position, a characterization), who inside is equipped to make it, and who actually makes it today?
4. Where is the single point of failure, and what happens during that person's absence or departure?
5. Is the outsourcing perimeter deliberate and matched to internal capacity, or was it drawn by default and never revisited?
6. If the CFO plans to build internal ownership, what is the honest gap between the intended owner today and the role, and does the plan account for provision competence separately from compliance coordination?

**Typical findings and calibration:**
- No one inside the company can evaluate the provision or the return; the preparer computes both and the same firm's work is the only check on itself. **Red, Risk Exposure.** Outsourcing without oversight is abdication, and the liability, the signature, and the financial statements all remain the client's.
- The controller inherited income tax with no ASC 740 background, no training channel, and no protected time; the provision is assembled by pattern-matching last year's file. **Red, Risk Exposure.** Pairs with the Dimension 1 ownership finding; record both only if the observations are distinct (mandate versus capability).
- The provision and the compliance calendar both depend on one person with no trained backup and nothing written. **Yellow, Risk Exposure.** Goes red when that person's departure is announced or imminent.
- The intended future owner has capacity and accounting depth but no income tax background; no development plan exists. **Yellow, Risk Exposure.** Seeds the readiness assessment in Phase 3; the plan should treat ASC 740 as its own workstream, not a chapter.
- The company has no advisor channel for federal questions outside the preparer's compliance scope; questions the preparer declines simply go unanswered. **Yellow, Risk Exposure.**

---

## DIMENSION 6: RISK IDENTIFICATION AND QUANTIFICATION

**Layer 1 (internal).** The processes for surfacing, assessing, and measuring federal income tax exposure: identification and documentation of uncertain tax positions under ASC 740-10, an exposure inventory with quantification, reserve evaluation with the financial statement auditors, exam history and open controversy tracking, statute of limitations monitoring, and substantiation of the attributes the balance sheet relies on, including valuation allowance judgments.

**Layer 2 (CFO translation).** Do you know which positions on your federal returns could be challenged, how much each could cost, whether your reserves reflect that honestly, and which years the IRS can still reach.

**What good looks like:**
- An inventory of uncertain tax positions exists, is refreshed annually with the provision, and each position carries documented technical support proportionate to its size.
- Known exposures are quantified, even in ranges, and reserve treatment has been evaluated deliberately with the auditors rather than defaulting to zero because no one raised it.
- A statute of limitations tracker exists by filing year, including the effect of any extensions granted, amended returns, and carryforward years held open by attribute usage.
- Exam history and outcomes are logged; prior adjustment themes inform current positions rather than repeating.
- Valuation allowance judgments on deferred tax assets are documented with the four sources of taxable income considered, refreshed when facts change, and not simply rolled forward.
- The company knows which of its attributes (NOLs, credits, interest carryforwards) would survive scrutiny at claimed amounts, because exit diligence will ask exactly that.

**Diagnostic questions:**
1. Does any inventory of uncertain positions exist, and does it match what the auditors were told during the last audit?
2. What positions on recent returns would the internal team least want examined, and has anyone quantified them?
3. Has reserve treatment for known exposures been evaluated with the auditors, or has silence stood in for analysis?
4. Which filing years are still open, who tracks that, and have any statute extensions been granted?
5. What is the exam history, what themes recur, and were prior adjustments remediated in subsequent returns?
6. Is the valuation allowance position documented and current, or rolled forward from a different fact pattern?
7. What analysis supports the usability of the attribute balances the sponsor's exit model is counting on?

**Typical findings and calibration:**
- No uncertain tax position inventory exists; material judgmental positions are known informally but undocumented and unquantified, and the auditors have never been engaged on them. **Red, Risk Exposure.** Exposure is unmeasured and the financial statements may be silent where they should not be; this is the canonical Dimension 6 red for this module.
- No statute of limitations tracking exists; no one can say which years are open or whether extensions were granted during the last exam. **Red, Risk Exposure.** The company cannot manage what it cannot see, and open years quietly accumulate exposure.
- The valuation allowance conclusion has been rolled forward unchanged through years in which the company moved from losses to sustained profitability. **Yellow, Risk Exposure.** A stale judgment in either direction misstates the balance sheet; goes red when the auditors have already questioned it or an exit process is contemplated within the year.
- Prior exam adjustments on [issue] were never remediated in subsequent returns; the same treatment continues. **Red, Risk Exposure.** A known, repeated error with exam history behind it is aggravated, not ordinary.
- Analysis of recent capital spending suggests reclassification could accelerate deductions through a cost segregation or method review. **Planning Opportunity.** Calibration note: the routing rule from D1 applies with force in this module; the value of a potential method change, credit study, or accelerated deduction is a Planning Opportunity, while any risk in the current treatment is a separate Risk Exposure record. One situation frequently yields both records.

---

## DIMENSION 7: STRATEGIC ALIGNMENT

**Layer 1 (internal).** The connection between the federal tax function and business and sponsor decision-making: whether tax input reaches acquisitions, dispositions, financing, and structural decisions before they are executed; transaction cost treatment; the tax dimension of the capital structure, including interest deductibility; credits and incentives evaluation; and exit and diligence readiness appropriate to PE ownership.

**Layer 2 (CFO translation).** Does the business, and the sponsor, learn the federal tax consequences of deals and structural decisions before they sign or after, and would this function be ready for buyer diligence at exit.

**What good looks like:**
- A short written trigger list defines which events require federal tax input before execution: acquisitions and dispositions, entity formations and mergers, debt issuance or refinancing, material contracts with unusual structure, and equity compensation changes.
- Tax review occurs pre-signing on acquisitions: structure (stock versus asset, relevant elections), attribute impact, transaction cost analysis, and post-close integration obligations, with the analysis retained.
- The capital structure's tax posture is understood and monitored: interest deductibility under the 163(j) limitation is modeled, not discovered at return time.
- Transaction costs from the sponsor's acquisition and any add-ons have been analyzed and documented, not defaulted entirely to one treatment.
- Federal credits, principally the R&D credit where the fact pattern supports it, have been deliberately evaluated, with the conclusion documented even when the answer is no.
- Core documentation is maintained diligence-ready: returns, workpapers, attribute schedules, elections history, exam files, and position support, assembled or assemblable on short notice.

**Diagnostic questions:**
1. How does federal tax input reach deal and structural decisions: before signing or after close? Walk the most recent acquisition or refinancing through that test.
2. Were transaction costs from the sponsor's acquisition and any add-ons analyzed and documented, and is the support retrievable?
3. Is interest deductibility under the limitation modeled as part of financing decisions, and who owns that model?
4. Have federal credits ever been deliberately evaluated against the company's fact pattern, and is the conclusion documented?
5. Would current documentation survive buyer-side federal tax diligence today, and what would the findings list look like?
6. Who tells the preparer when the structure changes, and how quickly?

**Typical findings and calibration:**
- A recent add-on acquisition closed with no federal tax review: no structure analysis, no attribute assessment, no transaction cost study, and integration obligations discovered at return time. **Red, Risk Exposure.**
- Interest deductibility under the limitation has never been modeled despite a leveraged capital structure; the disallowed carryforward appears on the return but nowhere in management's financing math. **Yellow, Risk Exposure.** The return is capturing a number the business is not managing; goes red when a refinancing is actively contemplated without it.
- Transaction costs from the sponsor's acquisition were expensed or capitalized wholesale with no analysis. **Yellow, Risk Exposure.** Where analysis suggests favorable treatment was forgone, record the potential recovery as a separate Planning Opportunity; the routing rule splits this situation into two records.
- No diligence-ready documentation exists; assembling the federal tax folder for a data room would take weeks and surface gaps a buyer would price. **Yellow, Risk Exposure.** For a PE-backed client this framing lands hard, and it is honest.
- The company's engineering payroll and development activity have never been evaluated against the R&D credit. **Planning Opportunity.** This dimension routinely generates Planning Opportunities; the D1 routing rule applies unchanged: the risk of missing tax input is a finding, the value of the input itself is a Planning Opportunity, separate records.

---

## DIMENSION 8: COMPLIANCE ACCOUNTABILITY

**Layer 1 (internal).** The clarity and completeness of ownership across every federal obligation: a full inventory of federal filings and payments for every entity in the group, explicit mapping of each obligation to an internal or external owner, reconciliation of the preparer's engaged scope against the inventory and against the current entity structure, confirmation that returns were accepted and payments cleared, and active calendar management across extensions, estimates, and the return itself.

**Layer 2 (CFO translation).** For every federal filing and payment this company and every entity in its group owes, can you name the person or firm responsible, and can you prove each one was made. This dimension is the direct test of whether anything is falling through the cracks at the federal level.

**What good looks like:**
- A complete federal obligation inventory exists: every entity, every filing (the consolidated return, any separate filings, information returns), every payment (estimates, extension payments, balance due), in one place with dates.
- The inventory reconciles to the current legal entity list, including entities added by acquisition and entities dissolved, because orphaned entities generate orphaned filings.
- Every line has a named owner, internal or preparer, with no unowned space, and the preparer's engagement letter has been reconciled line by line against the inventory.
- A confirmation loop exists independent of the preparer: e-file acceptances are retained, and payment clearance is verified through the company's own EFTPS access, with credentials held by the client.
- The commonly orphaned federal items are affirmatively owned: information return obligations flagged by the international module, elections and statements that must be attached or renewed, and the filing consequences of entities acquired mid-year.

**Diagnostic questions:**
1. Does a complete federal obligation inventory exist anywhere, in any form, covering every entity in the group?
2. Has the preparer's engaged scope ever been reconciled against that inventory and against the current entity list? What falls in the gap?
3. What does the client believe the preparer handles that the engagement letter does not actually cover: estimates, extensions, notices, exam support, new entities?
4. Who confirms that returns were accepted and payments cleared, and does the company hold its own EFTPS credentials, or does the preparer?
5. For each entity acquired in the last five years: who owns its pre-close federal filing history and its stub period returns, and were they filed?
6. When the routing conversation could not assign an owner to a question, which federal obligations did those questions touch?

**Typical findings and calibration:**
- No federal obligation inventory exists; coverage is assumed complete because "the accountants handle it," and the entity list the preparer works from predates two acquisitions. **Red, Risk Exposure.** This is the canonical falling-through-the-cracks condition in the federal module, and the entity list mismatch is what makes it concrete rather than theoretical.
- Stub period and pre-close returns for an acquired entity were never confirmed filed; each party assumed the other handled them. **Red, Risk Exposure.**
- No confirmation loop exists: the company retains no e-file acceptances and has no EFTPS access of its own; the preparer holds the only evidence and the only credentials. **Yellow, Risk Exposure.** Goes red if any filing or payment has already been discovered missed. Provider-held credentials are also a transition finding for Phase 3; the client must be able to see its own account.
- Estimated payments are owned by no one between the preparer's voucher email and the treasury function; one payment in the last two years was made late. **Yellow, Risk Exposure.** Goes red where the pattern is recurring, because it evidences the unowned handoff, not a one-time slip.
- Required election statements and attachments exist only in the preparer's files; the client holds no copy of its own elections history. **Yellow, Risk Exposure.** The income tax version of provider-held records: route the request through the external advisor interview, and a held item the preparer cannot produce becomes a finding sourced to both.

---

## WORKED REGISTER EXAMPLES (module calibration)

These follow the D1 schema exactly and calibrate this module's ratings against the D1 examples.

**Example 1: Red, Risk Exposure**

| Field | Entry |
|---|---|
| Finding ID | F-0## |
| Finding description | The deferred tax balance of $[X] has never been proved to an inventory of temporary differences and is carried forward as an unsupported balance. The financial statements are relying on a number the company cannot substantiate. |
| Dimension | 3. Data Integrity |
| Tax type(s) | Income |
| Jurisdiction(s) | Federal |
| Source | IDR-FED-D3-04 (deferred proof: Does Not Exist); interview, [Controller] |
| Priority Rating | Red |
| Finding Type | Risk Exposure |
| Recommended action | Build a supported temporary difference inventory and prove the deferred balance before the next audit cycle. |
| Status | Open |
| Owner | [blank in Phase 1] |
| Date identified | [Date] |
| Evidence reference | Provision workbook FY[Year]; auditor PBC correspondence noting prior-year test-around approach. |

**Example 2: Yellow, Operational Efficiency**

| Field | Entry |
|---|---|
| Finding ID | F-0## |
| Finding description | The annual preparer data package is reassembled from scratch over approximately [X] weeks, duplicating schedules already maintained in the provision workbook. The output has been accurate; the cost is time. |
| Dimension | 2. Process and Controls |
| Tax type(s) | Income |
| Jurisdiction(s) | Federal |
| Source | Interview, [Staff Accountant]; Q-EA-03 (preparer confirms rework on receipt) |
| Priority Rating | Yellow |
| Finding Type | Operational Efficiency |
| Recommended action | Define a standing extract and checklist so the provision workbook feeds the preparer package directly. |
| Status | Open |
| Owner | [blank in Phase 1] |
| Date identified | [Date] |
| Evidence reference | Walkthrough of annual cycle, [Date]; no error history, supporting the efficiency (not risk) classification. |

**Example 3: Planning Opportunity**

| Field | Entry |
|---|---|
| Finding ID | F-0## |
| Finding description | The company's development activity and engineering payroll of $[X] have never been evaluated against the federal R&D credit. A credit may be available for open years. |
| Dimension | 7. Strategic Alignment |
| Tax type(s) | Income |
| Jurisdiction(s) | Federal |
| Source | IDR-FED-D7-03 (credit evaluations: Does Not Exist); interview, [CFO] |
| Priority Rating | Yellow |
| Finding Type | Planning Opportunity |
| Recommended action | Route to Planning Opportunity Log; separate conversation on credit study feasibility and open-year claims. |
| Status | Open |
| Owner | n/a (out of scope of current engagement) |
| Date identified | [Date] |
| Evidence reference | Payroll census by function FY[Year]; value stated qualitatively pending workpaper support. |

*End of Federal Income Tax Module: Assessment Lens.*
