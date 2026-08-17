# 专有名词库

本文件保存口播字幕的标准写法、常见 ASR 误识别和排版规则。执行时只将别名替换为标准名，前提是上下文明确指向该专名；不把普通词作无条件全局替换。

首次校准时，先将本表作为“预设常用词”展示给用户，并询问是否需要新增、删除或改写；用户确认后的条目才成为其后续自动剪辑的优先词库。

| 标准写法 | 常见 ASR / 输入变体 | 使用与排版规则 |
| --- | --- | --- |
| 不二 | 博二、博尔 | 人名。固定显示为“不二”；“我是博二”等自称按上下文统一为“我是不二”。 |
| Focusee | Foxsee | 产品名。固定显示为 `Focusee`；仅在明确指向该工具时替换。 |
| Vibe Coding | Web coding、vibe coding、VibeCoding | 两词首字母大写，保留一个空格；整词组不拆行、不拆字幕卡。 |
| Cola | cola | 品牌/产品名。首字母大写；只有上下文明确指向该名称时才将“可乐”等近音词改为 `Cola`。 |
| learn in public | leaning public、learning public、learn public | 全小写，保留两个空格分隔；整词组不拆行、不拆字幕卡。 |
| build in public | Build in public、building public、building in public、build public | 全小写，保留两个空格分隔；整词组不拆行、不拆字幕卡。 |
| GitHub | github、Git Hub、github.com | 品牌名：`G`、`H` 大写且不加空格；仅在代码托管、仓库、开源语境下替换。 |
| Supabase | supabase、Superbase、Super base | 品牌名：首字母大写，其余小写；不拆词。 |
| Vercel | vercel、Versel、Vercel | 品牌名：首字母大写，其余小写；不拆词。 |
| OpenAI | openai、Open Ai、Open AI | 品牌名：`O`、`A`、`I` 大写且不加空格。 |
| ChatGPT | chatgpt、Chat GPT、chat GP T | 产品名：`C`、`GPT` 大写且不加空格。 |
| Claude | claude、Cloud、克劳德 | 产品名：首字母大写；只在 AI 助手语境下替换，避免误改人名或普通词。 |
| Cursor | cursor、Cursor AI | 产品名：首字母大写；仅在 AI 编程工具语境下替换。 |
| Replit | replit、Repl it、Replit AI | 产品名：首字母大写；不拆词。 |
| Midjourney | midjourney、Mid Journey | 产品名：`M` 大写且不加空格。 |
| Figma | figma、FIGMA | 品牌名：首字母大写，其余小写。 |
| Notion | notion、Notion AI | 品牌名：首字母大写；仅在产品/知识库语境下替换。 |
| API | api、A P I | 技术缩写：全大写；与中文相邻时不额外插入空格。 |
| SaaS | saas、Saas、S A A S | 技术缩写：全大写。 |
| Seedance | seedance、SeeDance、Seed Dance | 产品名：`S` 大写，其余小写；不拆词。 |
| Seedream | seedream、SeeDream、See Dream、Seed Dream | 产品名：`S` 大写，其余小写；不拆词。 |
| Typeless | typeless、Type less、TypeLess | 产品名：`T` 大写，其余小写；不拆词。 |
| ListenHub | listenhub、Listenhub、Listen Hub | 产品名：`L`、`H` 大写且不加空格。 |

## 新增条目模板

| 标准写法 | 常见 ASR / 输入变体 | 使用与排版规则 |
| --- | --- | --- |
|  |  |  |

## 每条视频的终校步骤

1. 在口播语义清理完成后，搜索本表中每个标准写法及其变体；把已确认的 ASR 错误修正到源文字稿。
2. 完成字幕字体、字号和语义断句后，重新扫描观众实际看到的字幕。
3. 检查英文的大小写、词间空格以及人名用字；多词专名只能整体出现在同一张单行字幕中。若空间不足，在整个短语的前后断句。
4. 视频中未出现的条目保留在库中，供下一条视频自动校对；不因未出现而删除。
