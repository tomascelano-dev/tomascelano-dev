# Hi, I'm Tomas Celano 👋

**Backend Developer · Automation & AI.**
I build APIs, internal tools and AI integrations with .NET and Python, mostly for small businesses
that run on WhatsApp and spreadsheets. My usual pattern: a model reads the messy input, tested code
makes the decisions.

🌐 **Portfolio:** [tomas.techxto.ar](https://tomas.techxto.ar)

---

## 🚀 Featured projects

### RepairShop Management System
Full-stack internal management system for repair shops: customers, devices,
repair orders, inventory, payments, status history and message templates.

`.NET 8` · `PostgreSQL` · `EF Core` · `React + TypeScript` · `Docker` · `Clean Architecture` · `JWT`

🔗 [Live app](https://app.techxto.ar) · 📦 [Repository](https://github.com/tomascelano-dev/repair-shop-management-system)

### precios-mcp
Multi-tenant service that turns messy wholesale supplier lists into WhatsApp price lists with each
store's markup. One core behind two doors: a REST API for n8n and an MCP server, so Claude can use it
as tools. Claude only structures the list; every price comes from deterministic code with 23 tests,
including integration tests against PostgreSQL.

`Python` · `FastAPI` · `MCP SDK 2.x` · `PostgreSQL` · `pytest` · `GitHub Actions` · `Docker`

📦 [Repository](https://github.com/tomascelano-dev/precios-mcp)

### LeadPipeline · _ran in production_
Lead-capture and CRM engine for businesses that sell and support over WhatsApp
and Instagram. It ingests every inbound message, auto-classifies intent and
lead status, schedules follow-ups, and reports purchase conversions back to
Meta Ads with ad attribution.

`.NET 8` · `Clean Architecture` · `Hangfire` · `Meta Webhooks (HMAC-256)` · `Meta Conversions API` · `PostgreSQL` · `EF Core + Dapper` · `Docker / VPS`

> Ran in production for a real business. The source is private (Meta tokens,
> secrets and customer data); the case study is on my [portfolio](https://tomas.techxto.ar).

More on the portfolio: the Python toolchain behind a phone retailer's online store, and a subtitle-plan
generator (faster-whisper + OpenCV) that I use on client work for a video agency.

---

## 🛠️ Tech I work with

- **Backend:** C# / .NET 8, ASP.NET Core, Python, FastAPI, PostgreSQL, EF Core, Dapper, Hangfire
- **AI:** MCP servers, Claude / Anthropic API, faster-whisper, LLM tool design
- **Frontend:** React, TypeScript, Vite
- **Infra:** Docker, Linux VPS, Cloudflare, GitHub Actions, n8n
- **Integrations:** Meta APIs (WhatsApp Cloud, Conversions API), webhooks, WooCommerce

---

## 📫 Contact

[Portfolio](https://tomas.techxto.ar) ·
[LinkedIn](https://www.linkedin.com/in/tomas-celano-coronel-891668195/) ·
[Email](mailto:tomasgabrielcelano@gmail.com)
