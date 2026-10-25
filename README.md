# thesis-night-run-marketplace

独立的最小市场，只含一个插件 `thesis-night-run`。结构与 Claude 官方市场一致：

```
.claude-plugin/marketplace.json
thesis-night-run/
  .claude-plugin/plugin.json
  skills/task-triage-night-run/SKILL.md
```

## 安装

1. 在 GitHub 新建一个空仓库，例如 `zjw020808/thesis-night-run-marketplace`，选公开，不要初始化 README。
2. 在本目录执行：

```bash
git remote add origin https://github.com/zjw020808/thesis-night-run-marketplace.git
git push -u origin main
```

3. Claude Desktop：**设置 → Plugins → Add marketplace → GitHub repo**，填 `zjw020808/thesis-night-run-marketplace`。
4. 在插件列表里安装 `thesis-night-run`。

这个仓库与 `academic-writing-marketplace` 完全独立：添加它不会影响原有市场和已装插件，也不会覆盖 `physics-thesis-revision`。

## 许可

MIT。
