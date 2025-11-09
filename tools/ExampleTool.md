单个工具条目模板（推荐放在 tools/目录下的单独 md 文件）
--------------------------------
以下为每个工具应包含的必填/可选字段（可直接复制到工具条目的顶部作为 front-matter 或在 README 中按此格式展示）：

YAML 示例（可选）
```yaml
name: "ExampleTool"
slug: "example-tool"         # 用于 URL/文件名
category: "文献分析"
tags: ["python", "notebook", "nlp"]
short_description: "从科研文献中自动提取方法和结果的工具"
status: "active"
maintainer: "@devname"
repo: "https://github.com/owner/ExampleTool"
homepage: "https://example.org/demo"
license: "MIT"
last_update: "2025-11-01"
```

Markdown 展示模板
### ExampleTool
- 类别：文献分析
- 简短描述：从科研论文自动提取方法、指标和结果，生成可复现的实验摘要。
- 官方仓库 / 文档：https://github.com/owner/ExampleTool
- 在线 Demo：https://example.org/demo
- 维护者：@devname（联系邮箱：dev@example.org）
- 状态：active
- 许可：MIT
- 平台：Python 3.9+, Docker
- 部署/运行（最简示例）：
```bash
git clone https://github.com/owner/ExampleTool.git
cd ExampleTool
docker build -t exampletool .
docker run -p 8080:8080 exampletool
```
- 免费功能（Free tier）：
  - 单文档文本抽取
  - 本地运行脚本（命令行）
  - 基本规则与示例 notebook
- 付费功能（Paid tier / Enterprise）：
  - 批量云端抽取（并发）
  - 专用 API key 与 SLA 支持
  - 数据长期保存与团队共享功能
  - 定制化模型训练与优先 bug 修复
- 隐私/数据政策：
  - 免费计划：本地运行，不上传到第三方服务。
  - 云服务：使用前请参阅 Privacy Policy（链接）。
- 引用（如何在论文中引用）：
  - ExampleTool: Author et al., 2024, URL, DOI（如有）
