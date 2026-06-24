# China Travel Hub · 战略方案文档站

外国人来华旅行信息站的完整战略与执行方案，整合了战略设计、商业计划、可行性评审三方面内容。

## 技术栈

- **文档框架**：MkDocs Material（移动端自适应、暗黑模式、搜索、导航）
- **部署**：Render Static Site
- **源码托管**：GitHub

## 本地预览

```bash
pip install -r requirements.txt
mkdocs serve
# 打开 http://127.0.0.1:8000
```

## 构建

```bash
mkdocs build
# 输出到 site/ 目录
```

## 部署到 Render

1. Fork 或推送本仓库到 GitHub
2. 在 Render 控制台新建 **Static Site**
3. 连接 GitHub 仓库
4. 配置：
    - **Build Command**: `pip install -r requirements.txt && mkdocs build`
    - **Publish Directory**: `site`
5. 保存部署

或使用 `render.yaml` Blueprint 一键配置。

## 文档结构

```
docs/
├── index.md          首页/执行摘要
├── strategy.md       核心战略与五大杠杆
├── market.md         市场分析
├── competitors.md    竞品分析
├── product.md        内容矩阵
├── tools.md          工具与社区
├── business.md       变现体系
├── finance.md        财务预测
├── operations.md     内容与SEO
├── channels.md       多渠道分发
├── roadmap.md        实施路线图
├── risks.md          风险与避坑
├── checklist.md      执行清单
└── audit.md          评审报告要点
```

## 版本

- v2.1（整合版）· 2026-06-24
