<div align="center">

# BUG BOUNTY

Security findings, reports and responsible disclosures.

---

<details>
<summary><strong>Sentry.cv — Public API Key / Rate Limiting</strong></summary>

<br>

**Year:** 2026  
**Status:** Informational / Not accepted  
**Type:** API Security

### FINDING

During testing, I identified an API key exposed on the client side and an endpoint that appeared to lack rate limiting.

This initially appeared capable of generating a large number of requests and potentially causing resource exhaustion.

### RESPONSE

I responsibly reported the issue to Sentry.cv.

The report was not considered a valid vulnerability because the API key was intended to be publicly accessible.

### WHAT I LEARNED

`API Security` `Rate Limiting` `Public API Keys` `Responsible Disclosure` `Bug Bounty Triage`

</details>
