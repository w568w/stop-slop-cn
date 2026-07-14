# Stop Slop：让你的 AI 停止说浓重「AI 味」回复的 Skill

是否受够了 AI 回复中浓重的「AI 味」？

- 不是……而是……
- 重要的是……
- 你说得对，我……
- 要不要我顺手……
- 我会稳稳接住……
- 我已经吃下代码……
- 代码已经落盘并形成闭环、按照文档口径收紧、拆开代码不硬写……
- 这个项目的体积很强，说法大……

## 1. 安装方式

### 1.1. 使用 Skills（推荐）

```bash
npx skills add https://github.com/w568w/stop-slop-cn
```

### 1.2. 手动安装

直接下载本 Skill 的代码，放到 `.agents/skills/` 目录下即可。

## 2. 这是 AI Vibe 的 Skill 吗？

否。所有内容，无论是 README 还是 SKILL，都是 100% 手动编写的，绝无任何 AI 生成内容。

理由：我们发现 AI 并不能很好的总结出自己 sloppy 的句式。而且让他总结过往对话中的 pitfalls 的时候，他往往没有办法把握住 special 和 general 的关系（比如把特定于某个项目的规则也写到 skills 里来）。在经过一番折腾之后，还是决定自己手写更方便。

## 3. 许可协议

本项目按照 Apache License 2.0 协议开放源代码。