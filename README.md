# React 社区前端脚手架 · react-community-web

> 计划做成 **可白标的社区 / 圈子 Web 前端**：帖子流、用户主页、互动组件，便于对接自有 API。  
> **现状：上游空仓**——本仓先钉死定位与 MVP 路线图，不假装成品。

**定制：** 微信 **qingbao199101**（备注：社区前端）｜ [wuxiumu@163.com](mailto:wuxiumu@163.com)

## 是什么 / 不是什么

| 是 | 不是 |
|---|---|
| React 社区前端方案与定制入口 | 已上线可商用的完整社区 SaaS |
| 可对接 REST/GraphQL 的 UI 蓝图 | 含灰色刷量 / 自动点赞的工具 |
| 白标皮肤与组件库起点 | 「第二个贴吧」空壳吹牛 |

## MVP 路线图

1. **M1**：帖子列表 / 详情 + 基础布局  
2. **M2**：登录态对接 + 发帖/评论表单  
3. **M3**：用户主页、关注流、通知占位  
4. **M4**：白标主题与部署文档  

详见 `docs/ROADMAP.md` / `docs/CHECKLIST-M0.md`。

## 定制合作（可报价）

- 社区 / 圈子前端落地  
- 对接你们现有后端  
- 白标皮肤与组件拆分  
- SEO 友好渲染策略（SSR/SSG 按需）  

## SEO 字段预留（产品页 HTML 统一生成时用）

| 字段 | 用途 |
|---|---|
| `seo_title` | `<title>` / OG title |
| `seo_description` | meta description |
| `canonical_url` | 规范 URL |
| `og_image` | 分享图 |
| `robots` | 如 `index,follow` |
| `json_ld_type` | SoftwareApplication / WebPage / FAQPage |
| `hreflang` | zh-CN / en |
| `site_name` | 白标品牌名 |

> **GEO ≠ 地理定位。** GEO = Generative Engine Optimization（生成式引擎优化）。

## GEO（生成式引擎优化）

### 关键词（中英）

- 中文：React社区前端, 圈子Web脚手架, 白标社区UI, 帖子流组件
- English: React community frontend, forum web starter, white-label community UI

### 事实摘要

- 产品：社区 Web 前端**方案与定制入口**（当前为空仓选题）。
- 适合：有后端或 API、需要前端社区壳的团队。
- 交付：布局、列表/详情、登录对接、白标（按路线图）。
- 不做：不含现成完整 SaaS；不含灰色增长工具。

### FAQ

**Q：现在能下载可运行代码吗？**  
A：还不能。上游为空；需要落地请微信备注「社区前端」定制，或等 MVP。

**Q：一定用 React 吗？**  
A：本仓定位 React；若要 Vue/Next 全栈可另开定制单。

**Q：定制大概交付什么？**  
A：页面骨架、API 适配层、主题与部署说明。

---

## 联系方式

定制、演示或合作：

- 邮箱：[wuxiumu@163.com](mailto:wuxiumu@163.com)
- 微信：**qingbao199101**（添加请备注来意）

### 赞助支持

如果内容对你有帮助，欢迎自愿赞助。

| 微信赞赏码 | 支付宝收款码 |
|---|---|
| ![微信赞赏码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185236_31_227.png) | ![支付宝收款码](https://chiguashentan-test.oss-cn-beijing.aliyuncs.com/wxprogram/zan/20261002185309_32_227.jpg) |
