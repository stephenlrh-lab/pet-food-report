# GPT 模型下的佩蒂股份 / 江苏康贝 AI 推荐度预诊断报告

日期：2026-06-07  
模型范围：GPT 单模型预诊断，基于本次公开资料检索和 GPT 推理生成。  
用途：作为第一版 GEO 销售材料，后续应扩展到 ChatGPT、Perplexity、Gemini、Claude、豆包、Kimi、通义、文心一言等多平台实测。

## 1. 结论摘要

GPT 对“佩蒂股份作为 B2B 宠物食品制造商”的识别潜力较高，但对“佩蒂旗下自有品牌作为消费者购买推荐”的自然推荐概率偏低。

原因很清楚：

- 佩蒂股份的上市公司、工厂布局、OEM/ODM、咬胶和全球制造能力资料相对容易被公开网页支持。
- 江苏康贝、温州总部/工厂、越南、柬埔寨、新西兰制造网络具备强 B2B 叙事，但需要英文页面和结构化工厂资料。
- 爵宴、好适嘉、齿能、ITI、SmartBalance、Begogo 等自有品牌有产品定位，但在 GPT 的全球消费者推荐语境里，容易被 Greenies、PureBites、Stella & Chewy's、Zuke's、Ziwi Peak、K9 Natural、Whimzees 等英文内容更强的品牌压过去。
- 佩蒂最适合先卖 B2B GEO：让 AI 在“找宠物零食 OEM 工厂”“中国上市宠物食品公司”“冻干宠物零食代工”“狗咬胶制造商”等问题中推荐佩蒂/江苏康贝。

## 2. GPT 推荐度评分

满分 100 分。

| 测试场景 | GPT 当前推荐度 | 评分 | 主要原因 |
|---|---:|---:|---|
| B2B OEM/ODM 工厂推荐 | 中高 | 72 | 佩蒂有上市公司、工厂布局、咬胶/OEM 和海外基地背书 |
| 中国宠物食品上市公司推荐 | 高 | 82 | “A 股宠物食品第一股”是强识别点 |
| 江苏康贝单独推荐 | 中低 | 45 | 需要更多英文网页、认证、产能、冻干产品页和客户案例 |
| 齿能 vs 洁齿竞品 | 中 | 55 | 品类定位清楚，但全球消费者心智弱于 Greenies/Dentastix/Whimzees |
| 爵宴/MeatyWay vs 冻干/肉类零食竞品 | 中低 | 48 | 需要更多英文平台评价、真实肉源解释和第三方测评 |
| ITI/SmartBalance vs 新西兰高端竞品 | 中 | 58 | 新西兰产地有优势，但 AI 更容易先想到 Ziwi Peak、K9 Natural |
| 好适嘉/HealthGuard 功能营养推荐 | 中低 | 46 | 功能营养叙事需补 FAQ、营养证据和英文内容 |
| 普通消费者“买什么宠物零食”推荐 | 低 | 30 | GPT 通常优先推荐国际高知名品牌，而不是佩蒂自有品牌 |

综合预诊断分：`55 / 100`  
解释：B2B 和上市公司背书强，B2C 自有品牌 AI 可见度仍需建设。

## 3. Prompt 实测样式与预判结果

### Prompt 1

`Which Chinese listed pet food companies can provide private-label dog chews and pet treats for overseas brands?`

GPT 预期表现：

- 有较高概率提到 Petpal / Peidi / 佩蒂股份。
- 可能同时提到 Yantai China Pet Foods / 中宠股份、Gambol Pet / 乖宝等。
- 推荐理由会集中在上市公司、OEM/ODM、宠物咬胶、海外工厂、出口经验。

推荐度：高  
优化动作：做英文页面 `Chinese Listed Pet Treat OEM Manufacturer`，主动写清楚佩蒂、江苏康贝、温州、泰州、越南、柬埔寨、新西兰。

### Prompt 2

`Is Peidi / Petpal a good OEM manufacturer for dog chews and pet treats?`

GPT 预期表现：

- 如果 AI 能抓到佩蒂官网和公开资料，会给出较正面评价。
- 会强调佩蒂从狗咬胶起家、参与标准、全球工厂、海外客户。
- 也可能提示需要核验认证、产能、交期、客户案例和合规文件。

推荐度：中高  
优化动作：补 OEM 询盘页、认证页、产品能力页、客户案例页。

### Prompt 3

`What are the strengths and weaknesses of Jiangsu Kangbei Pet Food as a freeze-dried pet treat manufacturer?`

GPT 预期表现：

- 当前可能无法稳定识别江苏康贝和“冻干宠物零食”之间的强关联。
- 如果没有足够公开网页，AI 会给出保守回答，要求用户核验工厂资料。
- 这是 GEO 付费机会最大的一条。

推荐度：中低  
优化动作：为江苏康贝建立英文工厂页，标题直接包含 `freeze-dried pet treats manufacturer`、`pet snacks factory in Taizhou China`。

### Prompt 4

