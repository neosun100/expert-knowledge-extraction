# 🧠 Expert Knowledge Extraction — 专家知识萃取方法论

> 通过系统性深度研究 + 战略性问题设计，在与行业专家的有限沟通时间内，最大化知识萃取效率。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 这是什么？

一套通用的 AI Agent 指令（Skill/Prompt），让 AI 助手帮你：

1. **深度研究**任意未知领域（多轮并行搜索 + 深度阅读核心文章）
2. **设计战略问题**（漏斗法 + 数据钩子，从专家脑中提取方法论）
3. **输出完整文档体系**（研究报告 + 数据武器库 + 知识缺口分析 + 问题清单 + 沟通策略 + 会议纪要模板）

最终目标：将专家的隐性知识转化为可复用的方法论和知识体系。

## 适用场景

- 🤝 准备与行业专家/甲方/合作伙伴的深度交流
- 🔬 从零开始研究一个新领域
- 📋 设计高质量的访谈/调研问题
- 🧩 构建某个领域的知识体系和方法论

## 支持的 AI 工具

| 工具 | 配置文件 | 安装方式 |
|------|---------|---------|
| **Kiro CLI** | `SKILL.md` | 复制到 `~/.kiro/skills/expert-knowledge-extraction/` |
| **Claude Code** | `CLAUDE.md` | 复制到项目根目录 |
| **Cursor** | `.cursorrules` | 复制到项目根目录 |
| **OpenAI Codex CLI** | `AGENTS.md` | 复制到项目根目录 |

## 快速安装

### Kiro CLI
```bash
mkdir -p ~/.kiro/skills/expert-knowledge-extraction
curl -o ~/.kiro/skills/expert-knowledge-extraction/SKILL.md \
  https://raw.githubusercontent.com/neosun100/expert-knowledge-extraction/main/SKILL.md
```

### Claude Code
```bash
curl -o CLAUDE.md \
  https://raw.githubusercontent.com/neosun100/expert-knowledge-extraction/main/CLAUDE.md
```

### Cursor
```bash
curl -o .cursorrules \
  https://raw.githubusercontent.com/neosun100/expert-knowledge-extraction/main/.cursorrules
```

### OpenAI Codex CLI
```bash
curl -o AGENTS.md \
  https://raw.githubusercontent.com/neosun100/expert-knowledge-extraction/main/AGENTS.md
```

## 使用方法

安装后，在对话中说类似以下的话即可触发：

```
"帮我准备下周跟XX专家的沟通"
"我要深入研究XX领域"
"帮我设计跟甲方交流的问题"
"我想从零了解XX行业"
```

## 核心方法论

```
Phase 0: 需求解构 → 明确沟通对象、目标、我方能力
Phase 1: 知识地图 → 多轮并行搜索 + 深度阅读 + 数据武器库
Phase 2: 问题工程 → 漏斗法(广度→聚焦→深挖→方法论) + 数据钩子
Phase 3: 沟通策略 → 时间分配 + 角色切换 + 话术库 + 风险预案
Phase 4: 文档输出 → 8个结构化文件，面向行动
Phase 5: 会后沉淀 → 纪要整理 → 方法论v1 → 知识体系构建
```

## 输出文件体系

```
{topic}-research/
├── README.md                    # 项目索引
├── research-report.md           # 领域深度研究报告
├── data-weapons.md              # 数据武器库（10-15个杀手级数据点）
├── knowledge-gaps.md            # 知识缺口分析（已知/模糊/未知）
├── meeting-questions.md         # 问题清单（含钩子+预期回答方向）
├── meeting-strategy.md          # 沟通策略（时间分配/话术/风险预案）
├── meeting-notes-template.md    # 会议纪要模板（打印带去会议）
└── our-value-proposition.md     # 我方价值方案
```

## 案例

| 领域 | 搜索维度 | 数据武器示例 |
|------|---------|-------------|
| 量化交易 | 策略分类、Alpha衰减、回测框架 | "动量策略10个月后alpha转负" |
| AI芯片 | 架构对比、推理效率、软件生态 | "TOPS/W指标头部公司对比" |
| 生物医药 | AI药物发现、靶点预测、临床优化 | "AI制药成功率vs传统对比" |
| 跨境电商 | 选品策略、内容营销、供应链 | "TikTok Shop GMV增长率" |

## 设计原则

1. **信息不对称最小化** — 你越懂，对方越愿意分享深层内容
2. **问题即工具** — 每个问题都是精心设计的知识撬棍
3. **数据即信任** — "年均衰减5.6%"比"策略会失效"有力100倍
4. **方法论优先于知识点** — 知识会过时，方法论持续产生新知识
5. **价值交换而非单向索取** — 让沟通成为双赢

## License

MIT
