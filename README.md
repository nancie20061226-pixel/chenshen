# 陈燊应援资料站

TF 家族五代练习生陈燊的粉丝向非官方资料站，六视图单文件站点。

- 纯静态：`index.html` 一个文件即全部内容，CSS / JS / 内联 SVG 均已打包进文件
- 视图路由：`#home` 首页 · `#profile` 档案 · `#line` 轨迹 · `#stage` 舞台 · `#team` 数据组 · `#sites` 站姐
- 外链：哔哩哔哩直拍、微博主页与原博、超话、数据组矩阵；字体走 `miaoda.feishu.cn` 自托管镜像
- 无图片依赖，无第三方脚本，无构建步骤

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库（Public 或 Private 均可，Pages 对私有仓库需付费方案）
2. 把本目录里的 `index.html`、`.nojekyll`、`README.md` 三个文件上传到仓库根目录
3. 仓库 Settings → Pages → Source 选 `Deploy from a branch` → Branch 选 `main`、目录选 `/ (root)` → Save
4. 等 1–2 分钟，访问 `https://<你的用户名>.github.io/<仓库名>/`

`.nojekyll` 是空文件，作用是让 Pages 跳过 Jekyll 处理，必须一起上传。

## 本地预览

双击 `index.html` 用浏览器打开即可，也可在目录内任意静态服务器里预览。

## 修改指引

`index.html` 内部按注释分段：

- `<style>` 顶部是配色变量（`--fire` 赤焰红、`--ember` 焰橙、`--ink` 底色、`--paper` 字色）
- 结构依次为进度条、左侧导航 `header.rail`、`main#view-home`、`main#view-profile|line|stage|team|sites`、`footer.pfoot`
- 底部 `<script>` 含进度火线、火星粒子、入场动画、视图路由（含左右方向键切页）、词条点击复制

改文案直接改对应区块，改完保存覆盖上传即可，无需任何构建。

## 说明

本页为粉丝向非官方资料整理，与艺人本人、所属公司及任何官方组织无关，不使用任何商业物料。如有错漏，以官方与授权数据组口径为准。
