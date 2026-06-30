# 坦克大战 (Tank Battle)

一个使用纯 HTML5 Canvas + JavaScript 制作的 2D 坦克大战游戏。无需任何依赖，直接打开 `index.html` 即可游玩。

## 在线试玩

GitHub Pages 部署后可通过以下地址访问：
`https://ytao03313-hash.github.io/tank-battle/`

## 操作说明

| 按键 | 操作 |
|------|------|
| `W` / `↑` | 前进 |
| `S` / `↓` | 后退 |
| `A` / `←` | 左转 |
| `D` / `→` | 右转 |
| `空格键` | 开火 |
| `Enter` | 开始 / 重新开始 |

## 游戏目标

- 消灭所有敌方坦克即可进入下一关
- 共有 3 个关卡，难度逐渐提升
- 玩家有 3 条生命，生命耗尽则游戏结束
- 利用墙壁作为掩体，摧毁墙壁可获得额外分数

## 游戏特性

- 🎮 流畅的 Canvas 实时渲染
- 🤖 敌方坦克简单 AI：巡逻 + 追击玩家
- 💥 子弹碰撞、墙体破坏、爆炸粒子效果
- 🏆 分数、生命、关卡 HUD 显示
- 📱 自适应全屏画布

## 本地运行

```bash
git clone https://github.com/ytao03313-hash/tank-battle.git
cd tank-battle
# 直接用浏览器打开 index.html
start index.html
```

## 技术栈

- HTML5
- CSS3
- 原生 JavaScript (ES6+)

## 许可证

MIT
