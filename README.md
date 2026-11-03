# wordbook-add · 我的生词本 Claude Skill

问 Claude 英语或日语单词、句子时，它会在回答后提议把值得记的内容记进「我的生词本」（一个 Claude Artifact 页面）。你同意了才写入。

## 功能

- 支持英语（美式 IPA）和日语（假名 + 罗马字）
- 单词和句子都能记，句子有错会记改正后的说法和错因
- 先提议、后写入，不会自动乱记
- 第一次使用自动发布生词本页面（`wordbook.html`）

## 安装

1. 下载本仓库的 `wordbook-add` 文件夹（或打成 zip）
2. claude.ai：Customize > Skills > 上传 zip；Claude Code：放到 `~/.claude/skills/wordbook-add/`
3. 第一次让 Claude 记词时，它会建好生词本并给你链接。把 `SKILL.md` 里的 `WORDBOOK_URL` 换成这个链接，以后都会写进同一本。

## 使用

- 问「insurance 怎么读？」→ 回答末尾会问「要加进生词本吗？」→ 回「加」
- 或直接说「帮我记一下 懐かしい」

## 许可

MIT License © 2026 Alice Yu
