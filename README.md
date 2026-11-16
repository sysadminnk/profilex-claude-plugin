# ProfileX for Claude

Connects Claude and Claude Code to the ProfileX MCP server so you can find the KYC
verification services enabled on your ProfileX account, check the inputs each one needs, and
run them. You sign in with your
own ProfileX account in the browser; Claude never sees your password or API keys. Results
are returned in full, the same as the ProfileX REST API.
Verifications are billed to your ProfileX account (UAT calls use free UAT pulls).

On a headless Linux server: `ssh -t server 'claude mcp login profilex --no-browser'`, open
the printed URL on any device, sign in, and paste the final URL back.

Support: support@neokred.tech · Privacy: https://www.neokred.tech/privacy-policy
