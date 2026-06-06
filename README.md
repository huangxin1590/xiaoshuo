# xiaoshuo

## 常用命令

### 核心交互

```bash
# 直接对话（最常用）
inkos interact "帮我写下一章的大纲"

# 进入连续对话模式
inkos interact

# 终端交互界面
inkos tui

# 启动 Web UI（注意：中转站可能被 Cloudflare 拦截，CLI 不受影响）
inkos studio
```

### 写作流程

```bash
# 写一章草稿
inkos draft

# 审核章节连续性（检查前后矛盾、坑位）
inkos audit 系统降临：废柴纪元 6

# 根据审核结果修订章节
inkos revise 系统降临：废柴纪元 6

# 导出全书
inkos export

# 写作质量评估
inkos eval

# AIGC 检测（查 AI 味）
inkos detect 系统降临：废柴纪元 6

# 章节摘要整合（长文减少上下文消耗）
inkos consolidate
```

### 后台自动模式

```bash
# 启动后台守护进程（自动定时写作）
inkos up

# 停止守护进程
inkos down

# 查看项目状态
inkos status
```

### 其他

```bash
# 环境与配置检查
inkos doctor

# 市场雷达（追热点）
inkos radar

# 管理书籍
inkos book --help
```
