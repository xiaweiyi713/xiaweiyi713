<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=%E5%BE%90%E6%96%87%E6%9B%9C%20%C2%B7%20Wenyao%20Xu&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=%E6%9E%84%E5%BB%BA%E5%8F%AF%E4%BF%A1%E7%9A%84%20AI%20%E7%B3%BB%E7%BB%9F%20%C2%B7%20Building%20trustworthy%20AI%20systems&descSize=16&descAlignY=58" width="100%" alt="banner"/>

<a href="https://github.com/xiaweiyi713">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+SC&weight=600&size=22&duration=2800&pause=700&center=true&vCenter=true&width=600&height=45&color=5A67D8&lines=%E8%AF%81%E4%BC%AA%E4%BC%98%E5%85%88%20Agent%20%C2%B7%20%E5%8F%AF%E9%AA%8C%E8%AF%81%20RAG%20%C2%B7%20MCP%20%E5%BC%80%E5%8F%91%E8%80%85%E5%B7%A5%E5%85%B7;%E5%AE%81%E5%8F%AF%E8%AF%B4%E3%80%8C%E6%9F%A5%E4%B8%8D%E5%87%86%E3%80%8D%2C%E4%B9%9F%E4%B8%8D%E7%BC%96%E4%B8%80%E4%B8%AA%E7%AD%94%E6%A1%88;Verify%2C%20don%27t%20trust." alt="typing"/>
</a>

<br/>

[![CiteGuard](https://img.shields.io/badge/CITEGUARD-证伪优先引用核验-1a7f37?style=for-the-badge)](https://github.com/xiaweiyi713/citeguard)
[![PyPI](https://img.shields.io/pypi/v/citationguard?style=for-the-badge&label=PyPI&color=3775A9)](https://pypi.org/project/citationguard/)
[![struct-viz](https://img.shields.io/badge/STRUCT--VIZ-408_算法可视化_⭐106-3178C6?style=for-the-badge)](https://github.com/xiaweiyi713/struct-viz)

![Profile views](https://komarev.com/ghpvc/?username=xiaweiyi713&style=flat&color=5A67D8)

</div>

---

- 🚢 [**CiteGuard**](https://github.com/xiaweiyi713/citeguard) **v0.1.1 已上 [PyPI](https://pypi.org/project/citationguard/) 与 [MCP 官方 registry](https://registry.modelcontextprotocol.io)**(`pip install citationguard`)— AI 写作的"多疑审稿人",核验引用是否存在、元数据是否正确、是否真支持论点;可被 Claude Code / Codex / Cursor 以 **MCP 工具**直接调用
- 🚀 [**FAR**](https://github.com/xiaweiyi713/FAR) 正朝论文推进 — 让 RAG Agent 主动追问"**什么证据能证明当前答案是错的**"
- 🌱 持续打磨 [**VeraRAG**](https://github.com/xiaweiyi713/VeraRAG)(可验证 Agentic RAG,791 个测试)与 [**agentic-os-core**](https://github.com/xiaweiyi713/agentic-os-core)(零依赖的 Agent 记忆/规划引擎)
- 💬 可以和我聊:**引用幻觉与核验、可验证 RAG、Agent 弃权设计、MCP 工具开发**
- ⚡ 一条贯穿所有项目的原则:**宁可说"查不准",也不编一个答案**

---

## 关于我

西南财经大学 AI 方向本科生。我做的是**生产级的可信 AI 系统**——不是 notebook、不是 demo:有 CI、有发布门禁、有几百个测试守住行为边界的那种。

我最关心的问题是:**AI 说错话的时候,系统怎么兜底?** 围绕这个问题做了一条"证伪优先"主线——[CiteGuard](https://github.com/xiaweiyi713/citeguard) 用真实学术库证伪每一条引用;[FAR](https://github.com/xiaweiyi713/FAR) 把"哪里可能错"转成可检索的证据需求;[VeraRAG](https://github.com/xiaweiyi713/VeraRAG) 让 Agentic RAG 的每步推理可审计。它们共享同一套设计哲学:**弃权优于猜测,证伪优于自证,源不可达只降置信度、绝不升级成指控。**

工程上我在意:测试纪律(CiteGuard 548 / VeraRAG 791 / agentic-os-core 330 个测试)、零依赖核心、机器可读的输出契约。

## 我在做什么

| 项目 | 一句话 |
|---|---|
| 🔍 [**CiteGuard**](https://github.com/xiaweiyi713/citeguard) | 证伪优先的引用核验:存在性 / 元数据 / 论点支撑三重检查,支持中文文献(GB/T 7714 + DOI 注册表) · [PyPI](https://pypi.org/project/citationguard/) + MCP registry |
| 🧪 [**FAR**](https://github.com/xiaweiyi713/FAR) | 证伪引导检索,让语言 Agent 自我纠错(研究项目) |
| ✅ [**VeraRAG**](https://github.com/xiaweiyi713/VeraRAG) | 可验证的 Agentic RAG 推理系统,每一步可审计 |
| 📊 [**struct-viz**](https://github.com/xiaweiyi713/struct-viz) | 408 考研四科算法动画可视化平台 ⭐106 |
| 🛒 [**CartCompass**](https://github.com/xiaweiyi713/CartCompass) | 多模态电商导购 Agent,商品事实零幻觉(iOS + FastAPI) |
| 🧠 [**agentic-os-core**](https://github.com/xiaweiyi713/agentic-os-core) | Agent 记忆与规划引擎:图存储 + MCTS + 分层规划,零依赖 |
| 📬 [**MailAI**](https://github.com/xiaweiyi713/MailAI) | 接入多 LLM 的 iOS 智能邮件应用(SwiftUI) |

## 🛠 技术栈

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-1575F9?style=flat&logo=swift&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-5A67D8?style=flat)

<br/>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/xiaweiyi713/xiaweiyi713/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/xiaweiyi713/xiaweiyi713/output/github-snake.svg" alt="snake eating my contributions" />
</picture>

<sub>宁可说"查不准",也不乱指控 · <i>Verify, don't trust.</i></sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer" width="100%" alt="footer"/>
</div>
