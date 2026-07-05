# Claude-https://api.star-history.com/svg?repos=Alishahryar1/free-claude-code&type=Datesource media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Alishahryar1/free-claude-code&type=Date">
      <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Alishahryar1/free-claude-code&type=Date" width="700">
    </picture>
  </a>
</div>

## What You Get

- Drop-in proxy for Claude Code's Anthropic API calls (`/v1/messages`, `/v1/models`).
- Drop-in proxy for Codex via the OpenAI Responses API (`/v1/responses`).
- `fcc-claude` and `fcc-codex` launchers that read the current Admin UI port and auth token each time they start.
- 22 provider backends: NVIDIA NIM, OpenRouter, Google AI Studio (Gemini), DeepSeek, Mistral La Plateforme, Mistral Codestral, OpenCode Zen, OpenCode Go, Vercel AI Gateway, Hugging Face Inference Providers, Cohere, Wafer, Kimi, MiniMax, Cerebras Inference, Groq, Fireworks AI, Cloudflare, Z.ai, LM Studio, llama.cpp, and Ollama.
- Per-model routing for Claude Code: send Opus, Sonnet, Haiku, and fallback traffic to different providers.
- Native Claude Code `/model` picker support through the proxy's `/v1/models` endpoint (see [Model Picker](#model-picker)).
- Native Codex `/model` picker support when launched through `fcc-codex`, using a generated local model catalog.
- Streaming, tool use, reasoning/thinking block handling, and local request optimizations.
- Optional Discord or Telegram bot wrapper for remote Claude Code sessions.
- Optional Usage through the Claude Code VS Code extension.
- Codex CLI and VS Code extension support through the shared `~/.codex/config.toml` provider config.
- Optional voice-note transcription through local Whisper or NVIDIA NIM.
- Local **Admin UI** at `/admin` to edit supported proxy settings, validate changes, and check providers (loopback access only).

## Quick Start

### 1. Install/Update The Proxy

macOS/Linux:

```bash
curl -fsSL "https://github.com/Alishahryar1/free-claude-code/blob/main/scripts/install.sh?raw=1" | sh
```

