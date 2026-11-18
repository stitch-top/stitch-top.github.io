<div align="center">

# Dr.626

**记录 · 沉淀 · 分享：一个关于测试、开发与自我提升的技术笔记站。**

[![Blog](https://img.shields.io/badge/Blog-stitch--top.github.io-2ea44f?style=for-the-badge)](https://stitch-top.github.io/)
[![Hexo](https://img.shields.io/badge/Hexo-6.2.0-0e83cd?style=for-the-badge)](https://hexo.io/)
[![Posts](https://img.shields.io/badge/Posts-58-f59e0b?style=for-the-badge)](https://stitch-top.github.io/archives/)
[![Categories](https://img.shields.io/badge/Categories-7-8b5cf6?style=for-the-badge)](https://stitch-top.github.io/categories/)
[![Tags](https://img.shields.io/badge/Tags-189-0ea5e9?style=for-the-badge)](https://stitch-top.github.io/tags/)

</div>

---

## 📌 博客速览

> 机会是累积的努力，平庸是堆积的荒芜。

**Dr.626** 始于 2021 年，是一份持续更新的个人技术笔记。内容从 Java 基础、Python 数据分析，延伸到自动化测试、测试工具与 Web 前端，也收录一些工具实践中沉淀下来的随笔。

| 项目 | 内容 |
| :--- | :--- |
| 站点地址 | [https://stitch-top.github.io](https://stitch-top.github.io) |
| 作者 | Dr.626 |
| 起始年份 | 2021 |
| 文章总量 | 58 篇（截至 2026 年 7 月） |
| 内容方向 | 自动化测试 · Python · 测试工具 · Java · Web · 数据库 |

---

## 🧭 内容地图

站点共 7 个分类，点击分类名可直接跳转到对应归档页。

| 分类 | 篇数 | 主要内容 |
| :--- | :---: | :--- |
| [Python](https://stitch-top.github.io/categories/Python/) | 17 | 基础语法、文件处理、NumPy / Pandas / SciPy / Matplotlib、机器学习、Flask、Tkinter、Streamlit |
| [测试工具](https://stitch-top.github.io/categories/%E6%B5%8B%E8%AF%95%E5%B7%A5%E5%85%B7/) | 13 | JMeter、Fiddler、Charles、Postman、ADB、F12、FFmpeg、SQLMap、Burp Suite |
| [自动化](https://stitch-top.github.io/categories/%E8%87%AA%E5%8A%A8%E5%8C%96/) | 10 | Selenium、Pytest、Allure、UnitTest、Mock、Playwright、Robot Framework、Locust、Cypress |
| [Java](https://stitch-top.github.io/categories/Java/) | 7 | Java 基础系列、Servlet 系列（容器、注解、Session、Filter、Listener） |
| [Web](https://stitch-top.github.io/categories/Web/) | 7 | JavaScript 基础与进阶、DOM / BOM、ES6 特性 |
| [数据库](https://stitch-top.github.io/categories/%E6%95%B0%E6%8D%AE%E5%BA%93/) | 2 | SQL 与 MQL 查询笔记 |
| [逸文](https://stitch-top.github.io/categories/%E9%80%B8%E6%96%87/) | 2 | 多数据库问题、MongoDB 连接等实践随笔 |

---

## 📝 最近更新

- **2026-06-08** · [F12 前端性能](https://stitch-top.github.io/2026/06/08/ce-shi-gong-ju/tt06-f12/tt03-f12-qian-duan-xing-neng/) — Performance 找卡顿白屏，Memory 堆快照定位内存问题
- **2026-04-01** · [Burp Suite（二）](https://stitch-top.github.io/2026/04/01/ce-shi-gong-ju/tt09-burp-suite/tt02-burp-suite-er/) — 序列分析、编解码与日志记录
- **2026-02-09** · [Burp Suite（一）](https://stitch-top.github.io/2026/02/09/ce-shi-gong-ju/tt09-burp-suite/tt01-burp-suite-yi/) — Target、代理与 Repeater
- **2025-12-22** · [SQLMap 的使用](https://stitch-top.github.io/2025/12/22/ce-shi-gong-ju/tt08-sqlmap/tt01-sqlmap-de-shi-yong/) — 注入点探测与联合查询
- **2025-11-27** · [Servlet（三）](https://stitch-top.github.io/2025/11/27/java/java07-servlet-san/) — Cookie、Session、Filter 与 Listener

更多文章请前往 [归档页](https://stitch-top.github.io/archives/)。

---

## ✨ 站点功能

- 📚 **归档 / 分类 / 标签**：按时间、主题和关键词三种方式浏览文章
- 🔍 **全文搜索**：基于本地索引的快速检索
- 🕸 **文章关系网**：以标签为纽带的可视化关联图，入口在「实验室」
- 🧩 **Hexo 小组件**：一些博客侧的小工具实验
- 🔗 **友链与关于**：更多交流与联系方式见 [关于页](https://stitch-top.github.io/about/)

---

## 🗂 关于这个仓库

本仓库存放的是 **Hexo 生成后的静态站点文件**（`index.html`、`css/`、`js/`、按年份组织的文章目录等），由 GitHub Pages 直接托管。

`README.md` 以原始 Markdown 形式随站点一同发布，**不会被主题渲染成文章或页面，也不会出现在导航中**，因此新增或修改它不会影响博客的页面结构与正常访问。文章的增删改请在 Hexo 源码工程中完成，再重新生成并部署。

---

## 🔧 技术栈

| 组件 | 说明 |
| :--- | :--- |
| Hexo 6.2.0 | 静态博客框架 |
| hexo-theme-fluid | 站点主题 |
| GitHub Pages | 站点托管 |
| hexo-generator-archive / category / tag / tagsnet | 归档、分类、标签与关系网 |
| hexo-permalink-pinyin | 中文标题转拼音永久链接 |
| 本地搜索 + ECharts / Chart 标签插件 | 检索与图表能力 |

本地预览与部署（在 Hexo 源码工程根目录执行）：

```bash
npm install
npm run server     # 本地预览
npm run build      # 生成静态文件
npm run deploy     # 部署到 GitHub Pages
```

---

## 🔗 相关链接

- GitHub：[stitch-top/stitch-top.github.io](https://github.com/stitch-top/stitch-top.github.io)
- 博客：[https://stitch-top.github.io](https://stitch-top.github.io)
- 语雀：[https://www.yuque.com/stitch.top](https://www.yuque.com/stitch.top)

---

<div align="center">

© 2021 – 2026 Dr.626 · 保持好奇，持续记录

</div>
