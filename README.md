# Auto AI Web — Claude AI & Gemini Skill for Code and Image Generation

> **Claude skill** that generates **code** and **images** through the **Claude AI** and **Google Gemini** web interfaces when official APIs are not configured or available.

[![ClawHub](https://img.shields.io/badge/ClawHub-auto--ai--web-blue)](https://clawhub.ai/metiu1/auto-ai-web)
[![Version](https://img.shields.io/badge/version-1.0.0-green)](https://clawhub.ai/metiu1/auto-ai-web)
[![License](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

**Keywords:** Claude AI skill · Gemini skill · AI code generation · AI image generation · web automation · Claude Code skill · OpenClaw · no-API fallback · browser automation · LLM skill

---

## 🇮🇹 Descrizione

**Auto AI Web** è una skill per [Claude](https://claude.ai) che genera **codice** e **immagini** tramite le interfacce web di **Claude AI** e **Google Gemini** quando le API ufficiali non sono disponibili o configurate.

Si attiva **automaticamente** quando l'utente richiede:
- 🖼️ Generazione di **immagini** → instradata su **Gemini**
- 💻 **Scrittura** o **analisi** di **codice** → instradata su **Claude AI**

## 🇬🇧 Description

**Auto AI Web** is a [Claude](https://claude.ai) skill that routes code generation, code analysis, and image generation requests through the **Claude AI** and **Google Gemini** web interfaces when official APIs are unavailable.

It activates **automatically** when the user requests image generation or code writing/analysis.

---

## ✨ Features

- **Code generation & analysis** via the Claude AI web interface
- **Image generation** via the Google Gemini web interface
- **Automatic activation** on image or code requests
- **Graceful fallback** when official APIs are not configured
- **Secure credential handling** — never stores plaintext passwords
- **CAPTCHA & login awareness** — pauses for manual user input when needed

## 🚀 Installation

Install directly from ClawHub:

```bash
# via ClawHub
https://clawhub.ai/metiu1/auto-ai-web
```

Or clone this repository into your Claude skills directory:

```bash
git clone https://github.com/metiu1/auto-ai-web.git
```

## 📋 Usage

The skill triggers automatically. Just ask Claude to:

- "Genera un'immagine di un tramonto" → routed to **Gemini**
- "Scrivi una funzione Python per ordinare una lista" → routed to **Claude AI**

See [`SKILL.md`](SKILL.md) for the full operational workflow.

## 🔒 Security & Risks

| Risk | Mitigation |
|------|-----------|
| Skill may request login credentials | Log in directly via the provider site; never share raw passwords |
| Private code/data sent to third-party services | Confirm content is safe to share before submitting |
| Web sessions, CAPTCHA, provider downtime | Expect manual intervention; prefer official APIs when available |

## 🔗 References

- [Claude AI](https://claude.ai)
- [Google Gemini](https://gemini.google.com)
- [ClawHub — auto-ai-web](https://clawhub.ai/metiu1/auto-ai-web)

## 👤 Publisher

[metiu1](https://clawhub.ai/user/metiu1)

## 📄 License

Released under the [MIT License](LICENSE).
