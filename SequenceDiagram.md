```mermaid
sequenceDiagram
  participant login
  participant verifier
  participant database
  login ->> verifier: Enter credentials
  verifier ->> database: Verify credentials
  database ->> verifier: Credentials verified
  verifier ->> login: Login acknowledgement
```
