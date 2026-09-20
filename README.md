# contract-2026

> **Lifecycle: SENSITIVE OPERATIONAL WORKFLOW — disruptive changes require runtime confirmation**

This public repository contains the 2026 labor-contract signing page used by 睿思有限公司.

## Sensitive-data boundary

The current page asks the signer for personal information including name, national ID number, address, bank account details, and an electronic signature. It generates a PDF in the browser and submits that PDF to an external Google Apps Script endpoint.

## Maintenance boundary

- Treat this as a sensitive operational workflow, not a generic static demo.
- Do not change repository visibility, hosting, the submission endpoint, or the signing flow without first confirming the currently used production URL and workflow.
- Do not commit completed contracts, signer data, generated PDFs, credentials, or other personal data to Git.
- Public repository visibility does **not** prove that public access is the intended long-term security model; review that separately before changing deployment.
- Keep code changes minimal and preserve a rollback path.

This README documents the repository role only; it does not claim that the live signing workflow was UAT-tested during this audit.
