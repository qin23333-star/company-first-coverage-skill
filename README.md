# Company First Coverage Skill

一个可移植的 Codex Skill，用于撰写上市公司首次覆盖、完整投研报告和深度研究报告。它强调资料覆盖审计、全球公开来源、第一性原理、订单/供给/财务兑现、竞争格局、证伪信号和高价值图表。

## 安装

在 Codex 中发送：

```text
请安装这个 Skill：
https://github.com/qin23333-star/company-first-coverage-skill/tree/main/company-first-coverage
```

也可以从 [Releases](https://github.com/qin23333-star/company-first-coverage-skill/releases/latest) 下载 ZIP，解压后把 `company-first-coverage` 文件夹放到：

- macOS/Linux：`~/.codex/skills/`
- Windows：`%USERPROFILE%\.codex\skills\`

确保最终路径是 `company-first-coverage/SKILL.md`，然后在下一轮对话中使用。

## 使用

```text
请使用 $company-first-coverage，为XX公司撰写完整首次覆盖报告。
公司代码和交易所是……，报告基准日是……。
资料目录是……，输出目录是……。
先完成全部资料覆盖审计，再分章节写入报告文件；不要只输出摘要。
```

如果希望接近 40 页，请明确写“完整深度模式，目标约 40 页”。Skill 会把它转化为章节、字数、资料覆盖和图表验收门槛，而不是机械凑页数。

## 使用前提

- 使用者需要把年报、公告、研报、会议材料和自有笔记放到 Codex 可访问的文件夹，或作为附件提供。
- Skill 不会自动授予本地文件、联网、付费数据库或写入权限。
- 财务、法律与投资结论需要使用者自行复核；本 Skill 不输出目标价、仓位或买卖建议。
- 不要把 API Key、未公开公司资料、受版权保护的研报原文或客户数据放进公开仓库。

## 更新

公开版只接受可通用、可验证、无私人路径和无敏感依赖的规则。个人工作流、私有资料和内部框架不会同步到公开版本。

## License

MIT
