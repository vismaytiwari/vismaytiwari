<p align="center">
  <img src="./assets/profile-hero.png" width="100%" alt="A connected workbench of local-first developer tools" />
</p>

<h1 align="center">Vismay Tiwari</h1>

<p align="center">
  <strong>I build useful systems at the seam between devices, browsers, backends, and AI.</strong>
  <br />
  Backend-heavy engineer · local-first toolmaker · open-source contributor
</p>

<p align="center">
  <a href="https://vismaytiwari.github.io/portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://github.com/vismaytiwari?tab=repositories">
    <img src="https://img.shields.io/badge/Projects-Explore-111827?style=flat-square&logo=github&logoColor=white" alt="Projects" />
  </a>
  <a href="https://github.com/pulls?q=is%3Apr+author%3Avismaytiwari">
    <img src="https://img.shields.io/badge/Open_Source-Contributions-0F766E?style=flat-square&logo=opensourceinitiative&logoColor=white" alt="Open-source contributions" />
  </a>
</p>

---

## Things I’ve built

I like software that removes a small, stubborn bit of friction—and remains
understandable after the clever part is over.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/vismaytiwari/hotdrop">HotDrop</a></h3>
      <p><strong>Local, two-way file transfer between macOS and Android.</strong></p>
      <p>No cloud, cables, or account. Transfers are resumable and protected with local TLS, session tokens, strict cookies, and rate-limited authentication.</p>
      <p><code>TypeScript</code> <code>Electron</code> <code>Express</code> <code>Vitest</code></p>
      <p><a href="https://github.com/vismaytiwari/hotdrop">Explore HotDrop →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🧰 <a href="https://github.com/vismaytiwari/serverless_converter">Serverless Converter</a></h3>
      <p><strong>A private conversion toolkit that runs entirely in the browser.</strong></p>
      <p>Work with Markdown, PDF, JSON, CSV, images, Base64, and Slack formatting without uploading files to somebody else’s server.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Vite</code> <code>WASM</code></p>
      <p><a href="https://vismaytiwari.github.io/serverless_converter/"><strong>Try it live ↗</strong></a> · <a href="https://github.com/vismaytiwari/serverless_converter">Source →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧭 <a href="https://github.com/vismaytiwari/multi_browse">MultiBrowse</a></h3>
      <p><strong>A tiny native macOS browser picker.</strong></p>
      <p>Click a link, choose a browser, move on. A focused AppKit utility with no embedded browser engine, network service, telemetry, or Electron-sized RAM tax.</p>
      <p><code>Swift</code> <code>AppKit</code> <code>Launch Services</code></p>
      <p><a href="https://github.com/vismaytiwari/multi_browse">Explore MultiBrowse →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🔗 <a href="https://github.com/vismaytiwari/mac2and">Mac2And</a></h3>
      <p><strong>A native clipboard bridge from macOS to Android.</strong></p>
      <p>Clipboard sync with AES-GCM encryption, Keychain-backed secret rotation, QR onboarding, device controls, and a deliberately documented threat model.</p>
      <p><code>Swift</code> <code>CryptoKit</code> <code>Keychain</code> <code>ngrok</code></p>
      <p><a href="https://github.com/vismaytiwari/mac2and">Explore Mac2And →</a></p>
    </td>
  </tr>
</table>

---

## How I like to build

| | Principle | What it means in practice |
|---|---|---|
| 🎯 | **Useful over flashy** | Start with real friction and make the happy path obvious. |
| 🔒 | **Local-first when possible** | Keep private data on the user’s device and remove unnecessary infrastructure. |
| 🧱 | **Simple surface, serious internals** | Small tools still deserve resilient protocols, tests, and explicit security boundaries. |

---

## Open source

I contribute fixes where SDK behavior, developer experience, and production
reliability meet.

- **Langfuse Python SDK** — improved
  [model metadata extraction](https://github.com/langfuse/langfuse-python/pull/1728),
  [structured tool inputs](https://github.com/langfuse/langfuse-python/pull/1719),
  and [tool-error semantics](https://github.com/langfuse/langfuse-python/pull/1718).
- **pytest** — added strict
  [top-level `pytest.toml` validation](https://github.com/pytest-dev/pytest/pull/14646).
- Also contributing across
  [LangChain Google](https://github.com/langchain-ai/langchain-google/pull/1864),
  [LiteLLM](https://github.com/BerriAI/litellm/pull/31559),
  [MCP Toolbox](https://github.com/googleapis/mcp-toolbox/pull/3539),
  and [Crush](https://github.com/charmbracelet/crush/pull/3205).

<p>
  <a href="https://github.com/pulls?q=is%3Apr+author%3Avismaytiwari">
    <strong>See all pull requests →</strong>
  </a>
</p>

---

<details>
  <summary><strong>Production systems and impact</strong></summary>
  <br />
  <table>
    <tr>
      <td><strong>Backend scale</strong></td>
      <td>Systems serving 200M+ users, 7–10M DAU, and 200M+ events/day</td>
    </tr>
    <tr>
      <td><strong>Payments</strong></td>
      <td>Monolith-to-Go/Postgres migration with 99.99% uptime</td>
    </tr>
    <tr>
      <td><strong>Search</strong></td>
      <td>Low-latency retrieval over 10M+ documents</td>
    </tr>
    <tr>
      <td><strong>Reliability</strong></td>
      <td>Reduced MySQL lock contention by ~60% and Redis usage by ~30%</td>
    </tr>
    <tr>
      <td><strong>AI infrastructure</strong></td>
      <td>Agent, evaluation, and observability workflows with ~22% lower multi-LLM cost</td>
    </tr>
  </table>
</details>

<br />

**Working set:** Python · Go · Ruby · TypeScript · Swift · SQL · Kafka · Redis ·
PostgreSQL · Elasticsearch · Kubernetes · AWS · Docker · Terraform · LLM tooling

---

<p align="center">
  <strong>Build small. Think in systems. Ship the useful thing.</strong>
  <br /><br />
  <a href="https://vismaytiwari.github.io/portfolio/">Portfolio</a>
  ·
  <a href="https://github.com/vismaytiwari?tab=repositories">Projects</a>
  ·
  <a href="https://github.com/pulls?q=is%3Apr+author%3Avismaytiwari">Open source</a>
</p>
