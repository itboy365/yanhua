# 烟花模拟器 🎆

一个基于 Canvas 的交互式烟花模拟器，纯前端实现，开箱即用。

**在线演示** 👉 [itboy365.github.io/yanhua](https://itboy365.github.io/yanhua/)

点击页面任意位置，即可发射烟花。

![预览](Preview.png)

---

## 功能特性

- 🎇 真实的烟花效果：粒子爆炸、重力下落、拖尾残影
- 🖱️ 交互式控制：鼠标点击、触摸屏点击均可发射
- 🎨 可自定义效果：烟花类型、大小、画质、天空光照、缩放
- 📱 响应式设计：PC、平板、手机全端适配
- ⚡ 零依赖：纯 HTML + CSS + JavaScript，无需构建、无需服务器
- 🚀 加载极快：单文件部署，秒开

## 快速开始

直接打开 `index.html` 即可，无需任何环境。

### 本地预览

```bash
# Python
python -m http.server 8000

# Node.js
npx http-server -p 8000
```

然后访问 `http://localhost:8000`。

## 操作说明

| 操作 | 效果 |
|---|---|
| 点击画面任意位置 | 发射烟花 |
| 设置菜单 → 烟花类型 | 切换爆炸形状 |
| 设置菜单 → 烟花大小 | 控制爆炸范围 |
| 设置菜单 → 画质 | 低 / 高 / 极致 |
| 设置菜单 → 自动放烟花 | 开启后自动随机发射 |
| 设置菜单 → 全屏 | 切换全屏模式 |
| 设置菜单 → 保留火花 | 模拟长曝光效果 |

## 项目结构

```
yanhua/
├── index.html          # 主页面
├── style.css           # 样式
├── favicon.png         # 图标
├── Preview.png         # 预览图
├── js/
│   ├── MyMath.js       # 数学计算
│   ├── Stage.js        # 舞台渲染
│   ├── fscreen.js      # 全屏 API
│   └── script.js       # 主逻辑
├── LICENSE
└── README.md
```

## 致谢

本项目基于以下作者的成果进行二次修改：

- **XgpNwb** — 原始作者（英文版）
- **NianBroken** — 中文化及二次修改 · [GitHub](https://github.com/NianBroken/Firework_Simulator) · [Gitee](https://gitee.com/nianbroken/Firework_Simulator)

## 许可证

[MIT License](LICENSE) © 2026 itboy
