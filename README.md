# 🎮 TrollDash · 无厘头整蛊闯关

> 卡通沙雕风整蛊解谜小游戏 | 10关脑洞大开 | 翻车比通关更好玩

## 🚀 在线游玩

**[leonis77.github.io/wwwlucky-Game](https://leonis77.github.io/wwwlucky-Game)**

## 📖 游戏介绍

TrollDash 是一款"反套路"整蛊解谜游戏。每一关都有一个看似正常的操作方式——但按常规思路必定翻车。你需要**另辟蹊径**，发现隐藏的通关方法。

| 关卡 | 名称 | 整蛊点 |
|------|------|--------|
| 🐸 1 | 点击开始 | 按钮疯狂逃跑，点空白处3次通关 |
| 😴 2 | 叫醒小人 | 点击月亮而非小人 |
| 🚪 3 | 开门 | 拖动门而非点击把手 |
| 🦟 4 | 消灭蚊子 | 点击电蚊香吸引蚊子ZAP |
| 🍬 5 | 拿到糖果 | 翻转手机（桌面端点底部手动翻转）|
| ☁️ 6 | 赶走乌云 | 向右滑动屏幕 |
| 🌊 7 | 渡过河流 | 待揭秘... |
| 🔐 8 | 破解密码 | 待揭秘... |
| 🕯 9 | 点燃蜡烛 | 待揭秘... |
| 🔑 10 | 终极挑战 | 待揭秘... |

## 🛠 项目结构

```
wwwlucky-Game/
├── public/                  # 🚀 部署目录（GitHub Pages 指向这里）
│   └── index.html           #    单文件游戏
├── src/                     # 📦 源码目录（未来模块化）
│   ├── css/
│   └── js/
│       └── levels/
├── tools/                   # 🔧 构建工具
├── docs/                    # 📚 文档
│   └── GAME_DESIGN.md
└── README.md
```

## 🏗 技术栈

- 纯 HTML5 Canvas + 原生 JavaScript
- Web Audio API 音效系统
- Web Speech API 语音鼓励
- DeviceOrientation API 陀螺仪交互
- 零依赖，单文件即部署

## 📦 部署

推送到 GitHub 后，在仓库 Settings → Pages 中设置 Source 为 `main` 分支，目录选 `/public`。

```bash
git push origin main
```

## 🎨 设计理念

1. **卡通沙雕风** — 色彩鲜亮，人物魔性，适配全年龄段
2. **失败即乐趣** — 每关翻车有专属整蛊动画和吐槽
3. **脑洞成就系统** — 奇葩成就 + 沙雕称号
4. **轻量低成本** — 纯前端，零服务器成本

## 📄 License

MIT
