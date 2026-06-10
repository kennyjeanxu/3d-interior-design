# 🏠 3D 室内装修设计 | 3D Interior Design Studio

一个基于 **Three.js** 的交互式 3D 室内装修设计工具，可直接在浏览器中运行。

An interactive 3D interior design tool built with **Three.js**, runs directly in the browser.

## ✨ 功能 Features

- 🛋️ **9种家具** — 沙发、茶几、餐桌、椅子、床、书架、落地灯、地毯、电视柜
- 🎨 **实时换色** — 墙壁、地板、天花板颜色自由切换
- 🖱️ **直观操作** — 点击选择家具 → 点击地板放置
- 🔄 **旋转家具** — 按 R 键或点击按钮旋转家具方向
- 🗑️ **删除管理** — 选中后按 Delete 删除，支持一键清空
- 📐 **网格参考** — 可开关的地面网格辅助线
- 🎥 **自由视角** — 右键旋转视角、滚轮缩放、中键平移
- 📱 **响应式设计** — 适配桌面和移动设备

## 🚀 快速开始 Quick Start

1. 克隆仓库：
```bash
git clone https://github.com/YOUR_USERNAME/3d-interior-design.git
```

2. 直接用浏览器打开 `index.html` 即可使用。

或使用任意 HTTP 服务器：
```bash
# Python
python -m http.server 8080

# Node.js
npx serve .
```

## 🎮 操作指南 Controls

| 操作 | 方式 |
|------|------|
| 选择家具 | 左侧工具栏点击家具图标 |
| 放置家具 | 在 3D 视图中点击地板 |
| 取消放置 | 按 `Esc` 键 |
| 旋转家具 | 按 `R` 键（放置前/选中后） |
| 选中家具 | 在 3D 视图中点击已放置的家具 |
| 删除家具 | 选中后按 `Delete` 键 |
| 旋转视角 | 鼠标右键拖拽 |
| 缩放 | 鼠标滚轮 |
| 平移视角 | 鼠标中键拖拽 |
| 切换网格 | 按 `G` 键 |

## 🛠️ 技术栈 Tech Stack

- [Three.js](https://threejs.org/) — 3D 渲染引擎
- 纯 HTML/CSS/JavaScript — 零依赖、零构建
- Import Map CDN 加载

## 📄 License

MIT
