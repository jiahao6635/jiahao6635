<!-- GitHub profile README for @jiahao6635 -->

<div align="center">

# Jiahao

**AI Application & Full-Stack Engineer · Open-Source Contributor**

I build LLM gateways, model-evaluation tools, digital-human workflows, and reliable AI applications.  
专注 LLM 网关、模型评测、数字人和 AI 应用，也参与 Java 量化交易平台的开源贡献。

<a href="https://jiahao6635.github.io/"><img src="https://img.shields.io/badge/Website-jiahao6635.github.io-0969DA?style=flat-square&logo=githubpages&logoColor=white" alt="Personal website"></a>
<a href="https://github.com/jiahao6635?tab=repositories"><img src="https://img.shields.io/badge/Repositories-Explore-24292F?style=flat-square&logo=github&logoColor=white" alt="GitHub repositories"></a>
<a href="https://github.com/search?q=is%3Apr+author%3Ajiahao6635+is%3Amerged&type=pullrequests"><img src="https://img.shields.io/badge/Open%20Source-Merged%20PRs-1F883D?style=flat-square&logo=git&logoColor=white" alt="Merged pull requests"></a>

</div>

## What I work on

- **AI applications:** self-hosted digital humans, RAG, LLM agents, and human-in-the-loop workflows.
- **LLM infrastructure:** self-hosted gateways, streaming transports, model evaluation, and usage diagnostics.
- **Developer experience:** diagnostic tools, automation, reproducible builds, and evidence-first debugging.
- **Open source:** focused, test-backed contributions to active AI and developer-tooling communities.

## Recent activity · 最近动态

_Last updated: 2026-10-21 (UTC+8)._

| Date | Update |
| --- | --- |
| 2026-10-21 | Released [CPS Codex Candy Eval v0.1.2](https://github.com/jiahao6635/cps-codex-candy-eval/releases/tag/v0.1.2): reasoning tasks, model behavioral fingerprints, SVG drawing previews, and account-based test history; adapted to CPS v3.29.7. |
| 2026-10-20 | [Codex Proxy RS #484](https://github.com/zyycn/codex-proxy-rs/pull/484) merged: base pooled WebSocket circuit breaking on actual connection results so slow successful connections do not count as failures. |
| 2026-10-19 | Published [Model Health Plugin v0.3.2](https://github.com/jiahao6635/codex-model-health-plugin/releases/tag/v0.3.2) from my fork: CPS v3.29.3 protocol compatibility and batch testing. |
| 2026-10-13 | [Codex Proxy RS #412](https://github.com/zyycn/codex-proxy-rs/pull/412) merged: color-coded first-token and total latency across usage views. |

Plugin releases above are locally/offline validated; live CPS installation and real-model billing checks remain pending.

## Open-source contributions · 开源贡献

Selected projects with merged PRs or direct upstream commits. Star badges reflect each upstream repository.

| Project | Stars | My contribution |
| --- | --- | --- |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | ![AutoGPT stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=flat-square) | HTTP response media-type parsing while preserving error bodies — [#14008 · merged](https://github.com/Significant-Gravitas/AutoGPT/pull/14008). |
| [WeKnora](https://github.com/Tencent/WeKnora) | ![WeKnora stars](https://img.shields.io/github/stars/Tencent/WeKnora?style=flat-square) | Password handling, tenant state, Wiki token limits, and document ingestion — [#2568](https://github.com/Tencent/WeKnora/pull/2568), [#2589](https://github.com/Tencent/WeKnora/pull/2589), [#2608](https://github.com/Tencent/WeKnora/pull/2608), [#2663](https://github.com/Tencent/WeKnora/pull/2663), all merged. |
| [MLflow](https://github.com/mlflow/mlflow) | ![MLflow stars](https://img.shields.io/github/stars/mlflow/mlflow?style=flat-square) | Correct `pydantic-ai-slim` version detection in autologging — [#24959 · merged](https://github.com/mlflow/mlflow/pull/24959). |
| [Codex Proxy RS](https://github.com/zyycn/codex-proxy-rs) | ![Codex Proxy RS stars](https://img.shields.io/github/stars/zyycn/codex-proxy-rs?style=flat-square) | WebSocket circuit-breaker behavior, OAuth HTTP/SSE transport, model catalog export, and usage latency display — [merged PRs](https://github.com/zyycn/codex-proxy-rs/pulls?q=is%3Apr+author%3Ajiahao6635+is%3Amerged). |
| [Dromara Northstar](https://github.com/dromara/northstar) | ![Northstar stars](https://img.shields.io/github/stars/dromara/northstar?style=flat-square) | Java quant trading platform: isolate playback contract-loading failures from application startup and improve data-service error reporting — [upstream commit](https://github.com/dromara/northstar/commit/4bc03e1b86bd8c3839e58da0a7b65704575907d1) (2024). |

Also merged: [OpsiMate — keyboard accessibility](https://github.com/OpsiMate/OpsiMate/pull/795) and [canvas-api-mcp — iterative discussion traversal](https://github.com/JohannsenLum/canvas-api-mcp/pull/31).

**In progress / 进行中:** [WeKnora #4116 — environment-owned OSS ECS RAM role authentication](https://github.com/Tencent/WeKnora/pull/4116), [WeKnora #2593 — embedding rate-limit retries](https://github.com/Tencent/WeKnora/pull/2593), and [MLflow #25303 — managed dataset identity in evaluations](https://github.com/mlflow/mlflow/pull/25303).

## Featured work

| Project | What it demonstrates | Core stack |
| --- | --- | --- |
| [CPS Codex Candy Eval](https://github.com/jiahao6635/cps-codex-candy-eval) | CPS plugin for reasoning tasks, behavioral fingerprints, SVG previews, and persistent batch-test history; adapted from upstream evaluation tools. | Rust · Go · JavaScript |
| [Model Health Plugin](https://github.com/jiahao6635/codex-model-health-plugin) | Fork integration of Meow / ModelTrace behavioral checks with CPS, batch controls, and historical reports. | Rust · Python · Vue |
| [HeyGemWeb](https://github.com/jiahao6635/HeyGemWeb) | A production-oriented Gradio UI and workflow layer for self-hosted HeyGem-compatible digital-human services. | Python · Gradio · FFmpeg |
| [Command Frontline](https://github.com/jiahao6635/Command-Frontline) | An original natural-language RTS with deterministic simulation, command planning, tests, and accessible controls. | TypeScript · React · Canvas · Playwright |
| [Repo Doctor](https://github.com/jiahao6635/repo-doctor) | An evidence-first CLI for diagnosing repositories that will not build or start. | Java 21 · Picocli · JUnit |
| [Slop Zoo Cannon Game](https://github.com/jiahao6635/slop-zoo-cannon-game) | A playable 3D arcade vertical slice with Blender assets, performance budgets, safe desktop packaging, and resilient saves. | Three.js · Blender · Electron |
| [AI Playground](https://github.com/jiahao6635/ai-playground) | Ten progressive projects covering RAG, tool use, LangGraph, persistence, HITL, and multi-agent orchestration. | Python · LangChain · LangGraph |

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
</p>

## GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jiahao6635&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jiahao6635&theme=github">
  <img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jiahao6635&theme=github" alt="Jiahao's GitHub contribution summary">
</picture>

<div align="center">

**日拱一卒 · Ship useful software · Contribute upstream**

</div>
