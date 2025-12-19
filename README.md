# [好伙伴们](https://www.owo.cab/friends/)

## 成为好伙伴

### 本站信息

- 名称: `拾星絮语`
- 链接: `https://www.owo.cab`
- 图标: `https://static.owo.cab/avatar.webp`
- 简介: `银汉凝睫上，璇玑坠瞳渊~`

### 前置条件

- 文章数量不少于 15 篇，**原创**内容不少于 80%；
- 无违法内容，无弹窗等影响用户体验的内容，可接受**一定程度**的推广内容；
- 全站启用**强制 HTTPS** 访问；
- **不接受**包括但不限于 [Public Suffix List](https://publicsuffix.org/list/public_suffix_list.dat) 列出的免费域名及托管商分配域名；
- **原则上不接受**含有不适合在公共场合展示 (NSFW) 内容的网站；
- 添加反向友链。

## 提交规范

1. 将你的站点图标提交到 `images` 目录下，路径和文件命名规则如下：

   - 路径: `/images/<YOUR_DOMAIN>/`
   - 文件: `avatar.webp|png|jpg|svg`
   
   路径中的 `<YOUR_DOMAIN>` 需与追加在 `linklist.yml` 中站点链接的域名一致，不包含协议前缀；
   
   仅接受 `webp`, `png`, `jpg`, `svg` 格式，建议使用 `webp` 或 `svg` 格式，图片大小不超过 `200KB`。

3. 将你的站点信息追加到 `linklist.yml` 中，格式如下：
   
   ```yaml
   - title: "<TITLE>"  # 站点标题
     description: "<DESCRIPTION>"  # 一句话描述
     image: "/images/<YOUR_DOMAIN>/avatar.(webp|png|jpg|svg)"  # 上传的图标
     link: "https://<YOUR_DOMAIN>"  # 站点链接
   ```

## 开启 PR 后会发生什么

- 等待流水线运行检查，若流水线未通过，可以通过流水线日志来定位问题，也可以看看改动是否符合[提交规范](#提交规范)；
- 在 PR 被合并后的 24 小时内，你的网站会在[这里](https://www.owo.cab/friends/)展示。

网站失联一段时间后会被移除。若站点信息有变更，可以重新开启 PR 来更新站点信息~
