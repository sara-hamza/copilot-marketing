# copilot-marketing

## What it does

Marketing Copilot: copy improvement, audience variants, headlines, proofing and FAQ generation.

Part of the **department-copilots** suite: local-only copilots where the employee provides the input, Claude analyses it on the machine, and the employee decides what to do. No CRM, NMS, email or system integrations.

## Install

```bash
claude plugin marketplace add sara-hamza/department-copilots
```

```bash
claude plugin install marketing@department-copilots
```

Paste the draft, the campaign brief or the event notes and get back polished copy with every change listed, versions for each audience with the facts kept identical, headline options grouped by angle, a proofing table, or an FAQ set.

| Command | Use when |
|---|---|
| `/marketing:polish <paste draft>` | Improve the copy and get a CHANGES MADE list so you can accept or reject each change |
| `/marketing:variants <paste copy>` | Versions for residents, developers, RSPs and internal staff with identical facts |
| `/marketing:headlines <paste brief or copy>` | 8 to 10 headline options grouped by angle |
| `/marketing:proof <paste copy>` | Grammar, consistency and brand check as an Issue / Location / Fix table |
| `/marketing:faq <paste brief or announcement>` | FAQs with answers drawn only from the input, and the questions the input cannot answer yet |

Requires `copilot-common` (privacy rules, document-reader for briefs and brochures exported as PDF, screenshot-reader for social or web screenshots, writing-helper for house style).

Reference knowledge lives in `skills/marketing-copilot/references/`. The brand voice (tone, terms to use and avoid, claims that need substantiation) is a sensible default marked `CUSTOMISE`; replace it with the company's brand guide.
