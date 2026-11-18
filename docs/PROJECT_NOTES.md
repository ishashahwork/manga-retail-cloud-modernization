# Project notes and evidence limits

## Selected deliverables

The [report](CloudIt_Manga_RFP_Report.pdf) is the primary portfolio deliverable because it is the most complete narrative artifact available: 18 pages covering the proposal and Appendices A–G, including contributions and references. Its cover says June 2026 and its PDF metadata records creation on June 21, 2026. No submission receipt, editable source, or explicit final-version marker is available, so this selection is not proof of the officially submitted version.

The [pitch deck](Manga%20Pitch%20Deck.pdf) is a separate 10-slide summary, not a replacement report. Its cover says May 2026, while its PDF metadata records creation on June 19, 2026. The retained PDFs have not been edited to resolve these date differences.

## Interpretation of results

This was an architecture and RFP-response exercise. The supplied assignment did not require a functioning solution. No application source, complete infrastructure project, deployment outputs, dashboards, benchmark evidence, or measured business results were found.

The diagrams and workflows describe intended behavior. In particular, latency figures, savings, compliance statements, and claims about portability or availability have not been independently demonstrated by this repository. Future-improvement figures are also projections.

## Known inconsistencies in the original artifacts

- **Cost terminology:** The report's executive summary calls €282,000–€561,000 an AWS run cost, while Table 4.5 includes €120,000–€200,000 of migration and professional services. The pitch calls the total mostly one-time migration, although that line represents approximately 36–43% of the stated total. The README describes it as an indicative Year 1 total. No itemized pricing workbook, usage assumptions, or measured colocation baseline is available to validate the savings claim.
- **Growth wording:** The course brief describes annual growth of 3.5%, below the market average. The pitch displays “−3.5%,” and the report says “3.5% below market.” These are different statements; the repository does not treat the pitch figure as an established negative growth rate.
- **Shopping example:** The proposed example returns product P0019 at store S04 for a jacket under €80 with 3 units. The supplied inventory sample lists P0019/S04 at €120.39 with stock 43. The example is illustrative, not a query result reproduced from that sample.
- **Sentiment example:** The walkthrough describes 37 reviews in 48 hours, 28 negative classifications, and an average rating of 2.1. The supplied review file has 20 rows total and no model-produced sentiment field. Those figures are a scenario, not observed analysis of the provided CSV.
- **Field names:** Some use cases use conceptual names that differ from the supplied CSV headers. Examples are listed below; any implementation would need an explicit mapping or revised schema.

| Report term | Supplied sample header |
| --- | --- |
| `weather_condition` | `weather` |
| `total_daily_sales` | `total_sales` |
| `current_price` | `price` |
| `stock_count` | `stock` |
| `review_text` | `text` |
| `star_rating` | `rating` |

The course brief also describes a web-metrics dataset, but no web-metrics CSV is present. Forecasting and pricing workflows therefore cannot be reproduced from the available samples.

## Original sources and excluded materials

The proposal is based on IE Business School's *Group Work – Option B: Cloud Data Platform for Retail*. The handout describes Manga as a fictional scenario inspired by a Mango cloud migration and identifies its CSV samples as synthetic. The report's Appendix C preserves the team's references; Appendix A preserves the original AI-use acknowledgement.

The course handout and six course-provided CSVs are retained locally but excluded from publication because no redistribution license is supplied. The customer and shipping samples contain name/address-like fields; they should not be shared without their synthetic-data context and confirmed permission.

A separate 18-slide detailed RFP deck is retained locally and excluded because its cover is marked **CONFIDENTIAL**. Its status must be clarified before sharing it. The architecture previews published here come from the shorter pitch deck, not that excluded file.

## Credits and rights

Appendix B is the source for the contributor table in the README. No contributor profile links or full name for Nicolas were supplied. No Git repository or commit history was found in the original folder or its subdirectories. There is no history to migrate, and the contribution table should not be mistaken for commit-level authorship.

No reuse license has been inferred. The availability of local copies does not establish public redistribution rights for the group work, course materials, logos, or diagrams. Confirm the appropriate sharing permissions before uploading the selected deliverables.
