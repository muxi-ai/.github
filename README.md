<h1 align="center">
  <img alt="MUXI" height="72" src="https://github.com/muxi-ai/muxi/raw/main/assets/muxi-wordmark.svg"><br>
  Deploy Intelligence
</h1>

<p align="center">The Open-source AI Application Server.<br>Not a framework. Not a wrapper. <u><strong>A server</strong></u>.</p>

<p align="center">
  <a href="https://muxi.org/docs"><img src="https://img.shields.io/badge/Docs-muxi.org-c98b45.svg" alt="Docs" height="20"></a>&nbsp;
  <a href="https://twitter.com/muxi_ai"><img height="20" src="https://github.com/muxi-ai/muxi/raw/main/assets/badge-twitter.svg" alt="X/Twitter"></a>&nbsp;
  <a href="https://linkedin.com/company/muxi-ai"><img height="20" src="https://github.com/muxi-ai/muxi/raw/main/assets/badge-linkedin.svg" alt="LinkedIn"></a>
  <!-- &nbsp;
  <a href="https://github.com/sponsors/muxi-ai"><img src="https://img.shields.io/badge/Sponsor-❤-ea4aaa" alt="Sponsor"></a>&nbsp;
  <a href="https://github.com/muxi-ai/muxi"><img src="https://img.shields.io/github/stars/muxi-ai/muxi?style=social&label=Stars" alt="GitHub stars"></a> -->
</p>

<p align="center">
  <a href="https://muxi.org/docs/quickstart">Quickstart</a> ·
  <a href="https://muxi.org/docs">Docs</a> ·
  <a href="https://agentformation.org">Agent Formation Schema</a> ·
  <a href="https://github.com/muxi-ai/muxi/discussions">Community</a> ·
  <a href="https://github.com/orgs/muxi-ai/projects/1">Roadmap</a>
</p>

---

<!-- TODO: Replace with terminal recording (asciinema/svg-term or ttygif, ~10-15s, ~800px width) -->
<!-- Recommended flow: muxi pull @muxi/hello-world -> muxi deploy -> muxi chat hello-world 
<p align="center">
  <a href="https://muxi.org/#hero-demo-video"><img src="https://github.com/muxi-ai/muxi/raw/main/assets/demo.gif" alt="MUXI Demo" width="800"></a>
</p>
-->

No one builds their own Nginx to deploy a website. No one should reinvent infrastructure to build AI.

MUXI (`/ˈmʌk.siː/`) is **production infrastructure for AI agents** -- where agents are native primitives with built-in orchestration, memory, observability, and scale.

| Concept | Docker | MUXI |
|---------|--------|------|
| **Engine** | Docker Engine | Server + Runtime |
| **Definition** | Dockerfile | Formation |
| **Registry** | Docker Hub | MUXI Registry |
| **CLI** | `docker` | `muxi` |

```bash
brew install muxi-ai/tap/muxi                        # macOS
curl -fsSL https://muxi.org/install | sudo bash      # Linux
powershell -c "irm https://muxi.org/install | iex"   # Windows
```

```bash
muxi pull @muxi/hello-world   # pull a formation
muxi deploy                   # deploy it
muxi chat hello-world         # talk to it
```

**That's it.** Your agent is running, stateful, and accessible via API.

---

## What You Get

- **Declarative agents** – `.afs` files, version-controlled, auto-discovered. [Docs](https://muxi.org/docs/concepts/agents-and-orchestration)
- **Three-tier memory** – buffer, persistent, and semantic memory built in. [Docs](https://muxi.org/docs/concepts/memory-system)
- **1,000+ MCP tools** – GitHub, Slack, Stripe, databases, and more. [Docs](https://muxi.org/docs/concepts/tools-and-mcp)
- **Multi-tenant** – per-user isolation, RBAC, OAuth. [Docs](https://muxi.org/docs/concepts/multi-tenancy)
- **Observability** – 349 event types, real-time streaming, 10+ export targets. [Docs](https://muxi.org/docs/concepts/observability)
- **Intelligent orchestration** – Overlord routes to specialists, decomposes tasks. [Docs](https://muxi.org/docs/concepts/overlord)
- **Async processing** – triggers, webhooks, scheduled tasks. [Docs](https://muxi.org/docs/concepts/async)
- **Any LLM** – 21 providers, 300+ models, no lock-in. [Docs](https://muxi.org/docs/concepts/llm-providers)

> MUXI implements the [**Agent Formation Standard**](https://github.com/agent-formation) – an open spec for declarative AI agents.

---

## Our Creed

> [!IMPORTANT]
> **AI infrastructure should be open, not owned by big tech.**
> - **Self-hostable** – Run anywhere, owned by you
> - **Observable** – See what's happening, always
> - **Declarative** – Version-controlled and reproducible
> - **Open** – No secrets, no lock-in
>
> If you build it, you should control it.

---

## Repositories

| Repo | Description |
|------|-------------|
| [muxi](https://github.com/muxi-ai/muxi) | The meta repo |
| [server](https://github.com/muxi-ai/server) | The AI Server |
| [cli](https://github.com/muxi-ai/cli) | Command-line interface |
| [sdks](https://github.com/muxi-ai/sdks) | 12 SDKs: Python, TypeScript, Go, Swift, Java, and more |

---

<p align="center">
  <strong>MUXI</strong> = <strong>Mu</strong>ltiplexed e<strong>X</strong>tensible <strong>I</strong>ntelligence<br>
  Built by <a href="https://x.com/aroussi">@aroussi</a>, author of <a href="http://productionaibook.com"><strong>Production-Grade Agentic AI</strong></a> (665 pages)
</p>

<p align="center">
  <sub>For AI/LLM agents: <a href="https://muxi.org/llms.txt">muxi.org/llms.txt</a></sub>
</p>
