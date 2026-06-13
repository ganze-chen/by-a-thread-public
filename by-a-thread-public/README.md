# 《一线》 / By a Thread

> 一个关于**身体、战争与脐带之线**的交互式数据可视化叙事。
> An interactive data-visualisation essay on bodies, war, and the umbilical line.

两位德国出身的女艺术家——**Paula Modersohn-Becker**(1876–1907)与 **Eva Hesse**(1936–1970)——都让"身体"成为各自时代最激进的突破口，都在创作攀至顶峰时天才早逝。一条线把她们系在一起：它输送生命，也能勒断生命；而战争，是那把剪刀。

**作者 · Author:** Ganze Chen

## 在线查看 · Live

启用 GitHub Pages 后访问：`https://<用户名>.github.io/<仓库名>/`
（Settings → Pages → Source: `main` / root）

本地查看：直接双击 `index.html`，或在本目录运行 `python3 -m http.server 8000` 后打开 `http://localhost:8000`。

## 内容 · Sections

1. **Hero** — 标题与"脐带 / 命悬一线 / 前线"的三重题旨
2. **天赐礼物** — Becker 的孕腹双圆 ↔ Hesse 的层叠双环，隔 59 年对望
3. **星海之中** — 一万余位艺术家的散点，女性仅占约 18%
4. **时间轴** — 两条人生曲线在战争色带上的起伏与剪断（可点击放大）
5. **主题孪生，视觉反转** — 双圆罗盘 + 主导色环：构图孪生、视觉互为镜像
6. **穿插** — 更早的一束光：Suzanne Valadon
7. **尾声** — Hesse 1970 年的绳网，线仍在延伸

## 技术 · Tech

纯静态：手写 HTML / CSS / 原生 JS，无构建步骤。字体来自 Google Fonts。

```
index.html      页面 + 内联样式 + 全部交互脚本
data.js         可视化数据（散点 / 时间轴 / 部门等）
assets/artworks 代表作图片
robots.txt      noindex（未列出）
.nojekyll       让 GitHub Pages 原样托管静态文件
```

## 数据来源 · Data

- [MoMA Collection (Kaggle)](https://www.kaggle.com/datasets/momanyc/museum-collection?select=artworks.csv)
- [Famous Paintings (Kaggle)](https://www.kaggle.com/datasets/mexwell/famous-paintings)
- [art_auction_valuation](https://github.com/lucienxshi/art_auction_valuation)（参考指标维度 / reference for the visual-feature dimensions）

视觉特征（主导色、亮度、边缘、角点等）由 OpenCV 自行提取。

## 图像与许可 · Image credits & license

本作品仅作**非商业的学术 / 教育用途**。Paula Modersohn-Becker 与 Suzanne Valadon 的作品属公有领域（via Wikimedia Commons）；Eva Hesse 作品 © The Estate of Eva Hesse，在此依合理使用原则引用。

For educational, non-commercial use only · © respective rights holders.
