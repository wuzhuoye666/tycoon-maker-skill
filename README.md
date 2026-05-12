# Tycoon Maker

**商业大亨培养器** — 创业者的苏格拉底式思考助手

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Obsidian](https://img.shields.io/badge/Obsidian-Compatible-purple.svg)](https://obsidian.md)
[![AI Powered](https://img.shields.io/badge/AI-Powered-blue.svg)](https://github.com)

---

## What is Tycoon Maker?

Tycoon Maker is an AI-powered Socratic questioning assistant designed for startup founders and entrepreneurs. It guides you through deep thinking about your business ideas, conducts market research, and helps you transform abstract concepts into actionable plans — all while building a structured knowledge base in Obsidian.

**Core Philosophy**: *Think Deep, Act Fast* (一思考一行动)

---

## Features

### 🔮 Socratic Questioning
Don't expect direct answers. Tycoon Maker asks the right questions to help you discover your own insights:
- Clarify your core problem
- Challenge your assumptions
- Explore different perspectives
- Evaluate risks and opportunities

### 🔍 Market Research Agent
Automatically research your business idea:
- Similar products and competitors
- Success/failure cases
- Market size and trends
- Differentiation opportunities

### 📋 Action Guide Generator
Turn insights into action:
- Weekly tasks with priority tags
- Monthly goals with measurable milestones
- Resource assessment (time, money, skills)
- Risk mitigation plans

### 📝 Obsidian Integration
Build your business knowledge base:
- Bidirectional links (`[[note-name]]`)
- Tag system for status tracking
- Callout formatting for visual clarity
- Dataview plugin compatibility

---

## Quick Start

### Prerequisites
- [Codebuddy Code](https://github.com/codebuddy-code/codebuddy-code) installed
- [Obsidian](https://obsidian.md) (optional, for knowledge management)

### Installation

1. Clone this repository to your Codebuddy skills directory:
```bash
cd ~/.codebuddy/skills
git clone https://github.com/your-username/tycoon-maker.git
```

2. Restart Codebuddy Code or reload skills

3. Start a conversation with phrases like:
   - "帮我想一个创业方向" (Help me think of a startup direction)
   - "讨论一下我的商业想法" (Discuss my business idea)
   - "创业问答" (Startup Q&A)

---

## How It Works

```
Your Business Idea
        │
        ▼
┌───────────────────────┐
│  Phase 1: Socratic    │  ← Ask questions, don't give answers
│  Questioning          │
└───────────────────────┘
        │
        ▼
┌───────────────────────┐
│  Phase 2: Market      │  ← Research similar cases
│  Research (Agent 1)   │    Competitors & trends
└───────────────────────┘
        │
        ▼
┌───────────────────────┐
│  Phase 3: Action      │  ← Weekly tasks
│  Guide (Agent 2)      │    Monthly milestones
└───────────────────────┘
        │
        ▼
┌───────────────────────┐
│  Phase 4: Save to     │  ← Obsidian format
│  Knowledge Base       │    Bidirectional links
└───────────────────────┘
```

---

## Example Output

When you discuss a business idea, Tycoon Maker generates a structured note like this:

```markdown
---
tags:
  - 创业
  - Token分流
  - 进行中
aliases:
  - AI API网关
created: 2026-05-12
status: 进行中
priority: 高
---

# 智能降本网关

> [!info] 概览
> - **认知程度**: 深入理解
> - **核心价值**: 用技术手段帮用户省钱

## 本周行动 `#本周任务`
- [ ] 本地部署 One-API `#高优先级`
- [ ] 测试核心功能 `#高优先级`

## 止损机制
| 节点 | 触发条件 | 止损成本 |
|------|---------|---------|
| 节点A | 技术难度超预期 | 20h + ¥100 |
| 节点B | 上线无用户 | 105h + ¥1450 |
```

---

## Directory Structure

```
tycoon-maker/
├── SKILL.md                    # Main skill definition
├── README.md                   # This file
├── LICENSE
└── references/
    ├── cognitive-template.md   # Obsidian note template
    ├── socratic-questions.md   # Question bank
    ├── agent-idea-research.md  # Agent 1 instructions
    └── agent-action-guide.md   # Agent 2 instructions
```

---

## Customization

### Change Knowledge Base Location
Edit `SKILL.md` and update the path:
```yaml
# Default:
C:/Users/kingwu/Desktop/商业文件夹/

# Change to your preferred location:
/path/to/your/obsidian/vault/
```

### Add Custom Questions
Edit `references/socratic-questions.md` to add your own questioning patterns.

### Modify Note Template
Edit `references/cognitive-template.md` to customize the output format.

---

## Socratic Question Categories

| Category | Purpose | Example Question |
|----------|---------|------------------|
| Clarification | Define the real problem | "你真正想解决的核心问题是什么？" |
| Challenge | Test assumptions | "如果这个假设是错的，会怎样？" |
| Evidence | Verify information | "你的判断基于什么数据？" |
| Perspective | Explore viewpoints | "如果站在用户角度，他们会怎么看？" |
| Consequence | Foresee outcomes | "最坏的情况会是什么？" |
| Meta-cognition | Reflect on thinking | "你现在是怎么思考这个问题的？" |

---

## Why Socratic Method?

Unlike AI assistants that give direct answers, Tycoon Maker helps you **think better**:

1. **Ownership** — You discover insights yourself, not receive them passively
2. **Depth** — Questions challenge surface-level thinking
3. **Clarity** — Articulating answers reveals gaps in understanding
4. **Action** — Confusion leads to paralysis; clarity leads to movement

---

## Use Cases

- 💡 **Early-stage founders** validating business ideas
- 🔄 **Pivot decisions** exploring new directions
- 📊 **Market positioning** finding differentiation
- ⚠️ **Risk assessment** planning for worst cases
- 📈 **Growth strategy** prioritizing actions

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Inspired by Socratic teaching method
- Built for [Codebuddy Code](https://github.com/codebuddy-code/codebuddy-code)
- Optimized for [Obsidian](https://obsidian.md) knowledge management

---

## Contact

Have questions or suggestions? Open an issue or reach out!

---

<p align="center">
  <b>Turn your ideas into action. Build your tycoon.</b>
</p>
