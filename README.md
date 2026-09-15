# 珀斯往返西澳自驾攻略

一家三口西澳自驾旅行页面，日期为 2026-11-11 到 2026-11-23，出发点和结束点均为珀斯。

## 页面入口

- 完整攻略：`index.html`
- 行程总表：`itinerary-overview.html`
- 手绘地图公网压缩版：`handdrawn-itinerary-map-public.jpg`
- 手绘地图高清备份：`handdrawn-itinerary-map.png`

## GitHub Pages 发布

1. 在 GitHub 新建仓库，例如 `perth-family-roadtrip`。
2. 上传本目录下所有文件。
3. 进入仓库 `Settings` -> `Pages`。
4. `Source` 选择 `Deploy from a branch`。
5. `Branch` 选择 `main`，目录选择 `/root`。
6. 保存后等待 1-2 分钟。

发布后地址通常是：

```text
https://你的GitHub用户名.github.io/perth-family-roadtrip/
```

## 本地预览

如果在本目录启动静态服务，可以访问：

```text
http://localhost:8787/
http://localhost:8787/itinerary-overview.html
```

## 说明

- 页面是纯静态 HTML/CSS/JS，不需要构建。
- `handdrawn-itinerary-map-public.jpg` 用于网页展示，加载更快。
- `handdrawn-itinerary-map.png` 是高清原图备份，可按需保留或不上传。
