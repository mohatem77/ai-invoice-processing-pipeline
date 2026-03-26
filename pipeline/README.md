
# Pipeline Flow

## Stage 1 – Document Ingestion
Invoices are received through upload, email attachment, or API input.

## Stage 2 – Pre-Processing
The document is prepared for extraction through image clean-up, formatting checks, and file normalization.

## Stage 3 – OCR / Text Capture
Invoice text is extracted from the source document.

## Stage 4 – Structured Field Extraction
The system identifies and maps fields such as:
- supplier name
- invoice number
- invoice date
- amounts
- VAT
- line items

## Stage 5 – Validation
Extracted data is checked for:
- missing fields
- suspicious values
- formatting issues
- duplicate invoice risk

## Stage 6 – Output Generation
The final output is transformed into a structured JSON object suitable for review or ERP integration.

## Purpose

The purpose of this pipeline is to support finance automation by reducing manual invoice entry and creating ERP-ready structured outputs.