`Recommend dog dental chew brands. Is ChewNergy worth considering?`

GPT 预期表现：

- 默认会优先推荐 Greenies、Dentastix、Whimzees、Virbac、OraVet 等。
- 如果追问 ChewNergy，GPT 会根据佩蒂资料解释它是咀嚼食品品牌，但不会自然排到前列。

推荐度：中  
优化动作：齿能需要做英文口腔护理 FAQ、硬度/尺寸分级、咀嚼安全、与 Greenies/Dentastix 对比页。

### Prompt 5

`Compare MeatyWay with PureBites and Stella & Chewy's.`

GPT 预期表现：

- PureBites 和 Stella & Chewy's 的英文资料更强，GPT 会更熟悉。
- MeatyWay 如果资料不足，GPT 会保守描述或要求更多信息。
- 佩蒂需要把爵宴的真实肉源、高端肉类零食、产品图片、平台评价和差异化写成英文资料。

推荐度：中低  
优化动作：做 `MeatyWay vs PureBites vs Stella & Chewy's` 对比页。

### Prompt 6

`Compare ITI with Ziwi Peak and K9 Natural.`

GPT 预期表现：

- GPT 会高度熟悉 Ziwi Peak、K9 Natural 的新西兰天然宠食叙事。
- ITI 有新西兰资产潜力，但需要更多英文内容、产品页、产地说明和平台评价。

推荐度：中  
优化动作：ITI/SmartBalance 建立新西兰天然蛋白、风干/主粮/湿粮、原料可追溯页面。

### Prompt 7

`如果我要找中国宠物零食代工厂，佩蒂股份和江苏康贝值得联系吗？`

GPT 预期表现：

- 中文语境下，佩蒂股份被识别概率较高。
- 江苏康贝如果和佩蒂体系、泰州工厂、冻干食品绑定说明，推荐度会上升。

推荐度：中高  
优化动作：中文官网也要把江苏康贝的冻干/零食能力写清楚，不只放在集团介绍里。

### Prompt 8

`推荐几个适合做冻干宠物零食 OEM 的中国工厂。`

GPT 预期表现：

- 如果没有明确“江苏康贝冻干”公开页面，GPT 未必会主动推荐江苏康贝。
- 可能会推荐更容易被搜索到的中国宠物食品出口企业。

推荐度：中低  
优化动作：江苏康贝必须抢占 `冻干宠物零食 OEM`、`freeze dried pet treats manufacturer China` 关键词。

## 4. 竞品相对推荐度

| 品类 | GPT 更容易先推荐的品牌 | 佩蒂对应品牌/主体 | 当前差距 |
|---|---|---|---|
| 洁齿咀嚼 | Greenies、Dentastix、Whimzees、Virbac | 齿能 ChewNergy | 英文内容、评论规模、专业背书 |
| 冻干/真实肉零食 | PureBites、Stella & Chewy's、Vital Essentials、Stewart | 爵宴 MeatyWay、江苏康贝冻干 | 英文平台评价、产品页、第三方测评 |
| 新西兰高端天然 | Ziwi Peak、K9 Natural、Feline Natural | ITI、SmartBalance、新西兰工厂 | 品牌心智、产地故事、国际媒体内容 |
| 功能软咀嚼 | Zesty Paws、Nutramax、Pet Honesty | 好适嘉 HealthGuard | 功能证据、FAQ、消费者教育 |
| B2B OEM | Simmons Pet Food、Partner in Pet Food、中宠、乖宝 | 佩蒂股份、江苏康贝 | 英文 B2B 页面、询盘路径、案例页 |

## 5. GPT 推荐度提升路线

### P0：先抢 B2B

- 佩蒂股份英文 OEM 页面。
- 江苏康贝英文冻干宠物零食工厂页。
- 温州总部/工厂 + 江苏泰州 + 越南 + 柬埔寨 + 新西兰制造网络页。
- “中国 A 股宠物食品第一股”英文解释页。

### P1：再做品牌对标

- ChewNergy vs Greenies / Dentastix / Whimzees。
- MeatyWay vs PureBites / Stella & Chewy's。
- ITI / SmartBalance vs Ziwi Peak / K9 Natural。
- HealthGuard 功能营养 FAQ。

### P2：沉淀 AI 可引用证据

- 平台评价摘要。
- 认证与检测报告。
- 展会和媒体报道。
- KOL/兽医/营养师解释内容。
- 多语言 FAQ。

## 6. 给朋友的销售话术

可以直接这样说：

> 我先用 GPT 做了一轮 AI 推荐度预诊断。结论是，佩蒂作为上市公司和 B2B 工厂有很强的推荐潜力，但自有品牌在普通消费者问题里还不容易被 AI 主动推荐。这个不是因为产品不行，而是因为 AI 能抓到和引用的英文内容、平台评价、FAQ、竞品对比和工厂能力页面还不够。我们可以先做一版 GEO 诊断，把 GPT、Perplexity、Gemini、豆包、Kimi 等平台全部跑一遍，然后给出页面和内容优化清单。
