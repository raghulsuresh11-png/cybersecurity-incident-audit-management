# Strategic Cybersecurity Incident & Audit Management: A CRM-Driven Approach with Salesforce and Power BI Analytics
A CRM-driven cybersecurity operations project built with Salesforce and Power BI to manage client accounts, security incidents, audit records and performance reporting in a centralized analytics workflow.

## Overview
This project was developed to address fragmented cybersecurity operations caused by solid data entry, spreadsheet-based incident tracking, informal audit records and limited reporting transparency. The solution combines Salesforce CRM for structured operational data management with Power BI for dynamic dashboards and decision support.

## Business Objective
The objective of this project is to create a centralized CRM-BI system for cybersecurity incident and audit management that improves traceability, reporting, risk visibility and operational decision-making.

## Solution Architecture
The system uses Salesforce as the core data platform and Power BI as the business intelligence layer.

### Salesforce Components
- Standard **Account** object for client companies
- Custom **CyberSec_Incidents** object for incident logging and tracking
- Custom **Security_Audit** object for audit records, risk values and recommendations
- Lookup relationships to maintain referential integrity across clients, incidents and audits

### Power BI Components
- Incident resolution KPI dashboards
- Attack trend analysis
- Audit risk reporting
- Consultant activity and workload monitoring
- Operational and management-level reporting views

## Key Features
- Centralized management of cybersecurity incidents and audits
- Structured client-linked data model using Salesforce relationships
- Improved incident traceability and audit readiness
- Dynamic Power BI dashboards for performance and risk monitoring
- Data validation using SOQL queries in Salesforce
- Bulk record handling and process improvement using Apex-based automation

## Development Highlights
During implementation, the project addressed practical CRM deployment challenges including failed manual imports, mismatched lookup references, invalid picklist values and date-format issues. To improve reliability, the workflow was extended with Apex-based record insertion and update logic, SOQL-based validation, and improved lookup and picklist consistency.

The final solution established a scalable CRM-BI framework capable of supporting cybersecurity service operations with stronger visibility, better data integrity, and more effective reporting.

## Tools and Technologies
- Salesforce CRM
- Power BI
- Apex
- SOQL
- Salesforce Developer Console
- Data Loader / Import utilities
- Mockaroo

## Repository Contents
- Project report / specification report
- Implementation report
- Power BI dashboard files
- Supporting documentation and assets

## Outcome
This project demonstrates how CRM and BI can be integrated to support cybersecurity incident handling and audit management through a structured, data-driven workflow. The resulting system improves compliance posture, operational transparency and risk-focused decision support.

## Author
**Raghul Sureshbabu**
