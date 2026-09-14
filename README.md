# Codex Image2

通过可配置的、兼容 OpenAI Images API 的第三方服务，在 Codex 中生成和编辑图片。

## 下载与安装

请从本仓库的 [Releases](../../releases) 下载 `codex-image2-skill-share.zip`，解压后将 `codex-image2` 文件夹复制至：

- macOS：`~/.codex/skills/codex-image2`
- Windows：`$HOME/.codex/skills/codex-image2`

然后在本机创建 `~/.config/codex-image2/.env`，填写：

```dotenv
API_URL=https://your-provider.example/v1
IMAGE_API_KEY=your-api-key
IMAGE_API_MODEL=your-image-model
```

请勿提交、上传或分享 `.env` 文件和 API Key。

详细的安装、跨平台使用和第三方 API 兼容要求，请见压缩包内的 `README.md` 与 `codex-image2/SKILL.md`。

## 功能

- 文字生图：`generate`
- 参考图创作和图片编辑：`edit`
- JSONL 并发批量生图：`generate-batch`
- 本机 `.env` 配置、dry-run 检查、超时和可重试错误处理

## 提醒

第三方服务的模型、价格、限额和数据处理规则会变化，请以服务商当前文档为准。
