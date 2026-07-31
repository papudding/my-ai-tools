# my-ai-tools
Record my selection choices

## [opencode](https://github.com/anomalyco/opencode)
开源 AI 编程智能体，可在终端中进行代码开发、分析和修改。
```bash
npm install -g opencode-ai
```

## [opencode-notify](https://github.com/papudding/opencode-notify)
OpenCode 的 Bark (iOS) 推送通知插件，当智能体需要权限确认、提问或输出完成时推送到手机。
```bash
mkdir -p ~/.config/opencode/plugins
```
```bash
cp notify.ts ~/.config/opencode/plugins/notify.ts
```
```bash
cp notify.sh ~/.config/opencode/notify.sh && chmod +x ~/.config/opencode/notify.sh
```

## [oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)
面向 OpenCode/Codex 的多智能体编排插件，支持多模型协作、团队模式和自动化开发工作流。
```bash
bunx oh-my-openagent install
```
```bash
brew install tmux
```
## [codegraph](https://github.com/colbymchenry/codegraph)
代码预索引知识图谱工具，自动构建符号与调用关系图，帮助 AI 编程助手精准理解代码库。
```bash
npm i -g @colbymchenry/codegraph
```
```bash
codegraph install
```
```bash
codegraph init
```

## [rtk](https://github.com/rtk-ai/rtk)
CLI 代理工具，自动压缩 git、ls、test 等常用命令输出，减少 LLM Token 消耗 60-90%。
```bash
brew install rtk
```
```bash
rtk init -g --opencode
```
## [cc-switch](https://github.com/farion1231/cc-switch)
跨平台桌面工具，一站式管理 Claude Code、Codex、OpenCode 等多个 AI 助手的 API 提供商和 MCP/技能配置。
download dmg file directly from release page

## [ghostty](https://github.com/ghostty-org/ghostty)
快速、功能丰富的跨平台终端模拟器，采用平台原生 UI 和 GPU 加速渲染。
download dmg file directly from release page

## [herdr](https://github.com/ogulcancelik/herdr)
终端内的 AI 智能体多路复用器，支持多智能体并行运行、会话持久化和远程 SSH 重连。
download binary file directly from release page
```bash
chmod +x herdr-macos-aarch64
```
```bash
mv herdr-macos-aarch64 ~/.local/bin/herdr
```
```bash
herdr --remote remote-host
```

## [fnm](https://github.com/Schniz/fnm)
基于 Rust 构建的快速 Node.js 版本管理器，支持 .node-version 和 .nvmrc 文件。
```bash
cargo install fnm
```
```bash
export FNM_NODE_DIST_MIRROR=https://mirrors.ustc.edu.cn/node/
```
```bash
fnm i 24
```

## [oc-stats](https://github.com/Cateds/opencode-stats)
终端下的 OpenCode 使用统计仪表板，显示 Token 消耗、成本估算、模型和提供商分布及 365 天活动热力图。
```bash
cargo install opencode-stats
```
```bash
oc-stats                    # 查看使用统计
oc-stats --theme dark       # 指定深色主题
oc-stats --json export.json # 加载 JSON 导出文件
```

## Skills

### [comet](https://github.com/rpamis/comet)
可恢复的长任务工作流与 Skill 平台，支持 Native/Classic 双模式 Spec 驱动开发和 Skill 创建、评估、发布。
```bash
npm install -g @rpamis/comet
```
```bash
export OPENSPEC_TELEMETRY=0
```
```bash
comet init
```

### [huashu-design](https://github.com/alchaincyf/huashu-design)
HTML 原生设计 Skill，一句话生成高保真原型、幻灯片、动画、信息图，支持 MP4/PPTX/PDF 导出。
```bash
npx skills add alchaincyf/huashu-design
```

### [andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills)
Andrej Karpathy 风格的 AI 编程技能集，提供简洁直接的代码建议和解释。

内容直接写入 AGENTS.md

### [grill-me](https://github.com/mattpocock/skills/blob/main/skills/productivity/grill-me/SKILL.md)
严格的面试式 Skill，通过连续提问来完善你的计划或设计方案。

使用方式：`/grill-me`
