# Hi, I'm Zhugong (主公) 👋

**Connecting AI to real workflows — turning ideas into runnable, verifiable automation.**  
**把 AI 接入真实工作流，做成可以运行、可以验证的自动化项目。**

[![Live Portfolio](https://img.shields.io/badge/Live_Portfolio-zhugong--portfolio.pages.dev-d95d39?style=flat-square)](https://zhugong-portfolio.pages.dev/)
[![AGY Claude Style Focus](https://img.shields.io/badge/Antigravity_Suite-agy--claude--style--focus-10b981?style=flat-square)](https://github.com/junjiemi23-ship-it/agy-claude-style-focus)
[![x-readonly-mcp](https://img.shields.io/badge/MCP_Server-x--readonly--mcp-1d4ed8?style=flat-square)](https://github.com/junjiemi23-ship-it/x-readonly-mcp)
[![Email](https://img.shields.io/badge/Email-junjiemi23%40gmail.com-1f2937?style=flat-square)](mailto:junjiemi23@gmail.com)

---

### 🚀 Featured Open-Source Projects / 代表作品直达

> Every project below is built from real daily problems, shipped with public code/playbooks, and verified with concrete evidence.  
> 以下项目全部源自日常真实痛点，附带公开代码、方法手册与可复查的验收证据。（觉得实用欢迎顺手点亮对应仓库 ⭐ Star 支持维护！）

| Project / 项目 | What It Solves / 解决的核心痛点 | Verification & Highlights / 验收证据与亮点 |
| :--- | :--- | :--- |
| **[agy-claude-style-focus](https://github.com/junjiemi23-ship-it/agy-claude-style-focus)**<br>`Antigravity Suite` · `CDP` | `app.asar` localization patches get wiped on every silent Antigravity update, and single usage rings hide token quota spikes.<br>改包汉化一升级就被覆盖，单圆环盯不住上下文与配额双余量。 | **Zero-invasion 4,955+ zh-CN entries** (survives auto-updates, 0 idle daemon) + **Clawd meteor wish** (`Alt+Shift+M`) + **Deep Focus Pomodoro** + **dual context/quota ring & cost guard** + 1-click `.exe` installer. |
| **[x-readonly-mcp](https://github.com/junjiemi23-ship-it/x-readonly-mcp)**<br>`MCP Server` · `Python` | Third-party X scrapers break on stale bearer tokens or missing `x-client-transaction-id`, and fail completely when cookies expire.<br>第三方 X 抓取库常因缺事务签名或 Cookie 过期全挂。 | **13 strictly read-only tools**: Passwordless public fallback (`FxTwitter → X oEmbed`, preserving Note Tweets & 12k-char X Articles) + live transaction signing + self-healing GraphQL `queryId` extraction. |
| **[agent-gateway](https://github.com/junjiemi23-ship-it/zhugong-portfolio/tree/main/agent-gateway)**<br>`Protocol Bridge` · `Tool Calling` | Web-reverse ChatGPT pools silently drop the `tools` array, so agent clients cannot call tools.<br>网页逆向号池会静默丢弃 `tools` 参数，导致 Agent 调不了工具。 | **XML pseudo-protocol + deep prefill + repair ladder**: P4 acceptance passed **59/60** tool rounds (**98.3%**), **20/20** multi-turn, **0** forged calls, 104 regression tests. |
| **[agent-dispatch-kit](https://github.com/junjiemi23-ship-it/zhugong-portfolio/tree/main/agent-dispatch-kit)**<br>`Multi-Agent Ops` · `Templates` | Multiple AI agents working in silos with no unified dispatch, tracking, or acceptance gate.<br>多智能体各自为战，缺乏统一的派发、跟踪与独立验收。 | **3-layer architecture**: Standardized `dispatch → track → accept → advise` workflow with independent second-model scoring and runnable acceptance script. |
| **[assistant-pc-access-kit](https://github.com/junjiemi23-ship-it/zhugong-portfolio/tree/main/assistant-pc-access-kit)**<br>`4-Layer Access` · `Security` | An AI assistant trapped in a chat window can only answer questions, not execute across your devices.<br>困在聊天框里的 AI 只能问答，无法跨设备真正动手干活。 | **4-layer daily architecture**: 24/7 cloud VM + read-first accounts + mobile remote + private PC bridge, complete with security redlines and cron templates. |
| **[chat2api-sft-toolkit](https://github.com/junjiemi23-ship-it/zhugong-portfolio/tree/main/chat2api-sft-toolkit)**<br>`SFT Data Pipeline` · `Stdlib` | Monthly Chat subscription quota goes unused while SFT dataset labeling is expensive.<br>每月 Chat 订阅额度吃灰，而 SFT 微调数据标注成本高。 | **Zero-dependency Python stdlib scripts**: Resumable batch Q&A generation + exponential-backoff retries + dedup/cleaning pipeline + 4 real-world wiring pitfall notes. |
| **[aihot-welfare](https://github.com/junjiemi23-ship-it/zhugong-portfolio/tree/main/aihot-welfare)**<br>`LLM Scoring Mod` · `Docker` | Base AIHOT monitors general news, whereas real promo hunting needs to surface genuine perks and bury fake ones.<br>把新闻监控框架改造成“捞真羊毛、压假福利”的福利雷达。 | **`promo_welfare` evidence-weighted scoring patch**: Fake promos without official claim paths capped at `cred≤3` / `<40` pts; zero-cost OpenAI-compatible model wiring. |

---

### 🛠️ What I Focus On / 核心方向

- **Multi-Agent Orchestration & MCP Infrastructure**: Designing role boundaries, protocol bridges, read-first MCP servers, and independent verification gates.
- **Applied AI & Data Pipelines**: SFT distillation pipelines, evidence-weighted LLM scoring, and resilient web/API automation.
- **Lightweight Web Delivery**: Zero-dependency bilingual static sites deployed on Cloudflare Pages & GitHub Pages.

📫 **Open to Applied AI / Agent Automation Internships & Collaborations**:  
🌐 Portfolio: **[zhugong-portfolio.pages.dev](https://zhugong-portfolio.pages.dev/)** · ✉️ Email: **[junjiemi23@gmail.com](mailto:junjiemi23@gmail.com)**
