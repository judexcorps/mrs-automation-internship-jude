\# Week 0: Setup



\## 1. Explanation

\- Problem: set up a working automation environment for the internship.

\- Solution: n8n running locally with Node.js, Google connected, accounts ready, public GitHub repo.



\## 2. Implementation

\- n8n runs locally via Node.js (npm) at localhost:5678, not Docker.

\- Google Sheets and Gmail OAuth credentials connected.

\- Test workflow "Task 00": Manual Trigger → Google Sheets (Get Row(s)) → Edit Fields.

\- Accounts: GitHub, Make, Zapier, Telegram bot, Gemini API.



\## 3. Documentation

| Test | Expected | Actual | Pass |

|---|---|---|---|

| Get Row(s) | 3 rows from test sheet | 3 rows returned | Yes |

| Restart n8n | Saved workflow still there | \[fill after test] | \[ ] |



\- Problem: Docker would not install on my laptop.

\- Fix: ran n8n with Node.js instead; proved persistence by restarting n8n.

\- Limits: n8n runs only while my laptop is on.

