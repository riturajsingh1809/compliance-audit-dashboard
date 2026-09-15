# Compliance Audit & Data Governance Dashboard

## Overview

This project focuses on building a compliance-focused analytics solution for monitoring consent, data retention, deletion status, downstream extract exposure, and audit compliance.

The objective is to make compliance data easier to monitor and provide clear, audit-ready business insights.

## Project Workflow

*Excel Data Cleaning → Python Data Analysis → Tableau Dashboard → GitHub Documentation*

## Data Preparation

The sample dataset was cleaned and validated in *Microsoft Excel*.

The cleaning process included:

* Removing duplicate records
* Handling missing values
* Standardizing text and status values
* Validating date fields
* Validating numerical fields
* Checking record and customer identifiers
* Preparing the final dataset for analysis

Python and Google Colab were used for analysis after the Excel cleaning process.

## Analysis

Python was used to analyze:

* Consent status and consent rate
* Records without granted consent
* Revoked consent records
* Retention status
* Pending and deleted records
* Extract exposure
* Audit compliance
* Region-wise compliance
* Purpose-wise compliance
* Data-source performance

## Tableau Dashboard

The final Tableau dashboard provides a consolidated view of:

* Consent Overview
* Retention Status
* Deletion Monitoring
* Extract Exposure
* Audit Compliance
* Regional Compliance

Interactive filters allow users to explore compliance information by region, purpose, and data source.

## Key Business Value

The dashboard helps identify:

* Records without valid consent
* Retention-expired records
* Pending deletion records
* Records still present in downstream extracts
* Compliance issues requiring review

This supports better data governance, compliance monitoring, and audit readiness.

## Tools Used

* Microsoft Excel
* Python
* Pandas
* Google Colab
* Tableau
* GitHub

## Conclusion

The project demonstrates an end-to-end compliance analytics workflow where data is cleaned in Excel, analyzed using Python, and presented through an interactive Tableau dashboard for business and audit-focused decision-making.
