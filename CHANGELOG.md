## v3.6.0 更新日志

### 🤖 服务架构全面升级
- Ollama 替代 LocalAI (端口 11434)
- Realtime 替代 Centrifugo + WuKongIM (端口 8081)
- 新增服务器状态面板页面 (ServerStatusActivity)
- UI 优化：功能按钮重新组织
- 一键部署脚本 start-all.ps1 / stop-all.ps1

### ✨ 新功能
- ServerStatusActivity 实时查看服务状态
- 服务器状态快捷入口卡片 (cardServerStatus)
- GitHub Release 自动化脚本
- 模型元数据管理 (models.json)

### 🔧 技术改进
- 适配 Ollama API 格式
- 服务自动检测适配新端口
- 更新所有字符串资源引用
- 导航菜单重构

### 📦 已下载 AI 模型
- qwen2.5:7b (4.36 GB) - 中文通用
- qwen2.5:3b (1.80 GB) - 轻量中文
- llama3.2:3b (1.88 GB) - 英文/代码

### 📱 APK 信息
- 版本: 3.6.0 (versionCode: 24)
- 大小: 16.76 MB
- 服务端口: Ollama=11434, PocketBase=8090, Realtime=8081