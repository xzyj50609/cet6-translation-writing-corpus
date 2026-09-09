# CET-6 Translation & Writing Corpus

> 大学英语六级（CET-6）历年翻译与作文全量精选语料库
>
> A Clean, Markdown-Native Corpus of CET-6 Translation & Writing Authentic Questions

[![CET-6](https://img.shields.io/badge/Exam-CET6-blue?style=flat-square)](https://neea.edu.cn)
[![Translation](https://img.shields.io/badge/Translation-73%20sets-green?style=flat-square)](#01)
[![Writing](https://img.shields.io/badge/Writing-30%20sets-orange?style=flat-square)](#02)
[![Format](https://img.shields.io/badge/Format-Markdown-black?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](./LICENSE)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2025.12-red?style=flat-square)](#)

---

## 📖 项目简介 / Introduction

这是一个**纯净、无排版杂质、Markdown 原生**的大学英语六级真题语料库。市面上的六级真题多为扫描版 PDF 或排版混乱的 Word 文档，本仓库将 2015–2025 年全部翻译真题与 2022–2025 年全部作文真题清洗为结构化 Markdown，并附带十年命题趋势深度分析。

This is a **clean, impurity-free, Markdown-native** corpus of CET-6 authentic exam questions. Unlike scattered scan PDFs and messy Word documents found online, this repository provides fully cleaned translation passages (2015–2025) and writing prompts (2022–2025), along with in-depth trend analysis.

---

## 📊 数据概览 / Data Overview

| 数据集 | 时间范围 | 数量 | 说明 |
|--------|---------|------|------|
| 🈶 翻译真题 | 2015.06 – 2025.12 | **73 套** | 段落汉译英，含 4 个特殊场次 |
| ✍️ 作文真题 | 2022.06 – 2025.12 | **30 套** | 给定首句续写，含完整 Directions |
| 📈 趋势分析 | — | **2 篇** | 翻译十年母题图谱 + 作文命题趋势推演 |

---

## 📂 目录结构 / Directory Structure

```text
cet6-translation-writing-corpus/
├── README.md                          # 本文件
├── LICENSE                            # MIT 开源协议
├── 01_历年翻译真题_2015-2025/
│   ├── README.md                      # 翻译题检索目录与母题索引
│   └── 六级翻译全量题库_73篇.md        # 73 篇纯净翻译原文（带锚点跳转）
├── 02_历年作文真题_2022-2025/
│   ├── README.md                      # 首句续写作风指南与分类
│   ├── 六级作文首句续写题库_30套.md    # 30 套 Directions + 给定首句
│   └── 作文分类与三轨覆盖分析.md       # 六大分类 + 三套模板 + 万能例句
└── 03_命题趋势深度分析/
    ├── 六级翻译十年母题全图谱.md       # 翻译命题逻辑与时代分期
    └── 六级作文命题趋势与押题推演.md   # 作文四轨趋势与方向评估
```

---

## 🚀 快速导航 / Quick Links

### 🈶 翻译真题
- [01_历年翻译真题_2015-2025/README](./01_历年翻译真题_2015-2025/README.md) — 母题分类速查表
- [六级翻译全量题库_73篇.md](./01_历年翻译真题_2015-2025/六级翻译全量题库_73篇.md) — 全部 73 篇，按时间倒序，带锚点目录

### ✍️ 作文真题
- [02_历年作文真题_2022-2025/README](./02_历年作文真题_2022-2025/README.md) — 题型结构与六大分类
- [六级作文首句续写题库_30套.md](./02_历年作文真题_2022-2025/六级作文首句续写题库_30套.md) — 全部 30 套 Directions 与首句
- [作文分类与三轨覆盖分析.md](./02_历年作文真题_2022-2025/作文分类与三轨覆盖分析.md) — 分类表 + 3 套高覆盖模板 + 4 个万能例句

### 📈 命题趋势分析
- [六级翻译十年母题全图谱.md](./03_命题趋势深度分析/六级翻译十年母题全图谱.md)
- [六级作文命题趋势与押题推演.md](./03_命题趋势深度分析/六级作文命题趋势与押题推演.md)

---

## 📋 翻译十年母题分布 / Translation Theme Distribution

| 时代分期 | 年份 | 代表母题 |
|---------|------|---------|
| 🏷️ 文化名片期 | 2015–2016 | 旗袍、深圳、待客之道、汉朝 |
| 📚 题组化知识期 | 2017–2019 | 朝代、湖泊、名花、语言文化 |
| 🏗️ 成就叙事期 | 2020–2022 | 超级工程、红色历史、地理国情 |
| 📋 时政语体期 | 2023–2025 | 老龄化、科技自立、传统美德、战略工程 |

---

## ✍️ 作文题型锁定 / Writing Format Lock-in

自 2022.06 起，**连续 8 个场次、30 个题位**全部为同一题型：

> 给定首句 → 30 分钟 → 150–200 词 → 须原样抄写首句

三大主题轨道：
- **永恒品质轨**：自律、目标、独立学习、职业准备
- **时代议题轨**：数字素养、AI、社交媒体
- **价值方向轨**：合作、助人、青年与国家

---

## 🛠️ 数据清洗说明 / Cleaning Notes

本语料库经过以下清洗流程：

1. **去除元信息**：移除 PDF 页码、排版残留、OCR 噪声字符
2. **修正 OCR 错误**：作文首句中的典型识别错误（如 `students5` → `students'`、`selAworth` → `self-worth`）已逐一修正
3. **结构化排版**：统一 Markdown 标题层级，添加锚点跳转目录
4. **保留原文**：题目中括号内的英文注释（真题原卷给出的参考译法）原样保留
5. **不添加译文**：本仓库仅收录中文原文（翻译）和英文题目（作文），不提供参考译文，以保持语料纯净

---

## 📄 开源协议 / License

本仓库采用 [MIT License](./LICENSE) 开源协议。你可以自由使用、修改和分发，但请保留原始版权声明。

This project is licensed under the **MIT License** — feel free to use, modify, and distribute, but please retain the original copyright notice.

---

## ⭐ 如果你觉得有帮助 / If You Find This Useful

如果这个语料库对你的六级备考或 NLP 研究有帮助，欢迎 **Star** ⭐ 本仓库！

If this corpus helps your CET-6 preparation or NLP research, feel free to **Star** ⭐ this repository!

---

<div align="center">
<sub>Built with ❤️ for CET-6 test-takers and language researchers worldwide</sub>
</div>