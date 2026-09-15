<p align="center">
  <a href="https://langbot.app">
    <img width="130" src="https://raw.githubusercontent.com/langbot-app/.github/main/profile/assets/logo-blue.png" alt="LangBot"/>
  </a>
</p>

<h3 align="center">Build AI agents for the messaging platforms your users already use.</h3>

<p align="center">
  <a href="https://github.com/langbot-app/LangBot"><img src="https://img.shields.io/github/stars/langbot-app/LangBot?style=social" alt="GitHub Stars"></a>
  <a href="https://github.com/langbot-app/LangBot/releases/latest"><img src="https://img.shields.io/github/v/release/langbot-app/LangBot" alt="Release"></a>
  <a href="https://discord.gg/wdNEHETs87"><img src="https://img.shields.io/discord/1335141740050649118?logo=discord&label=Discord&color=%235462eb" alt="Discord"></a>
</p>

---

**[LangBot](https://github.com/langbot-app/LangBot)** is an open-source platform for building and running AI agents across **Discord, Telegram, Slack, LINE, WeChat, QQ, Lark, DingTalk** and more. Connect your preferred models, knowledge bases, and tools to create support assistants, automate team workflows, or help manage your community — all from one web dashboard.

<p align="center">
  <img src="https://raw.githubusercontent.com/langbot-app/LangBot/master/res/dashboard-overview.png" alt="LangBot web dashboard showing message traffic, model calls, active sessions, and runtime status" width="720"/>
</p>

### Highlights

- **Agents that do more than chat** — Multi-turn conversations, tool calling, multimodal input, and a code sandbox for working with files and running tasks.
- **Your models and workflows** — Use OpenAI, Anthropic, Gemini, DeepSeek, or local models with Ollama. Connect existing applications built with Dify, Coze, n8n, and Langflow.
- **Knowledge-backed answers** — Bring your documents into conversations with built-in RAG and external knowledge-base integrations.
- **An extensible toolkit** — Add plugins, MCP servers, and skills from the [extension marketplace](https://space.langbot.app/market), or build your own.
- **One place to manage your bots** — Configure bots and pipelines, collaborate with teammates, manage access, and monitor conversations and model usage through the web dashboard.

### Get Started

#### LangBot Cloud (Recommended)

**[Get started with LangBot Cloud →](https://cloud.langbot.app)**

Build and manage your bots online without deploying or maintaining a server.

#### Self-host with uvx

Install [uv](https://docs.astral.sh/uv/getting-started/installation/), then run:

```bash
uvx langbot
```

#### Self-host with Docker Compose

With Git, Docker, and Docker Compose installed, run:

```bash
git clone https://github.com/langbot-app/LangBot
cd LangBot/docker
docker compose --profile all up -d
```

For either self-hosted option, open `http://localhost:5300` (or `http://YOUR_SERVER_IP:5300` for a remote server), complete the setup, and connect a model and a bot. See the [getting started guide](https://langbot.app/docs/en/insight/guide/) and [Docker deployment guide](https://langbot.app/docs/en/deploy/langbot/docker/) for details.

### Links

| | |
|---|---|
| 🌐 **Website** | [langbot.app](https://langbot.app) |
| 📖 **Documentation** | [langbot.app/docs](https://langbot.app/docs/en/insight/guide/) |
| ☁️ **Cloud** | [cloud.langbot.app](https://cloud.langbot.app) |
| 🧩 **Extension Marketplace** | [space.langbot.app/market](https://space.langbot.app/market) |
| 🗺️ **Roadmap** | [langbot.app/en/roadmap](https://langbot.app/en/roadmap) |
| 📝 **Blog** | [langbot.app/en/blog](https://langbot.app/en/blog) |

### Repositories

| Repository | Description |
|---|---|
| [**LangBot**](https://github.com/langbot-app/LangBot) | Core platform — agents, messaging adapters, and the web dashboard |
| [**langbot-docs**](https://github.com/langbot-app/langbot-docs) | Documentation site |
| [**langbot-plugin-sdk**](https://github.com/langbot-app/langbot-plugin-sdk) | Plugin SDK, CLI, plugin runtime, and sandbox runtime |
| [**langbot-plugin-demo**](https://github.com/langbot-app/langbot-plugin-demo) | Plugin demos and officially maintained plugins |

### Community

- [Discord](https://discord.gg/wdNEHETs87) — Chat with the community and get help
- [QQ Group (1030838208)](https://qm.qq.com/q/DxZZcNxM1W) — 中文社区
- [Feature Requests & Roadmap](https://langbot.app/en/roadmap) — Share ideas and vote on upcoming features

---

<p align="center"><sub>Made with ❤️ by the LangBot community</sub></p>
