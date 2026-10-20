# Power BI Dashboards

Vendor performance dashboards built in Power BI Desktop and exported to PDF. Each report gives a quarterly (January to March 2024) review of one supplier, covering purchases, returns, stock status, back orders, order projections, quality issues and meeting action items. The repository contains the PDF exports only; the source `.pbix` files are not included.

## What's inside

| File | Pages | Size | Contents |
| --- | --- | --- | --- |
| [Vendor Dashboard_Bikaner Handloom.pdf](Vendor%20Dashboard_Bikaner%20Handloom.pdf) | 13 | 8.2 MB | Vendor review for Bikaner Handloom |
| [Vendor Dashboard_Jaipur Rugs.pdf](Vendor%20Dashboard_Jaipur%20Rugs.pdf) | 12 | 2.4 MB | Vendor review for Jaipur Rugs |

## Report pages

Both reports follow the same layout (the Bikaner Handloom export has one extra leading page):

1. **Business Overview (Jan - March '24)** - KPI cards for Total Purchase YTD, Purchased Billed YoY %, Returns YTD and Return Rate; a yearly Purchase History chart (2016-2024); Stock Status split (In Stock / In Transit / OOS); YTD Shipped vs Open Orders.
2. **SKU Count and Stock Status** - SKU count by program (Launch, Program, Last Call, Launch 2023, Launch 2024); stock status by item category; new product launch update by season; stock status by velocity code; SKU, collection and lead-time table by item type and construction; Inventory Turn; Open Order value; Q1 placed orders compared year over year.
3. **In Stock Status by Velocity Code A & B** - program and swatch SKU breakdowns for velocity codes A and B.
4. **OOS Designs** - out-of-stock designs and top-selling OOS items by velocity code.
5. **Back Order Details** - SKUs by construction and back-order delay days.
6. **Order Projections** - projected orders for April to July by construction, with PO status.
7. **Quality Issues and Chargebacks (Jan-Mar '24)** - quality return reasons YTD with images.
8. **Top 10 SKUs by COGS**.
9. **Action items (Last Meeting)** - follow-ups from the previous vendor meeting.
10. **Opportunities** - meeting notes and action items.
11. **Thank You** closing page.

## Tools used

- Power BI Desktop (report authoring and PDF export)

## How to open

Open either PDF in any PDF viewer or directly on GitHub. To edit the reports, the original `.pbix` files would need to be added to this repository and opened in Power BI Desktop.

## Repository structure

```text
PowerBI_Dashoards/
├── README.md
├── Vendor Dashboard_Bikaner Handloom.pdf
└── Vendor Dashboard_Jaipur Rugs.pdf
```
