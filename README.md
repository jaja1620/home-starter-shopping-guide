# 两人过日子采购指南

# Home Starter Shopping Guide


一份从毛坯到开火的两人居住采购清单：83 项物品、19 个分类，附预算三档口径与选购参考价。

A move-in shopping list for a two-person household — 83 items across 19 categories, with three budget tiers and reference prices.


## 数据概览 Data Overview

| 指标 Metric | 数值 Value |
| --- | --- |
| 物品总数 Total items | 83 项 / 83 items |
| 分类数 Categories | 19 个 / 19 categories |
| 必买 Must-buy | 66 项 / 66 items，30,239 元 / CNY 30,239 |
| 选配 Optional | 17 项 / 17 items，7,843 元 / CNY 7,843 |
| 完整版预算 Full version | 38,082 元 / CNY 38,082 |
| 基础版预算 Essentials only | 30,239 元 / CNY 30,239 |
| 租房精简版 Rental-lite version | 19,839 元 / CNY 19,839 |

## 目录 Contents

| 中文 | English |
| --- | --- |
| [采购清单（83 项完整明细）](docs/purchase-checklist.md) | [Purchase checklist (all 83 items)](docs/purchase-checklist.md) |
| [采购指南（预算、挑选原则、下单顺序、省钱时机）](docs/buying-guide.md) | [Buying guide (budget, principles, ordering, timing)](docs/buying-guide.md) |
| [家电大件选购（五类实测机型与价格）](docs/appliance-guide.md) | [Major appliances (five categories, models and prices)](docs/appliance-guide.md) |
| [保修与发票登记表](docs/warranty-register.md) | [Warranty and invoice register](docs/warranty-register.md) |
| [入住前 7 天待办时间轴](docs/move-in-timeline.md) | [Pre-move-in 7-day timeline](docs/move-in-timeline.md) |

## 快速开始 Quick Start

> 仓库内提供的是双语 Markdown 版；配套 Word 与 Excel 印刷版为中文单语，未随仓库分发。
> This repository ships the bilingual Markdown edition; the Chinese-only Word and Excel print editions are not bundled here.

### 用 Excel 版 Use the Excel version

1. 打开配套 Excel 工作簿（未随仓库分发），在“采购清单”页逐行核对数量；仓库内等价内容见 [采购清单](docs/purchase-checklist.md)。
   Open the companion Excel workbook (not bundled) and review quantities row by row; the bilingual equivalent is [purchase-checklist.md](docs/purchase-checklist.md).

2. “是否已有”填“是”，对应金额会自动从实际支出中扣减；“是否已购”记录下单进度。
   Set “是否已有” (already owned) to “是”, and the amount is deducted from actual spending automatically; use “是否已购” (purchased) to track order progress.

3. “分类汇总”“预算建议”两页由公式联动，改数量后自动重算。
   The “分类汇总” (category summary) and “预算建议” (budget advice) sheets recalculate automatically via formulas.


### 用 Word 版 Use the Word version

1. 打开配套 Word 版（未随仓库分发），先看第一章三档预算口径，确认自己属于哪一档；仓库内等价内容见 [采购指南](docs/buying-guide.md)。
   Open the companion Word edition (not bundled) and start with the three budget tiers; the bilingual equivalent is [buying-guide.md](docs/buying-guide.md).

2. 第三章按 19 个分类列明细，第四章讲大家电选购与安装前置条件，第五章补日用小件。
   Chapter 3 lists items by category, chapter 4 covers major appliances and installation prerequisites, chapter 5 covers small daily necessities.

3. 附录一为保修与发票登记表，附录二为入住前 7 天待办时间轴，可直接打印填写。
   Appendix 1 is a warranty & invoice log; appendix 2 is a 7-day pre-move-in timeline — both printable.


## 文件结构 File Structure

```text
github_export/
├── README.md                     # 项目说明 / Project overview
├── LICENSE                       # MIT 许可（英文正文） / MIT license (English text)
├── LICENSE.zh-CN.md              # MIT 许可中文对照译文 / Chinese reference translation
├── .gitignore                    # 忽略 Office 临时文件与系统文件 / Ignores Office temp and OS files
└── docs/
    ├── purchase-checklist.md     # 83 项完整清单（中英对照） / Full 83-item checklist (bilingual)
    ├── buying-guide.md           # 预算、挑选原则、下单顺序、省钱时机 / Budget, principles, ordering, timing
    ├── appliance-guide.md        # 五类家电实测机型与价格区间 / Five major appliances: models and price ranges
    ├── warranty-register.md      # 保修与发票登记表（可打印） / Warranty and invoice register (printable)
    └── move-in-timeline.md       # 入住前 7 天待办时间轴 / Pre-move-in 7-day timeline
```

## 价格说明 Price Note

所有价格为 2026 年中国主流电商平台的参考成交区间，非实时报价，实际支出随品牌、促销与地区安装费浮动 ±15% 属正常。

All prices are reference price ranges on mainstream Chinese e-commerce platforms in 2026, not live quotes. Actual spending varies with brand, promotions and local installation fees; a ±15% deviation is normal.


## 许可 License

本项目采用 MIT 许可证：英文正文见 [LICENSE](LICENSE)，中文对照译文见 [LICENSE.zh-CN.md](LICENSE.zh-CN.md)。

This project is released under the MIT License: see [LICENSE](LICENSE) for the English text and [LICENSE.zh-CN.md](LICENSE.zh-CN.md) for the Chinese reference translation.
