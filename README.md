# 外贸独立站资源大全 | Awesome Cross-border DTC & Independent E-commerce

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg) [![Stars](https://img.shields.io/github/stars/sasharun/awesome-waimao-dulizhan?style=social)](https://github.com/sasharun/awesome-waimao-dulizhan) ![Last update](https://img.shields.io/badge/last%20update-2026--11-blue.svg)

> 一份关于**外贸独立站**的精选资源清单，长期更新。聚焦**独立站搭建**、**Shopify 独立站**、**WooCommerce / WordPress 独立站**、**Headless 自建站**，覆盖建站平台选型、**2026 AI 智能体购物（Agentic Commerce）与关税/合规应对**、主题模板、**跨境支付收款**、**独立站广告投放**（Google / Meta / TikTok）、**独立站 SEO 与内容引流**、转化率优化（CRO）、数据分析、**独立站运营**工具栈与出海学习资源。
>
> 搜索词对齐：外贸独立站 · Shopify独立站 · WooCommerce外贸站 · 跨境独立站 · Headless电商 · 询盘站 · 工厂官网

无论你是做 DTC 品牌、铺货转型品牌，还是工厂 / 外贸卖家从亚马逊转向自有独立站，这里把「从 0 到 1 到运营」的工具与方法一次理清。

---

## 📮 关于 & 建站服务

**Gavin**，**模酷科技（ModalCube）** 主理人，专注**外贸独立站 / 询盘站 / 工厂站**。主力栈 **Next.js** 与 **WordPress / WooCommerce**，优先速度、SEO 与可维护性。

**服务：** 外贸独立站 / DTC · B2B 询盘站 / 工厂官网 · Google SEO 与 CWV · 多语言多货币 · Stripe/PayPal · Vercel/Cloudflare 部署

> 📧 xqi@live.com　💬 微信 gav1nq　🌐 https://modalcube.com　📖 [外包建站避坑指南](https://modalcube.com/jianzhan-guide)

**开源配套（本账号）：**
- [nextjs-export-starter](https://github.com/sasharun/nextjs-export-starter) — Next.js 外贸/工厂**询盘站**模板（双语 SEO + Resend）
- [dulizhan-inquiry-checklist](https://github.com/sasharun/dulizhan-inquiry-checklist) — 有流量没询盘自查清单

---

## ⚡ 30 秒选型

| 你的情况 | 更合适 | 说明 |
|----------|--------|------|
| 最快上线卖货 / 测品 | **Shopify** | 运维少、App 多、广告和 AI 渠道接得好 |
| 预算紧、重内容 SEO | **WordPress + WooCommerce** | 长期成本低，要自己管主机与安全 |
| 工厂 B2B、只要询盘 | **Next.js 询盘站 / 轻量 WP** | 见 [starter](https://github.com/sasharun/nextjs-export-starter) |
| 极致性能 + 完全控制 | **Next.js + Medusa / Hydrogen** | 开发成本高，适合有规模的定制站 |
| 华语团队、本地支付物流一体 | **SHOPLINE / Shoplazza** | 上手快，深度定制弱于纯 Shopify |

**B2B 询盘 vs B2C 商城：** 询盘站 = 规格讲清 + 表单能收到 + Google 能搜到；商城 = 结账顺 + 支付稳 + 税费透明 + 物流可追踪。别一上来堆 App。

---

## 📑 目录

- [⚡ 30 秒选型](#-30-秒选型)
- [🤖 2026 必看：AI 智能体购物与关税合规](#-2026-必看ai-智能体购物与关税合规)
- [🏗️ 建站平台选择](#️-建站平台选择)
- [⚙️ Headless / 自建站](#️-headless--自建站技术栈)
- [🎨 主题与模板](#-主题与模板)
- [💳 支付与收款](#-支付与收款)
- [📦 货源与一件代发](#-货源与一件代发dropshipping--pod)
- [📢 广告投放](#-广告投放google--meta--tiktok)
- [🔍 SEO 与内容](#-seo-与内容引流)
- [🚀 CRO](#-转化率优化cro与应用)
- [📊 数据分析](#-数据分析与用户行为)
- [🌐 多语言 / 物流 / 合规](#-多语言--多货币--物流与合规)
- [🕵️ 选品与竞品](#️-选品与竞品分析)
- [📚 学习资源](#-学习资源与社区)
- [❓ FAQ](#-常见问题faq)
- [🧰 补充资源包](#-补充资源包)
- [🔗 相关清单](#-相关清单)

---

## 🤖 2026 必看：AI 智能体购物与关税合规

2025–2026 年做外贸独立站，有两条绕不开的结构性变化：

1. **小额包裹免税时代结束**：美国 $800 de minimis 豁免已全面无限期暂停（2025-05 中港、2025-08 全球，2026-06 写入 CBP 规章，2027-07 法定废除）；欧盟 €150 以下包裹免税已于 2026-07-01 取消（改为每件 €3 临时关税 + IOSS）。低客单直邮铺货利润被大幅压缩，**填全 HS Code/原产地、结账 DDP 完税、爆款备海外仓、提升客单价**成为标配。
2. **AI 智能体开始直接带货（Agentic Commerce）**：买家越来越多地在 ChatGPT、Google AI 模式 / Gemini、Copilot 里问推荐甚至直接结账。商品结构化数据（价格、库存、GTIN、规格、退换政策）越干净，越容易被 AI 推荐。

- [Shopify Editions Fall '26](https://www.shopify.com/editions/fall2026) — 2026 秋季核心更新：智能体商务（Agentic）、Shopify Connectors 与新版 Sidekick。
- [Shopify Agentic Storefronts](https://www.shopify.com/agentic-storefronts) — 后台统一管理 AI 购物渠道的曝光、目录资格与知识库。
- [Shopify Catalog](https://www.shopify.com/catalog) — 将合规商品目录自动同步给 AI 购物入口的官方索引机制。
- [Universal Commerce Protocol (UCP)](https://ucp.dev/) — Shopify 与 Google 联合推出的智能体商务开放协议（发现 → 结账标准化）。
- [Shopify 关税和进口税指南](https://help.shopify.com/zh-CN/manual/international/duties-and-import-taxes) — 结账代收关税（DDP）、HS Code 与原产地配置官方中文文档。
- [Avalara 小额免税政策解读](https://www.avalara.com/us/en/blog/de-minimis-exemption-changes-coming.html) — 美国 Section 321 暂停时间线、Entry Type 13 与欧盟 €3 新规速查。

---

## 🏗️ 建站平台选择

- [Shopify](https://www.shopify.com/) — 全球主流电商 SaaS，外贸独立站新手首选，对 AI 渠道与多市场支持最全。
- [WooCommerce](https://woocommerce.com/) — WP 免费电商插件，长期成本低、SEO 友好。
- [BigCommerce](https://www.bigcommerce.com/) — 中大型 / 复杂品类 SaaS，不收交易抽佣。
- [SHOPLINE](https://www.shopline.com/) — 华语跨境友好，支付物流集成完善。
- [Shoplazza](https://www.shoplazza.com/) — 国内团队跨境独立站，铺货与运营工具全。
- [Wix](https://www.wix.com/) / [Squarespace](https://www.squarespace.com/) — 轻量展示 / 品牌视觉向。
- 🌟 选型拿不准：xqi@live.com（或先看 [外包建站避坑指南](https://modalcube.com/jianzhan-guide)）

## ⚙️ Headless / 自建站技术栈

- [Next.js](https://nextjs.org/) — Headless 前端首选，性能与 SEO 控制力强。
- [Medusa](https://medusajs.com/) — 开源无头电商引擎，常配 Next.js。
- [Saleor](https://saleor.io/) — GraphQL Headless，大目录友好。
- [Shopify Hydrogen](https://hydrogen.shopify.dev/) — Shopify 官方自定义店面。
- [Vercel Commerce](https://github.com/vercel/commerce) — Next.js 电商骨架。
- [Strapi](https://strapi.io/) / [Sanity](https://www.sanity.io/) — Headless CMS（博客 / 产品内容）。
- [Cloudflare](https://www.cloudflare.com/) — CDN / WAF / Pages，海外访问底座。
- 🌟 [nextjs-export-starter](https://github.com/sasharun/nextjs-export-starter) — 开源 B2B 询盘站模板，Fork → Vercel。

## 🎨 主题与模板

原则：轻量优先，速度即转化。

- [Dawn](https://themes.shopify.com/themes/dawn/styles/default) — Shopify 官方免费旗舰主题。
- [Shopify Theme Store](https://themes.shopify.com/) — 官方主题市场。
- [Debutify](https://debutify.com/) — 转化向 Shopify 主题。
- [Astra](https://wpastra.com/) / [GeneratePress](https://generatepress.com/) / [Kadence](https://www.kadencewp.com/kadence-theme/) — 高性能 WP 主题。
- [ThemeForest](https://themeforest.net/) — 付费主题市场（看评分与更新）。

## 💳 支付与收款

常见组合：**信用卡收单 + 钱包 + 多币种提现**，多通道抗风控；欧美高客单建议补 **BNPL（先买后付）** 与 **DDP 完税结账**。

- [Stripe](https://stripe.com/) — 全球收单，开发者友好，配套 [Stripe Tax](https://stripe.com/tax) 自动算税。
- [PayPal](https://www.paypal.com/) — 高信任钱包，补充转化。
- [Shopify Payments](https://www.shopify.com/payments) — 原生支付，免平台交易抽佣。
- [Global-e](https://www.global-e.com/) — 跨境 DTC 常用 MoR（Merchant of Record），代管多国关税、本地支付与合规结账。
- [2Checkout / Verifone](https://www.2checkout.com/) — 跨境本地支付覆盖。
- [Payoneer](https://www.payoneer.com/) — 收款与多币种提现。
- [Airwallex](https://www.airwallex.com/) — 收单 + 多币种账户。

## 📦 货源与一件代发(Dropshipping / POD)

> 提醒：美欧小额免税取消后，纯低价直邮代发毛利大幅缩水；建议优先选**欧美本土仓/海外仓发货**、**POD 差异化高溢价**或**批量头程备货**。

- [CJdropshipping](https://cjdropshipping.com/) — 中国供应链 + 欧美海外仓。
- [DSers](https://www.dsers.com/) — AliExpress 官方合作铺货。
- [Spocket](https://www.spocket.co/) — 美/欧本土供应商，时效与清关风险更低。
- [Printful](https://www.printful.com/) / [Printify](https://printify.com/) — 按需打印（POD），支持欧美本地生产发货。
- [Zendrop](https://zendrop.com/) — 自动化 dropshipping 与定制包装。
- [1688](https://www.1688.com/) — 源头批发（自配头程 + 海外仓代发）。

## 📢 广告投放(Google / Meta / TikTok)

- [Google Ads](https://ads.google.com/) + [Merchant Center](https://www.google.com/retail/solutions/merchant-center/)
- [Meta Ads](https://www.facebook.com/business/tools/ads-manager) + [Meta Pixel](https://www.facebook.com/business/tools/meta-pixel)
- [TikTok Ads](https://ads.tiktok.com/)
- [Triple Whale](https://www.triplewhale.com/) — DTC 归因
- [Northbeam](https://www.northbeam.io/) — 进阶多触点归因

## 🔍 SEO 与内容引流

- [Google Search Console](https://search.google.com/search-console)
- [Ahrefs](https://ahrefs.com/) / [Semrush](https://www.semrush.com/) / [Ubersuggest](https://neilpatel.com/ubersuggest/)
- [Screaming Frog](https://www.screamingfrog.co.uk/seo-spider/)
- [Rank Math](https://rankmath.com/) / [Yoast](https://yoast.com/wordpress/plugins/seo/)
- [Surfer SEO](https://surferseo.com/)
- 更全 → [awesome-waimao-seo](https://github.com/sasharun/awesome-waimao-seo)
- 🌟 不收录 / 排名不动可附站发 xqi@live.com

## 🚀 转化率优化(CRO)与应用

- [Judge.me](https://judge.me/) / [Loox](https://loox.app/) / [Yotpo](https://www.yotpo.com/) — 评论 UGC
- [Klaviyo](https://www.klaviyo.com/) — 邮件/短信自动化（弃单与复购）
- [Vitals](https://vitals.app/) / [ReConvert](https://www.reconvert.io/) — CRO / upsell
- [Hotjar](https://www.hotjar.com/) / [VWO](https://vwo.com/) — 行为与实验
- [Shopify Flow](https://www.shopify.com/flow) — 无代码自动化
- 🌟 有流量没询盘 → [inquiry checklist](https://github.com/sasharun/dulizhan-inquiry-checklist)

## 📊 数据分析与用户行为

- [GA4](https://marketingplatform.google.com/about/analytics/)
- [Microsoft Clarity](https://clarity.microsoft.com/)
- [PageSpeed Insights](https://pagespeed.web.dev/) / [GTmetrix](https://gtmetrix.com/)
- [Google Tag Manager](https://tagmanager.google.com/)

## 🌐 多语言 / 多货币 / 物流与合规

- [Shopify Markets](https://www.shopify.com/markets) / [Markets 帮助文档](https://help.shopify.com/zh-CN/manual/markets) — 多市场定价、语言、货币与关税配置。
- [Weglot](https://www.weglot.com/) / [TranslatePress](https://translatepress.com/) / [WPML](https://wpml.org/) / [LangShop](https://langshop.io/) — 网站多语言与 hreflang 管理。
- [17TRACK](https://www.17track.net/) / [AfterShip](https://www.aftership.com/) / [Shippo](https://goshippo.com/) — 国际物流追踪与打单。
- [EU VAT OSS / IOSS 官方站](https://vat-one-stop-shop.ec.europa.eu/index_en) — 销往欧盟必备的增值税与小包申报入口。
- [EU GPSR 产品安全官方指南](https://single-market-economy.ec.europa.eu/single-market/european-standards/harmonised-standards/general-product-safety_en) — 欧盟通用产品安全法规（EU 2023/988），独立站销欧需在商品页清晰标明制造商、欧代与安全警示。

## 🕵️ 选品与竞品分析

- [Google Trends](https://trends.google.com/)
- [Koala Inspector](https://koala-apps.io/)
- [Sell The Trend](https://www.sellthetrend.com/) / [Exploding Topics](https://explodingtopics.com/)
- [SimilarWeb](https://www.similarweb.com/)

## 📚 学习资源与社区

- [Shopify Academy](https://www.shopify.com/learn) · [帮助中心中文](https://help.shopify.com/zh-CN)
- [雨果跨境](https://www.cifnews.com/) · [知无不言](https://www.wearesellers.com/) · [AMZ123](https://www.amz123.com/)
- [LOYSEO](https://loyseo.com/) · [增长黑盒](https://growthbox.net/)
- 建站避坑与案例：[外包建站避坑指南](https://modalcube.com/jianzhan-guide) · https://modalcube.com

---

## ❓ 常见问题(FAQ)

**平台怎么选？** 卖货快 → Shopify；SEO/低成本 → Woo；B2B 询盘 / 性能 → Next.js（[starter](https://github.com/sasharun/nextjs-export-starter)）。

**多少钱？** SaaS 订阅+App；Woo 主机+开发；定制看多语言/Headless/设计。先最小可用再迭代，外包前建议先过一遍 [避坑指南](https://modalcube.com/jianzhan-guide)。

**收款？** 常见 Stripe + PayPal + Payoneer/Airwallex，多通道；多国完税结账可评估 Global-e 或 Shopify Managed Markets。

**2026 美欧小包取消免税，独立站还能做吗？** 能，但**低客单价纯直邮铺货基本跑不通了**。现在主流是把客单价做高、把 HS Code 与 DDP 关税算进定价/结账、爆款前置到海外仓或走 POD 本地生产；B2B 询盘站走一般贸易批量出货，受小包新政影响小得多。

**AI 购物（ChatGPT / Gemini）怎么接？** 用 Shopify 的优先在后台 `Sales channels > Agentic` 检查 Shopify Catalog 资格并补齐商品结构化属性和退换货知识库；自建站务必做好 `Product / Offer / FAQ` JSON-LD 结构化数据，并关注 [UCP](https://ucp.dev/) 协议进展。

**没流量？** 广告测品 + SEO 打底 + 邮件再营销。

**多语言？** 只做英语可先不做；欧拉东南亚再上语言+货币。

---

## 🧰 补充资源包

- [Shopify Dev Docs](https://shopify.dev/docs) · [Shopify Agentic Commerce Docs](https://shopify.dev/docs/agents)
- [Google 电商 SEO](https://developers.google.com/search/docs/specialty/ecommerce)
- [Cloudflare Turnstile](https://developers.cloudflare.com/turnstile/) — 表单防机器人（免费、无需烦人的滑块）
- [FactoryBase](https://factorybase.ai) — Next.js 做的工厂核验目录（全静态 + GEO + MCP），工厂免费登录档案页，可被海外买家和 AI 搜到，独立站之外的一个补充曝光位。

| 模板 | 用途 |
|------|------|
| 启动包 | 品类、国家、客单、毛利、HS Code 与关税、物流/海外仓、收款、SKU、预算 |
| 商品页 | 卖点、规格、场景图、FAQ、评价、结构化数据、欧盟 GPSR 责任人信息（销欧时） |
| 广告承接 | 素材、落地页、像素、UTM、加购/结账率、弃单邮件 |

---

## 🔗 相关清单

- [外贸建站](https://github.com/sasharun/awesome-waimao-jianzhan)
- [出海建站](https://github.com/sasharun/awesome-chuhai-jianzhan)
- [外贸 SEO](https://github.com/sasharun/awesome-waimao-seo)
- [工厂官网](https://github.com/sasharun/awesome-gongchang-website)
- [询盘转化清单](https://github.com/sasharun/dulizhan-inquiry-checklist)
- [Next.js 询盘 Starter](https://github.com/sasharun/nextjs-export-starter)

---

## 🤝 贡献

欢迎提交 PR 或 Issue 补充优质资源或报告死链，详细标准见 [CONTRIBUTING.md](CONTRIBUTING.md)：

```markdown
- [名称](https://example.com) — 一句中文说明。
```

---

## 📈 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sasharun/awesome-waimao-dulizhan&type=Date)](https://star-history.com/#sasharun/awesome-waimao-dulizhan&Date)

## 📜 License

[CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/)

---

### 定制外贸站 / 询盘站 / 工厂站

> 📧 xqi@live.com　💬 gav1nq　🌐 https://modalcube.com

<table align="center">
  <tr>
    <td align="center" width="50%"><img src="assets/qr-fuwuhao.png" width="170" alt="微信"><br><b>模酷科技 · 微信</b></td>
    <td align="center" width="50%"><img src="assets/qr-gongzhonghao.png" width="170" alt="服务号"><br><b>模酷科技 · 服务号</b></td>
  </tr>
</table>

有用请 Star ⭐
