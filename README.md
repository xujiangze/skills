# 创建插件
https://code.claude.com/docs/en/plugins

# 插件市场
## 添加本地插件市场
```
/plugin marketplace add ./my-marketplace
```
执行完毕之后会在`/Users/xujiangze/.claude/plugins/known_marketplaces.json` 有插件市场
```json
{
  "my-plugins": {
    "source": {
      "source": "directory",
      "path": "/Users/xujiangze/go/src/xjz-skill/my-marketplace"
    },
    "installLocation": "/Users/xujiangze/go/src/xjz-skill/my-marketplace",
    "lastUpdated": "2026-06-30T10:35:56.338Z"
  }
}
```
## 安装插件市场中的plugin

