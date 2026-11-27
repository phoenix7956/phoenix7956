# Hi, I'm phoenix7956 👋

> 冯 · Mac M5 Max — AI Agent + 工具生态

我做 **AI Agent 内核**和**本地 AI 应用**。

[**盘古 Pangu**](https://github.com/phoenix7956/pangu) 是那个最后用户能摸到的 AI Agent —— 开源的通用 AI Agent 内核（Node / TypeScript），带 HTTP API 和零构建 Web 控制台。

---

## 🟢 Active Projects

| Project | Stack | Status | 用途 |
|---|---|---|---|
| [`mlx-studio`](https://github.com/phoenix7956/mlx-studio) | Python / Swift / macOS App | **v1.9 active（主项目）** | MLX Studio —— 本地 AI 创作工作台：音乐 / 出图 / 视频 / 配音 / TTS / 对话。已开源，Release `v1.9.0` |
| [`pangu`](https://github.com/phoenix7956/pangu) | TypeScript / Node.js | active | 盘古 —— 通用 AI Agent 内核，64 卦 384 爻，HTTP API + 零构建 Web 控制台（Apache-2.0） |
| [`bounty-radar`](https://github.com/phoenix7956/bounty-radar) | Python | active | GitHub / Opire 赏金单雷达 + 作业书 |
| [`medtravelcn`](https://github.com/phoenix7956/medtravelcn) | Astro / Node / SQLite | active | Medical tourism guide to China's top hospitals（Vercel 部署） |
| [`solfoundry-mcp`](https://github.com/phoenix7956/solfoundry-mcp) | JavaScript / MCP | v0.1 · 低频维护 | Claude Code MCP server for SolFoundry bounty platform — CLI CRUD bounties |
| [`claude-review`](https://github.com/phoenix7956/claude-review) | TypeScript / GitHub Action | v0.1 · 低频维护 | Claude Code agent that posts structured Markdown review comments on PRs |

> 账号级 SSH key **一把**（`mac-mini`）覆盖全部仓库 —— 不再需要 per-repo deploy key。
> `~/.ours/bin/gh-clone <仓库名>` 直接克隆，push 开箱即用 —— `~/.gitconfig` 里 `insteadOf` 把 `https://github.com/` 改写成 `ssh://git@ssh.github.com:443/`。

---

## ⛔ Discontinued

> 这些项目**已结束**。GitHub 上的仓库**已于 2026-11-25 删除**（一次性 bounty fork / 已被取代 / 已归档的一次性原型）。
> 完整 git 历史保留在本机：`~/Documents/GitHub 归档/2026-11-25/<仓库名>/`（需要时可直接 `git clone` 回来）。

| Project | Started | Ended | Reason |
|---|---|---|---|
| [`pangu-crawler`](https://github.com/phoenix7956/pangu) | 2026-05 | 2026-06 | 盘古爬虫已迁到 `phoenix7956/pangu`（Apache-2.0），旧仓只是 fallback |
| [`harnessclaw`](https://github.com/harnessclaw/harnessclaw) | 2026-06 (fork) | 2026-06 | 研究性 fork（曾提 PR #68 draft），上游 264★ 持续维护，**无需在本账号留副本** |
| [`solfoundry-pr-mcp`](https://github.com/SolFoundry/solfoundry) | 2026-05 (fork) | 2026-05 | 上游 PR 流程 MCP fork，内容**已并入** `solfoundry-mcp` 单一主仓 |
| [`claude-review-bounty`](https://github.com/claude-builders-bounty/claude-builders-bounty) | 2026-05 (fork) | 2026-05 | 内容**已拆成** `claude-review` 主仓；PreToolUse hook 随之迁到 `claude-review/.claude/hooks/block-destructive.py` |
| [`AgentOrchestration`](https://github.com/nguyencaoky1121-dev/AgentOrchestration) | 2026-05 (fork) | 2026-05 | 上游 fork，仅**作研究**，无本地改动 |
| [`meeet-solana-state`](https://github.com/santoslgl01-web/meeet-solana-state) | 2026-05 (fork) | 2026-05 | Solana 状态调研 fork，已不用 |
| `ai-seo-scanner`（仓库已删） | 2026-04 | 2026-05 | 项目方向调整，**不再做**。SaaS 4 维 AI 搜索 SEO 评分工具（Next.js 16 + Supabase + LemonSqueezy）原型 |
| `ao-962-fix`（仓库已删） | 2026-05 | 2026-06 | 独立 repo 维护 1 个 fork 的 bug patch 没价值，patch 内容**应合回**上游 `AgentOrchestration` |
| [`PlantGuide`](https://github.com/mergeos-bounties/PlantGuide) | 2026-07 (fork) | 2026-11 | mergeos-bounties bounty fork。本地独有 10 个提交（5 个物种包 + 5 条观察记录），**只保留在本机备份里** |
| [`BloggerEasy`](https://github.com/mergeos-bounties/BloggerEasy) | 2026-07 (fork) | 2026-11 | mergeos-bounties bounty fork，无本地改动 |
| [`PoseGuide`](https://github.com/mergeos-bounties/PoseGuide) | 2026-07 (fork) | 2026-11 | mergeos-bounties bounty fork，无本地改动 |

---

## 🛠️ Maintenance Policy

- **Active**: 接受 issue + PR，**自己** review
- **Discontinued record**: 本 README **永久记录项目起止** —— 仓库可删，记录不可删

---

## 📡 Activity

- **盘古**: `/Users/feng/Desktop/开源/pangu`（仓库 `phoenix7956/pangu`，Apache-2.0），本地跑在 `:18901`
- **OpenBot**: 多 Agent 派活总控（`~/Applications/OpenBot.app` · `~/.craft-anything` · `:8790`）—— 本机 + 局域网节点
- **GitHub 巡检 cron**: 已停（ticker 最后成功 2026-08-17）
- **Hermes / OpenClaw**: 已下线 —— OpenClaw 2026-07 并入 Hermes；Hermes 入口已不在 PATH，最后一次活动 2026-11-15，`~/.hermes/` 留着 5.8G 数据

---

<sub>Last registry update: 2026-11-27 by Codex —— 活跃 6 个（+ 本索引）</sub>
