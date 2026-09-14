# 所谓的教程 · Python 第三方库「从小白到大神」全站

一个 **持续扩充的 Python 第三方库教程仓库**：每一份教程都是完整的「从小白到大神」全套结构（是什么 → 核心概念 → 安装 → API 全面讲解 → 实战项目案例（入门/进阶/综合）→ 进阶内容 → 高频坑 → 学习路径与自测题），并配有一个 **离线教程生成器网站**。

> 本仓库与 [个人博客项目](https://gitee.com/pan-decai/personal-blog) 相互独立：那里是博客系统源码 + 博客绑定教程，这里专注 Python 库的通用教程。

---

## 📦 已收录教程（24 份，持续新增中）

| 分类 | 库 |
|------|-----|
| 🖥 浏览器自动化 | Playwright（含 7 库联动案例）、Selenium、PyAutoGUI |
| 🌐 网络与解析 | Requests、BeautifulSoup4 |
| 📊 数据分析 | Pandas、NumPy、Matplotlib、Openpyxl |
| 🧪 测试与图像 | Pytest、Pillow |
| 🏗 Web 框架 | Django、Flask、Jinja2、Werkzeug、Flask-SQLAlchemy |
| 🗄 数据存储 | SQLite |
| 📝 内容文档 | python-markdown、Pygments、PyYAML |
| ⏰ 时间处理 | python-dateutil |
| 📦 部署桌面 | waitress、pywebview、PyInstaller |

## 🗂 仓库结构

```
所谓的教程/
├── 独立版库教程/               # 24 份完整教程（.md 可编辑）
│   ├── 18第三方库全面教程 · Playwright.md
│   ├── 19第三方库全面教程 · Requests.md
│   └── ...
├── 纯教程网站/                 # 离线教程网站
│   ├── index.html              # 双击即用（26 个 tab，含教程生成器）
│   └── 使用说明.txt
└── README.md
```

## 🚀 快速开始

- **看网站**：解压后双击 `纯教程网站/index.html`，左侧 tab 切换教程，右上角切换日间/夜间模式
- **教程生成器**：网站内「🎓 教程生成器」页输入库名（支持别名，如 bs4 / drf），已收录库一键跳转完整教程；未收录库按提示把库名发给豆包，生成后加入本仓库
- **编辑 md**：直接用 Typora / VS Code 打开 `独立版库教程/*.md` 阅读或二次加工

## ✍️ 如何新增一份教程

1. 在 `独立版库教程/` 新建 `NN第三方库全面教程 · 库名.md`（编号接续当前最大号）
2. 按八章结构写作：是什么 / 核心概念 / 安装 / API 讲解 / 实战案例（入门→进阶→综合）/ 进阶 / 高频坑 / 学习路径 + 自测题
3. 提交推送：

```bash
git add -A
git commit -m "新增 XX 库教程"
git push
```

## 📄 License

仅供学习交流使用。本仓库教程涉及的开源库版权归其各自作者所有。
