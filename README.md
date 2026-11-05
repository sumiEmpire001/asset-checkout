# Asset Checkout

A responsive HTML/CSS/JavaScript equipment checkout ledger. Add assets, search inventory, assign equipment to a borrower, and record returns. Duplicate IDs and double checkouts are rejected.

## Run

Start `python -m http.server 8000` and visit http://localhost:8000. Browser ES modules require serving files over HTTP.

## Test

Requires Node.js 18+. Run `npm test`. CI runs eight tests on GitHub Actions.

## Scope

Records are saved in localStorage in one browser. There is no user authentication, audit trail, shared database, or multi-user locking. Use only as a prototype, not a production asset register.
