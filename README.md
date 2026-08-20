# alibaba-ai-search

> **分类**：技能市场（第三方作品） ｜ **文件数**：10 ｜ **仓库目录**：`alibaba-ai-search__skillhub`

## 📌 简介

Use Alibaba AI Mode for intelligent product search and discovery. Use when: (1) using natural language queries, (2) getting AI-powered recommendations, or (3) exploring AI sourcing features. All URLs include traffic_type=ags_llm tracking parameter.

## 🎯 适用场景

适用于该技能的能力范围，详见下方「📖 使用说明」。

## 📂 目录结构

```text
  - .gitignore
  - LICENSE
  - README.md
  - SKILL.md
  - _icon.png
  - _meta.json
  - _skillhub_meta.json
  - release.sh
  - **scripts/**
    - build_url.py
    - package_skill.py
```

## 🚀 安装方法

将本文件夹整体复制到 WorkBuddy 的技能目录即可启用：

```bash
# 用户级（推荐）
cp -r . ~/.workbuddy/skills/alibaba-ai-search__skillhub

# 或项目级
cp -r . <你的项目>/.workbuddy/skills/alibaba-ai-search__skillhub
```

复制完成后，**重启或刷新 WorkBuddy**，即可在对话中用自然语言触发该技能。

## ⚙️ 配置说明

本技能开箱即用，**无需额外配置**。若涉及外部 API 调用，请在使用时按需提供您自己的密钥（不要提交到公开仓库）。

## 📖 使用说明（完整规范）

> 以下为该技能的完整说明，涵盖核心能力、工作流程与关键规则，帮助您全面了解其运作方式。

Intelligent product search and discovery using Alibaba AI Mode.

## Required Parameter

All URLs MUST include: `traffic_type=ags_llm`

## URL Patterns

### AI Mode Main Page

```
https://aimode.alibaba.com/?traffic_type=ags_llm
```

### AI Sourcing (Tailored Selections)

```
https://sale.alibaba.com/p/aisourcing/index.html?traffic_type=ags_llm
```

### AI Mode with Query

```
https://aimode.alibaba.com/?query=<url-encoded-query>&traffic_type=ags_llm
```

**Examples:**
```
https://aimode.alibaba.com/?query=wireless+earbuds+under+5+dollars&traffic_type=ags_llm
https://aimode.alibaba.com/?query=eco+friendly+packaging+materials&traffic_type=ags_llm
```

## Workflows

### AI-Powered Product Search

1. Navigate to AI Mode URL
2. Enter natural language query
3. Review AI-curated results
4. Extract product recommendations

### Smart Sourcing

1. Navigate to AI Sourcing URL
2. Describe sourcing requirements
3. Review tailored product selections
4. Compare AI-recommended suppliers

## Notes

- AI Mode supports natural language queries
- AI Sourcing provides curated product recommendations
- Results are personalized based on query context
- Use descriptive queries for better results

## 💡 命令示例

```bash
https://aimode.alibaba.com/?traffic_type=ags_llm
```

```bash
https://sale.alibaba.com/p/aisourcing/index.html?traffic_type=ags_llm
```

```bash
https://aimode.alibaba.com/?query=<url-encoded-query>&traffic_type=ags_llm
```

```bash
https://aimode.alibaba.com/?query=wireless+earbuds+under+5+dollars&traffic_type=ags_llm
https://aimode.alibaba.com/?query=eco+friendly+packaging+materials&traffic_type=ags_llm
```

## ⚠️ 注意事项

- 本技能从本地 WorkBuddy 环境导出，**所有真实密钥 / 凭据 / 个人数据均已脱敏为占位符**，重新使用前请配置您自己的 Key。
- 本技能来自技能市场（文件夹名含 `__skillhub`），**版权归原作者所有**，使用时请遵守其许可证与署名要求。
- 技能提供的是自动化辅助能力，不替代专业判断；涉及交易、法律、医疗等高风险场景请谨慎并自担风险。

## 📄 许可证

MIT License —— 详见仓库内 `LICENSE` 文件。
