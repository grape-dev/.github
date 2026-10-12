<h1 align="center">grape-dev</h1>

<p align="center">
  <strong>AI Native DevOps — turn any Git project into an AI-driven development team.</strong>
  <br>
  No IDE required. Design, develop, test, and ship anywhere, anytime — AI-driven, human-reviewed.
</p>

---

## 👋 About

grape-dev builds **Grape**, a Multi-Agent DevOps platform where AI Agents autonomously collaborate to handle every repetitive step of the development workflow:

```
VOD Agent → Issue Agent → Coding Agent → QA Agent → SRE Agent
  voice       issues        code         review    build & ship
```

Connect a traditional Git project and the full pipeline from requirements to delivery runs on its own — Issues auto-triage, code auto-implements, PRs auto-review, builds auto-deploy. **In one sentence: your Git project becomes an autonomous development team.**

## 📦 Repositories

| Repo | Description |
|------|-------------|
| [**grape**](https://github.com/grape-dev/grape) | The Multi-Agent DevOps platform — Feishu / WebUI / Webhook entry points, one-click AI-native hosting |
| [**grape-cli**](https://github.com/grape-dev/grape-cli) | Contract-driven CLI for Agents — auto-generates commands from the server's OpenAPI, zero token exposure |
| [**grape-skills**](https://github.com/grape-dev/grape-skills) | Official skill library covering the full development lifecycle |
| [**grape-template**](https://github.com/grape-dev/grape-template) | One-click project templates — every open-source project can be your starting point |

## 🚀 Quick Start

```bash
git clone https://github.com/grape-dev/grape.git
cd grape
pip install -r requirements.txt
npm install -g opencode        # at least one Agent CLI
python -m src.api.run --dev    # open http://localhost:3000
```

## 🤝 Contributing

Contributions of every kind are welcome — code, docs, skills, templates, and community. See each repo's `CONTRIBUTING.md`.

## 📄 License

MIT