# 学无止境

这是一个使用 MkDocs 构建的技术文档网站，专注于分享编程技术和学习经验。

## 特点

- 🎨 使用 Material for MkDocs 主题
- 📱 响应式设计，支持移动端访问
- 🔍 全文搜索功能
- 🌙 深色模式支持
- 📝 Markdown 编写
- 🔄 自动部署到 GitHub Pages

## 本地开发

1. 克隆仓库：
```bash
git clone https://github.com/heweijian4933/learn.git
cd learn
```

2. 安装依赖：
```bash
# 使用 uv 安装依赖
uv pip sync pyproject.toml
```

3. 本地预览：
```bash
mkdocs serve
```

4. 构建静态文件：
```bash
mkdocs build
```

5. 部署到 GitHub Pages：
```bash
mkdocs gh-deploy
```

## 目录结构

```
.
├── docs/
│   ├── assets/
│   │   └── images/
│   ├── backend/
│   │   └── index.md
│   ├── frontend/
│   │   └── index.md
│   └── index.md
├── mkdocs.yml
├── pyproject.toml
└── README.md
```

## 贡献指南

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

# java相关
* [00-00-Spring第一天](./docs/backend/java/00-Spring第一天.md)

