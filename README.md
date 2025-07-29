
# Poe链接对话提取器 (Poe Link Conversation Extractor)

🌐 [点击这里在线访问 / Live Demo](https://zhang-lecheng.github.io/poe-extractor/)

---

## 🧩 简介 | Introduction

这是一个基于网页的工具，用于从文本中提取 [Poe.com](https://poe.com/) 对话链接，并自动抓取链接页面中的对话内容。用户粘贴包含链接的文本后，点击按钮即可批量获取内容，并支持复制汇总结果。

This is a web-based tool to extract [Poe.com](https://poe.com/) conversation links from input text and fetch the conversation content from each URL. Users can paste multiple links, extract messages with one click, and copy the results easily.

---

## ✨ 功能特点 | Features

- 🚀 从文本中自动提取有效的 Poe 对话链接  
- 🔎 自动抓取链接页面的对话内容并格式化展示  
- 📋 一键复制全部对话汇总内容  
- 🔁 支持多链接处理  
- 🌙 简洁美观的前端界面，无需登录或注册

---

## 📦 项目结构 | Project Structure

```

📁 poe-extractor
├── index.html  # 主网页文件（Main HTML file）
└── README.md   # 本文件（This file）

````

---

## 🚀 使用方式 | How to Use

### 在线使用（推荐） | Online Usage (Recommended)
👉 打开页面：[https://zhang-lecheng.github.io/poe-extractor/](https://zhang-lecheng.github.io/poe-extractor/)

1. 粘贴包含 Poe 链接的文本（每行一个，或用空格分隔）
2. 点击“提取并获取对话”
3. 等待加载完成后，可点击“复制所有内容”按钮导出文本

---

## 🛠 本地运行 | Run Locally

如需离线使用：

```bash
git clone https://github.com/zhang-lecheng/poe-extractor.git
cd poe-extractor
open index.html  # 或直接在浏览器打开 index.html
````

---

## 💡 技术说明 | Technical Notes

* 本工具通过 `fetch` 结合 `https://api.allorigins.win` 代理绕过跨域限制抓取 HTML 内容。
* 页面使用 JavaScript 原生 DOM 解析器提取对话内容，无需依赖后端。
* 前端设计简洁响应式，兼容主流浏览器。

---

## 📄 许可证 | License

本项目采用 [MIT License](LICENSE)。

This project is licensed under the MIT License.

---

## 🙌 鸣谢 | Acknowledgements

* [Poe.com](https://poe.com/) 提供内容来源
* [All Origins](https://allorigins.win/) 提供跨域代理 API
* HTML/CSS/JS 编写参考了多种开源界面组件设计风格

---

