# ProcureSight

ProcureSight automates the extraction, normalization, and analysis of supplier quotes from messy PDFs and Excel files, enabling SMB procurement teams to save hours on data cleaning, track historical pricing trends, and make informed negotiation decisions.[web:26]

## Product Vision
SMB procurement managers currently spend 30% of their time manually extracting line items from inconsistent supplier formats, leading to pricing errors, missed savings opportunities, and apples-to-apples comparison failures.[web:26] ProcureSight solves this by providing instant normalization, anomaly detection, and price intelligence across freight, warehousing, and component quotes.

## Target Users
- Procurement managers at SMB manufacturers and distributors (10-200 employees)
- Logistics coordinators handling supplier RFQs
- Purchasing teams in e-commerce fulfillment operations
- Operations leads tracking vendor pricing trends

## Problem Statement
Supplier quotes arrive in chaotic formats: lane-based freight PDFs, custom accessorial Excel exports, ERP dumps with hidden fees. Manual normalization consumes 30% of procurement hours, risks overlooking detention/FSC charges, and prevents historical trend analysis.[web:26] Existing OCR tools fail on structured pricing tables, while enterprise procurement suites cost $50K+/year and require IT setup.

## Core Value Proposition
Transform procurement from data drudgery to strategic intelligence. Unlock 20-30% cost savings through better negotiations, reduce quote processing time from hours to minutes, and build vendor scorecards without spreadsheets.[web:26]

## Functional Requirements

### Quote Ingestion and Extraction
- Upload PDF/Excel/scan quotes via drag-drop or email forwarding
- Extract line items, pricing, quantities, accessorials (FSC, detention, etc.)
- Handle lane-based freight structures and custom fields
- 99% accuracy on structured tables via specialized parsing

### Normalization and Standardization
- Convert disparate formats to unified schema (product, price/unit, total, terms)
- Map supplier-specific jargon to standard categories
- Flag inconsistencies (missing taxes, currency mismatches)
- Support 50+ freight/warehousing quote templates

### Price Intelligence and Trends
- Track historical pricing per supplier/product/lane
- Generate trend charts and benchmarks vs market averages
- Detect anomalies (sudden hikes, below-cost outliers)
- Predictive pricing based on volume/commitment patterns

### Comparison and Decision Support
- Side-by-side quote comparisons with normalized data
- Total cost of ownership calculator (freight + accessorials)
- Vendor scoring based on price reliability, speed, terms
- Negotiation playbook with leverage points highlighted

### Reporting and Export
- Custom dashboards for procurement KPIs
- PDF/Excel exports for stakeholder reviews
- API access for ERP integration (future)
- Audit trail of all extractions and analyses

## User Experience Requirements
- Process single quote in under 60 seconds
- Mobile upload and review for field teams
- Collaborative commenting on quotes
- Template library for common suppliers

## Constraints
- Focused on freight/warehousing/procurement quotes (not invoices)
- Max 500 quotes/month on starter plan
- No custom supplier template building
- English-only document processing

## Success Criteria
- 80% time savings on quote processing
- 15% average procurement cost reduction
- 90% extraction accuracy
- 4.5+ stars user rating

## Monetization
- Freemium: 10 quotes/month free
- Pro: $49/mo 100 quotes, trends
- Business: $199/mo unlimited, teams, benchmarks
- Enterprise: Custom volume pricing

Value-based: Charge per quote processed or % savings unlocked.