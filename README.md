# 备考助手

基于 AI 的智能备考复习笔记整理工具。

## 功能特性

- 📄 上传文档（PDF、PPT、TXT、MD、DOCX、RTF）
- 🎙️ 录音转文字，课堂录音直接生成笔记
- 🤖 AI 智能解析章节结构
- 📝 支持多种学习方法（费曼、康奈尔、思维导图、记忆宫殿、案例分析）
- 📚 配套练习题生成
- 📤 PDF 导出

## 技术栈

- **框架**: Next.js 16 (App Router)
- **核心**: React 19
- **语言**: TypeScript 5
- **UI 组件**: shadcn/ui
- **AI 能力**: 豆包大模型
- **数据库**: Supabase

## 快速开始

```bash
# 安装依赖
pnpm install

# 启动开发服务器
pnpm dev

# 构建生产版本
pnpm build
```

## 环境变量

复制 `.env.example` 为 `.env` 并配置：

```bash
cp .env.example .env
```

## 许可证

MIT License
