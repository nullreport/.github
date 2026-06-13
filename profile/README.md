<div align="center">

# NullReport

**Write penetration testing reports faster with AI, fully self-hosted.**

[Website](https://nullreport.app) · [Documentation](https://docs.nullreport.app) · [Customer portal](https://portal.nullreport.app)

<br>

<img src="https://raw.githubusercontent.com/nullreport/.github/main/profile/assets/demo.webp" alt="NullReport report editor: clicking AI opens the Generate menu and writes a finding" width="720">

</div>

---

NullReport is a report generator for security teams. You write findings, organize them into reports, and export polished DOCX deliverables, all on your own infrastructure. On Pro, an AI assistant drafts and polishes finding text using the model you choose, including a local one so your draft text can stay on your network. The free tier runs entirely on a machine you control, and none of your engagement data ever leaves it.

## Install

Run one line on the server where you want to host it:

```sh
curl -fsSL https://raw.githubusercontent.com/nullreport/install/main/install.sh | sh
```

The installer pulls prebuilt Docker images and brings the app up with a single command. The full walkthrough, including prerequisites and verification, lives in the [documentation](https://docs.nullreport.app).

## What you get

- A reusable finding library so you stop rewriting the same writeups every engagement.
- Per-report dynamic fields. Every engagement is different, so each report lets you define your own named fields once, whether that is a client contact, an assessment window, or a custom risk rating, and reference them anywhere in your template. The export fills them in for you.
- One-click export to a polished Word (DOCX) document.
- Finding and report templates with a simple placeholder syntax. Custom report templates are a Pro feature.
- **AI assistance (Pro):** drafts and polishes findings with the provider you choose. Point it at a local model and nothing leaves your network, or connect OpenAI, Anthropic, or Gemini if you prefer.
- **Team collaboration (Team):** multiple users with roles and permissions, a shared finding library, and audit logs.
- An optional [Model Context Protocol server](https://github.com/nullreport/mcp) that lets an AI client like Claude or Cursor drive your instance in natural language.

---

<div align="center">

## Help shape NullReport

**Built for penetration testers, by listening to them.** Want a feature, or hit a bug? Tell us, it shapes what gets built next.

### [Request a feature](https://github.com/nullreport/feedback/issues/new?template=feature_request.md) &nbsp;·&nbsp; [Report a bug](https://github.com/nullreport/feedback/issues/new?template=bug_report.md) &nbsp;·&nbsp; [Browse and upvote ideas](https://github.com/nullreport/feedback)

</div>

---

## Pricing

| Tier | Price | Includes |
|---|---|---|
| **Free** | $0 | Unlimited reports, finding library, dynamic fields, and DOCX export. One user, fully self-hosted. |
| **Pro** | $39 / month | Everything in Free, plus AI assistance, custom report templates, and priority support. One user. |
| **Team** | $99 / month | Everything in Pro, plus collaboration for multiple users, a shared finding library, and audit logs. Three seats included, thirty dollars per extra seat. |

See [nullreport.app](https://nullreport.app) for the full feature comparison.

## Open repositories

The application source is commercial and stays private. The pieces you run on your own machine are open so you can read exactly what they do before you trust them:

- [**install**](https://github.com/nullreport/install) — the installer, update script, and Docker Compose files.
- [**mcp**](https://github.com/nullreport/mcp) — the local MCP server, published to npm as `nullreport-mcp`.

## Feedback and support

Bugs and feature requests go to the **[feedback tracker](https://github.com/nullreport/feedback)**: open an issue or upvote an existing one. For help, licensing, billing, or anything private, email **support@nullreport.app**. Documentation is at [docs.nullreport.app](https://docs.nullreport.app).
