<p align="center">
  <img src="./banner.jpg" alt="Nipcode. search. decide. install." />
</p>

# Building [Nipcode](https://nipcode.xyz)

Package search and trust layer for humans and AI agents. Evidence, risk and install boundary before any code touches your workspace.

> Not another registry. Not a remote executor. Not a magic score.

## What is live

- **7 sources.** npm, PyPI, crates.io, GitHub, Hugging Face, Docker Hub, MCP servers.
- **4 endpoints.** `/api/search`, `/api/decision`, `/api/inspect`, `/api/install-plan`.
- **OTP and OAuth.** Email, Google, GitHub, Phantom (Solana SIWS).
- **Project namespaces.** Up to 25 API keys per account, grouped by project.
- **Rate limit.** 60 requests per minute per key.
- **Public docs.** [nipcode.xyz/docs](https://nipcode.xyz/docs).
- **Open changelog.** [nipcode.xyz/changelog](https://nipcode.xyz/changelog).

## Boundaries

- The hosted API is read-only. It never installs and never writes to your workspace.
- The trust score is one signal. It is never install permission.
- Package metadata is treated as untrusted data, not as agent instructions.
- Install commands always require explicit user or host-policy approval.

## On the roadmap

- JSR, Go modules, Maven Central, NuGet.
- Local CLI with deep scan, sandbox audit, sandbox runtime.
- Remote and local MCP servers.
- Per-key usage stats in the dashboard.
- Custom OTP email through Resend.

## Links

- Code. [github.com/trynipcode/nipcode](https://github.com/trynipcode/nipcode)
- Site. [nipcode.xyz](https://nipcode.xyz)
- Docs. [nipcode.xyz/docs](https://nipcode.xyz/docs)
- Changelog. [nipcode.xyz/changelog](https://nipcode.xyz/changelog)
- X. [x.com/trynipcode](https://x.com/trynipcode)
- License. MIT.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/trynipcode/trynipcode/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/trynipcode/trynipcode/output/snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/trynipcode/trynipcode/output/snake.svg" />
  </picture>
</p>
