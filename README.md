# Phil Cheesman

**Founder @ [SIOP360](https://www.siop360.com)** — AI-native supply chain intelligence for mid-market manufacturers.

Purdue Industrial Engineer turned technical founder. Spent my career in manufacturing operations — production planning, procurement, inventory management, ERP implementations — writing the tools I couldn't find on the market along the way.

---

### What I'm Building

**[SIOP360](https://www.siop360.com)** is a full-stack B2B SaaS platform that transforms ERP data into actionable supply chain intelligence. Supply chain professionals spend over half of their working hours flipping through ERP screens. We cut that by 70%.

<table>
<tr><td><b>Platform</b></td><td>React 18 + TypeScript, Node/Express, PostgreSQL 17 with row-level security, Redis, Cube.js semantic layer, dbt ELT pipeline</td></tr>
<tr><td><b>Data</b></td><td>ERP-agnostic ingestion → dbt model → pre-built intelligence reports (shortage tracking, demand analysis, vendor performance, ABC classification)</td></tr>
<tr><td><b>AI Layer</b></td><td>Natural-language view builder, conversational supply position analysis, AI-powered vendor communication</td></tr>
<tr><td><b>Infra</b></td><td>Multi-tenant SaaS on Vercel + Railway + Neon. Row-level security at DB level, JWT + RBAC auth, Azure AD SSO</td></tr>
</table>

**Repos:** `SIOP360/siop360-app` · `SIOP360/siop360-ops` · `SIOP360/siop360-site` · `SIOP360/siop360-remotion`

---

### Prior Work — Manufacturing Supply Chain / ERP

The domain expertise behind SIOP360 comes from years of building internal tools across different manufacturing environments. These ranged from complex SQL, M, and DAX-driven analytics in traditional BI tools (Power BI, Tableau, DOMO) to full data pipeline and migration scripts:

- **Production scheduling** — ERP-agnostic finite-capacity scheduler
- **MRP & inventory optimization** — obsolete/excess analysis, PO expediting, ABC classification (SQL/Python)
- **ERP migration** — IBM AS/400 data extraction and transformation tooling (SQL/Python)
- **S&OP analytics** — NetSuite SIOP planning dashboards with multi-level DAX measures (Power BI / SQL / M / DAX)
- **Procurement automation** — rules-based PO generation and vendor scoring (Python → TypeScript)
- **Engineering document pipelines** — batch DWG-to-PDF conversion for manufacturing drawing packages (Python)
- **BOM & routing analytics** — work order costing, routing efficiency, and bill-of-material reporting (SQL / Power BI)

---

### Developer Tools & Open Source

| Repo | What It Does | |
|------|-------------|---|
| [`claude-parallel-sessions`](https://github.com/phil-cheesman/claude-parallel-sessions) | Run 4+ Claude Code agents in parallel on the same codebase with per-session file tracking and clean commits | Python · ⭐ 6 |
| `mcp-odbc` | MCP Server for connecting AI agents to any ERP/database via ODBC | Python |

`claude-parallel-sessions` came out of running Claude Code daily for 6+ months to build SIOP360. It uses hooks to track file changes per session, parses sub-agent work, and generates clean attributed commits — no worktrees needed.

---

### Side Projects

| Repo | What It Does |
|------|-------------|
| `personal-finance-bi` | Data pipeline + analytics across 10+ years of personal financial transactions |
| `project-cheddar` | Personal finance web app with automated categorization and reporting |

---

**Currently:** Phoenix, AZ · [siop360.com](https://www.siop360.com) · [LinkedIn](https://www.linkedin.com/in/phillipcheesman)
