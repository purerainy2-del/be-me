# Be Myself · 人生之书

Be Myself 是一款单人互动叙事游戏：玩家在五个生命时刻中，先听见自己的愿望，再面对现实条件，最后看见选择留下的痕迹，并获得重新落笔的机会。

## 本地运行

这是一个无构建依赖的静态网页游戏。直接打开 `game.html` 即可体验；使用本地服务器可以获得更稳定的浏览器行为：

```powershell
python -m http.server 4173
```

然后访问 `http://localhost:4173/game.html`。

## 当前版本

- 五个人生阶段：家庭、学校、工作、亲密关系、此刻
- 两种现实资源起点
- 愿望与行动分离的双层选择
- 玩家原话生成的第四选项
- Canvas 人生图与纸张材质
- 本地存档、显影、反事实重写
- Web Audio 声景开关
- 生成个人书页 PNG

完整的产品方向与技术路线见 [docs/game-design.md](docs/game-design.md)。
