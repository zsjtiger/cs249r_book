# 中文译本术语表与翻译约定（卷一、卷二）

本文件是 `dev-chinese-book` 分支的翻译规范。所有章节译文须遵守此表，术语一经确定不得随意更改。

## 翻译范围

- **翻译**：正文段落、标题、列表、表格中的文字、脚注、图注（`fig-cap`、`fig-alt`）、表注、提示框（callout）标题与正文、交互式 HTML 中的可见文字。
- **保持不变**：
  - 所有代码块（```` ``` ````，包括 `{python}` 计算块）及其内容，包括代码注释；
  - 行内代码（反引号内的内容）；
  - 标签与交叉引用：`{#sec-…}`、`{#fig-…}`、`{#tbl-…}`、`{#eq-…}`、`{#lst-…}`、`@sec-…`、`@fig-…`、`@tbl-…`、`@eq-…`、`[@key]` 引文键；
  - 文件路径、图片路径、URL、HTML/CSS/JS 标签与属性（属性中的可见文字如 `alt`、`title` 除外）；
  - LaTeX 命令与数学公式（`$…$`、`$$…$$`）的结构；数学符号不变，公式周围的说明文字翻译；
  - `\index{…}` 条目内容保持英文原文（索引生成依赖原文，不做改动）；
  - YAML 前置元数据的键名。`title`、`pagetitle`、`description-meta` 等可见字符串翻译。
- 引用的论文标题、会议名、书名：正文中保留英文原名，并在首次出现时给出中文说明（如"Karpathy 的《Software 2.0》"）。

## 语言与排版

- 使用中文全角标点（，。；：“”（）、），专有名词与缩写保留英文。
- 中文与英文或数字之间不额外加空格。
- 数字、单位、公式保持原文；单位写法沿用中文习惯，但数值不变（如 `100 ms` 可写作 `100 毫秒`，但若原文在代码中则保持）。
- 译文忠实原文：不增删论点，不意译成与原文不同的结论。

## 核心术语

| 英文 | 中文 | 备注 |
|---|---|---|
| Machine learning systems | 机器学习系统 | |
| Iron law (of ML systems) | 铁律（机器学习系统铁律） | |
| Data-Algorithm-Machine (D·A·M) | 数据-算法-机器（D·A·M） | 分类法名称：D·A·M 分类法 |
| Software 1.0 / 2.0 | 软件 1.0 / 软件 2.0 | |
| Data-as-code principle | 数据即代码原则 | |
| Data-centric AI | 以数据为中心的 AI | |
| Degradation equation | 退化方程 | |
| Return on compute | 算力回报 | |
| Silent quality loss / silent degradation | 无声的质量下降 | |
| Dual mandate | 双重使命 | |
| Model weights | 模型权重 | |
| Inference | 推理 | |
| Training | 训练 | |
| Serving / model serving | 服务 / 模型服务 | |
| Stochastic gradient descent (SGD) | 随机梯度下降（SGD） | |
| Hidden technical debt | 隐性技术债 | |
| Learning objectives | 学习目标 | 提示框标题 |
| War story | 实战案例 | `callout-war-story` 的标题 |
| Purpose | 目的 | 章节的 PIPO 段落标题 |
| Fleet | 集群 | 卷二中的 fleet，指大规模加速器集群 |
| Edge | 边缘 | |
| Accelerator | 加速器 | |
| GPU | GPU | 缩写保留 |
| Latency | 延迟 | |
| Throughput | 吞吐量 | |
| Bandwidth | 带宽 | |
| Memory hierarchy | 存储层级 | |
| Benchmark / benchmarking | 基准测试 | |
| Quantization | 量化 | |
| Pruning | 剪枝 | |
| Distillation | 蒸馏 | 知识蒸馏 |
| Checkpoint | 检查点 | |
| Data pipeline | 数据管道 | |
| Feature | 特征 | 机器学习语境 |
| Label | 标签 | |
| Drift / data drift | 漂移 / 数据漂移 | |
| Skew / training-serving skew | 偏差 / 训练-服务偏差 | |
| Monitoring | 监控 | |
| Hallucination | 幻觉 | |
| Fairness | 公平性 | |
| Robustness | 鲁棒性 | |
| Privacy | 隐私 | |
| Sustainability | 可持续性 | |
| Collective communication | 集合通信 | |
| All-reduce | All-Reduce | 原语名保留英文 |
| Parallelism | 并行 | 数据并行 / 模型并行 / 流水线并行 |
| Fault tolerance | 容错 | |
| Orchestration | 编排 | |
| Network fabric | 网络结构 | |
| Interconnect | 互连 | |

## 章节结构用语

- 章节的 `## Purpose`、`## Learning Objectives` 等标题统一译为“目的”、“学习目标”等。
- `::: {.callout-…}` 的 `title` 属性译为中文，类型名保持英文。

## 待定项（遇到时在此补充并统一）

- 随译随补充。
