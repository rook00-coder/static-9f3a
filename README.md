# solid

Synthetic HTML fixtures for an authorized Microsoft Copilot Bounty evaluation.
No personal data, credentials, or production code.

- `control.html` — benign page.
- `payload.html` — the same visible content with a prose reference that points
  at a disposable canary webhook.
- `index.html` — links to both.

These pages are public so the evaluation target can fetch them. The payload
contains a canary URL, not a credential, and the canary expires.
