# CXH AUTO (车小花) — China New & Used Car Price Trends

Query China’s new- and used-car market prices and available historical price trends through a compatible AI agent. Compare region- and configuration-specific observations, keeping wholesale quotes, retail asking prices and guide prices separate.

Brand website: [CXH AUTO](https://cxhauto.com/).

International setup page: [AI / MCP — China car price trends](https://cxhauto.com/mcp?lang=en), with a copyable service URL, configuration and example prompt. [Information for AI assistants](https://cxhauto.com/llms.txt).

**Public beta.** Open the setup page for your client. [WorkBuddy](https://www.cxhcf.com/mcp/workbuddy) · [Qwen Work](https://clue.cxhcf.com/localCarBusinessIntranet/quotesWeb/connect.html?client=qwenwork) · [Doubao Work](https://clue.cxhcf.com/localCarBusinessIntranet/quotesWeb/connect.html?client=doubaowork) · [Search in your browser](https://clue.cxhcf.com/localCarBusinessIntranet/quotesWeb/cards.html) · [中文](README.md)

Remote MCP endpoint (Streamable HTTP):

https://clue.cxhcf.com/localCarBusinessIntranet/quotesWeb/mcp

Listed in the **official MCP Registry** as `io.github.leo2026888/cxhauto-car-prices`: [read the public registry record](https://registry.modelcontextprotocol.io/v0.1/servers/io.github.leo2026888%2Fcxhauto-car-prices/versions/latest). Clients that consume this registry can discover the remote service; connect using the Streamable HTTP endpoint above. Each platform's own marketplace approval and client compatibility are verified separately.

After importing and enabling the connector, submit the query below in your client. Other clients with remote MCP support can add the Streamable HTTP endpoint manually.

## Continue with your existing membership

In the original chat, ask “Use CXH AUTO to check my account and membership. If my account can make queries, continue with the same vehicle and filters.” If the connector still shows guest access, use the account setup for the client you were using. [WorkBuddy](https://www.cxhcf.com/mcp/workbuddy) · [Qwen Work](https://clue.cxhcf.com/localCarBusinessIntranet/quotesWeb/connect.html?client=qwenwork#account) · [Doubao Work](https://clue.cxhcf.com/localCarBusinessIntranet/quotesWeb/connect.html?client=doubaowork#account). If manual setup is needed, update the existing CXH AUTO connection. After authorizing it, return to the original chat and rely on the entitlement returned by get_access_status.

## First vehicle query

- New car: “Use CXH AUTO to compare dealer offers and the guide price for a new 2027 Toyota Camry 2.0E Elite in Nanjing over the past seven days. Include dates and offer conditions.”
- Used car: “Use CXH AUTO to look up seven days of quotes for a used 2023 BMW 530Li in Hangzhou. List wholesale and retail asking prices separately, and let me choose the trim. If the exact criteria yield no quotes, label any supported comparison with the differences.”

The [Skill](skills/cxh-car-quotes/SKILL.md) supplies usage instructions. Establishing the MCP connection is a separate step. First-time guests have a limited trial; allowance and membership are reported by the service. Client compatibility and post-login membership continuity are still being tested in some clients.

Market data is compiled and provided by CXH AUTO. Quote dates, observation dates, geographic scope and applicable terms are shown where available. Quoted prices are for comparison. Confirm actual transaction prices and vehicle availability separately. Demonstration charts do not establish forecasting accuracy.

This repository publishes documentation and the public connection address only. It does not publish application code, automation programs, credentials, server configuration, account information or a quotation database.
