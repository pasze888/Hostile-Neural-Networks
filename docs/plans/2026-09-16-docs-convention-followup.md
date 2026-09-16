# 文档落点规范：未完成项

依据工作区根 `AGENTS.md` §7（文档落点与协作规范）。2026-09-16 核查本仓库：没有需要迁移的
`docs/**` 文件（无旧命名文档），以下是尚未处理的部分。

## 待办

- [x] **补中文 README**（2026-09-16 完成）：已建 `README.zh-CN.md`，与英文版按 §7.3 逐项核对
  标题层级、顺序、代码块数量、链接路径一致，两份互为语言切换。
- **README 内容归位**：「Adding Custom Data Models」一节讲的是数据包 JSON 结构与 schema，
  超出 README 承载范围（简介、安装、快速开始、配置、常用命令、文档链接），建议归到
  `docs/reference/custom-data-models.md`，落点待确认后再动。

## 依据

- §7.2：验证过的 API 事实 / 领域知识 → `docs/reference/<topic>.md`。
- §7.3：`README.md` 为英文源，`README.zh-CN.md` 为中文同步。
