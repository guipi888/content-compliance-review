# 内容合规审核 · WorkBuddy Skill

六平台（视频号/抖音/小红书/快手/B站/公众号）内容合规审核：本地违禁词检测+平台专项规则+隐私脱敏+过度承诺扫描，输出修改建议。

## 特性

- 请参考 SKILL.md 中的详细说明

## 安装

### WorkBuddy 技能市场（推荐）

在 WorkBuddy 中搜索「内容合规审核」一键安装。

### 手动安装

```bash
git clone https://github.com/guipi888/content-compliance-review.git \
  ~/.workbuddy/skills/内容合规审核
```

### 环境依赖

请参考 SKILL.md 中的环境要求章节

## 使用

```bash
python3 scripts/pipeline.py <参数>
```

详细参数请参考 SKILL.md

## 输出

结构化审核报告（✅正确 / ⚠️存疑 / ❌错误 + 修正建议）

## 项目结构

```
.gitignore
LICENSE
references
references\审核流程.md
references\微信公众号和服务号推荐运营规范.md
references\违禁词库
references\违禁词库\B站违禁词库.md
references\违禁词库\公众号违禁词库.md
references\违禁词库\小红书违禁词库.md
references\违禁词库\快手违禁词库.md
references\违禁词库\抖音违禁词库.md
references\违禁词库\视频号违禁词库.md
references\违禁词库\通用违禁词库.md
references\违禁词库\闲鱼违禁词库.md
references\违禁词库.md
scripts
scripts\check_prohibited_words.py
SKILL.md
```

## 关于作者

**桂皮 Guipi** — AI Agent 开发者 · 超级个体践行者
专注 AI 效率工具与一人公司方法论，帮普通人用 AI 成为超级个体

| 平台 | 账号 |
|------|------|
| 📱 小红书 | [桂皮AI实战](https://www.xiaohongshu.com/user/profile/5a409dda44363b313b9d7e15) |
| 🎬 抖音 | [桂皮AI实战](https://v.douyin.com/QJRjHGAtrvA/) |
| 📺 视频号 | 微信内搜「桂皮AI实战」 |
| 💬 公众号 | 微信搜「桂皮AI实战」 |
| 🌟 知识星球 | [AI超级个体](https://t.zsxq.com/guSUk) — AI工具 · 创作 · 产品 · 流量 · 变现 |
| 🐙 GitHub | [guipi888](https://github.com/guipi888) |
| 💬 微信 | guipi996（注明来意） |

## License

MIT License — 详见 [LICENSE](./LICENSE)
