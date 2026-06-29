# Payer Reimbursement Validator

Static Vercel version. No backend, API routes, Python files, environment variables, or database are required.

## Deploy Files

Upload only these files to GitHub:

- `index.html`
- `vercel.json`
- `README.md`

## How Data Works

The app stores approved reimbursement reference data in the browser where it is used.

Recommended workflow:

1. Open the deployed app.
2. Upload the Q1 CPT Intelligence workbook.
3. Preview and approve the payer/CPT reimbursement ranges.
4. Click **Export approved reference**.
5. Send the exported JSON file to VAs.
6. VAs open the app and use **Import reference JSON** once.

This avoids server setup and keeps the first shared version simple.
