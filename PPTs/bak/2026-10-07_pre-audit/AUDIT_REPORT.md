# CSC163 PPTs 审查与更新记录（2026-10-07）

原文件备份：`PPTs\bak\2026-10-07_pre-audit\`（12 个 pptx，逐字节校验一致）。以下改动均已原地写入 `PPTs\` 下的 pptx（不含子文件夹）。

## 1. 删除隐藏页（共 235 张）
| 文件 | 原页数 → 现页数 | 删除张数 |
|---|---|---|
| 1_overview | 78 → 42 | 36 |
| 3_single_agent_safety LONG | 134 → 50 | 84 |
| 4_safety_engineering | 68 → 67 | 1 |
| 5_complex_systems | 44 → 37 | 7 |
| 6_machine_ethics | 85 → 66 | 19 |
| 7_collective_action_problems | 111 → 68 | 43 |
| 8_governance | 76 → 71 | 5 |
| 9_normative_ethics_background | 77 → 33 | 44 |
10_utility_functions、2_AI_fundamentals、3_single_agent_safety、L0 course overview 本来没有隐藏页。

## 2. 已修改的内容
**事实/数值错误**
- 9_ 第 23 页（Drunk Driving）：期望效用 `-49.5` → `-49.05`；事故概率 `.5` → `.05`。
- 4_ 第 60 页：`-$10000` → `-$10,000`（与同页写法统一）。

**时效性更新（已联网核对）**
- 8_ 第 33/34/70 页：OpenAI 已于 2025-10 重组为 PBC（OpenAI Group PBC，由 OpenAI Foundation 控制，利润上限取消），原 "capped for profit" 表述改为"此前采用…，现已…"。
- 8_ 第 3、51 页：UK AI Safety Institute → UK AI Security Institute（2025-02 更名）。

**错别字/语病**
- 1_：`Satya Nadella’s of Microsoft`；`1970 Ford motors’ Ford pinto` → `Ford Pinto (1970s)`；`100× times` → `100×`；备注 `discrete`→`discreet`、`LLms`→`LLMs`。
- 3_（两个版本）：`more robust to is adversarial training` → `…robust to attacks is…`；`possibility deterministic`→`possibly`；`highschool`→`high school`；`language model has.Questions`；`microrganisms`；`aims to identifying`。
- 4_：`Tails events`→`Tail events`（4 处 Roadmap）；`consecutive number nines`；`elevator breaks`→`brakes`；`increasing advanced`→`increasingly advanced`；`preferable anonymous`→`preferably`；`Black swans high-impact…`→`Black swans are…`。
- 5_：`These system are`；`The systems can change its`；`Reduced of the depletion`；`sustain effort`。
- 6_：`GDP measure`→`measures`；`desires.Example`；`has elitism complaints`→`have`；`account moral uncertainty`→`account for`。
- 7_：`cutting corners of safety`→`on safety`；第 16 页备注 `see slide 42` → `see slides 24–26`（原页码已失效）。
- 8_：`may also increased`；`indispensable part training`→`part of training`；第 49/50/51 页标题 `(1/2),(1/2),(2/2)` → `(1/3),(2/3),(3/3)`。
- 9_：`are do not permissible`；`following following`；`some some deontologists`。
- 10_：`wins takes home`；`treat them equality`；`change of $5 million`→`chance`（4 处）；`occured`；`suggests`→`suggest`。

**因删除章节而调整的 Roadmap/Recap**
- 6_：Roadmap/Recap 共 6 处删去 "Social Welfare Functions: Make AIs maximize total wellbeing"（该章节页已全部删除）。
- 9_：第 3/6/19 页 Roadmap 删去 Virtue Ethics / Social Contract Theory / Moral Uncertainty；第 20 页 "four most common theories" → "two of the most common theories" 并删去对应两条；第 33 页 Recap 删去 virtue ethics、social contract theory、moral parliaments 的描述。

**页码**：所有 slide-number 域的缓存文字已刷新为当前页号（PowerPoint 本来就会自动重算，此处只是让其他查看器也一致）。

## 3. 发现但未改（需你决定）
- 1_ 第 8 页（图片页）"White House Executive Order"：Biden EO 14110 已于 2025-01 被撤销。
- 8_ 第 5 页：`query companies with Defense Production Act` 依赖上述已撤销行政令。
- 8_ 第 28 页："xAI and Anthropic are PBCs"；xAI 已并入 SpaceX，法律形式需核实。
- 8_ 第 51 页："Treaties: No current examples" 与 2024 年开放签署的欧洲委员会《人工智能框架公约》不符。
- 8_ 第 50 页：Summits 只列 UK 与 France，可考虑补充 2026 年印度峰会。
- 7_ 第 29 页：OpenAI charter 的 "merge-and-assist" 条款在重组后是否仍适用需核实。
- 5_ 第 27 页："We examine this in more detail in the chapter: Collective Action Problems"，但 7_ 中对应的 Intrasystem goal conflict / Sub-goals / Delegation 页已作为隐藏页被删除。
- 6_ 第 12 页："Fortunately, AI companies have to exercise reasonable care, but AIs do not yet have to" 语义自相矛盾。
- 6_ 第 17 页：COMPAS "partially successful lawsuit" 说法需核实；第 35 页 Easterlin paradox 的描述不准确；第 47 页把 DPO 描述为"人类对输出排序"（更接近 RLHF 的偏好数据收集）。
- 9_ 第 10/11 页：Alice 的例子写的是选举候选人，但示例语句是 "AI's output X"，第 11 页又用 Google vs ChatGPT，示例前后不一致。
- 8_ 第 19 页 "viruses can kill humans destroy some AIs" 缺连接词；第 22 页 "Stability" 一段重复。
- 3_ 第 18 页备注 `TODO: remake plot; current plot contains FashionMNIST results`；4_ 第 46/47 页备注 `Comment on relation to ongoing harms…` 仍是未完成的 TODO。
- 3_ 等页脚同时出现 "Introduction to ML Safety" / "Center for AI Safety" 与 "Introduction to AI SES"（来源幻灯片残留）。
- 2_ 第 4 页历史时间轴止于 ChatGPT/Transformer，如需可补充近年节点。

## 4. 其他
- `L0 course overview.pptx` 我没有改动；其 Office hours 你已自行改为周五 8:00–10:00，与课程网站一致。
- 文件夹里的 `.pdf` 是旧导出，页数与现在的 pptx 不再对应，需要时请重新导出。
