# 华中科技大学本科毕业设计（论文）LaTeX 模板（2026）

基于 [HustGraduPaper](https://github.com/hust-latex/hustthesis) v2.1.7 修改，适用于华中科技大学本科毕业设计（论文）的撰写。

## 主要修改

- 参考文献格式调整为 GB/T 7714-2015 标准
- 预置 TikZ 流程图配色与样式，可快速绘制学术风格插图
- 表格样式统一为 tabularx + booktabs 三线表

## 文件说明

| 文件 | 作用 |
|:---|:---|
| `article.tex` | 论文主源码 |
| `HustGraduPaper.cls` | 华科毕设 LaTeX 模板类文件 |
| `mybib.bib` | 参考文献数据库（含格式示例） |

## 使用方法

1. 安装 TeX Live（推荐）
2. 修改 `article.tex` 中的个人信息（标题、姓名、学号、院系、导师）
3. 在 `mybib.bib` 中填入参考文献条目
4. 编译： XeLaTeX → BibTeX → XeLaTeX → XeLaTeX
5. 生成的 `article.pdf` 即为最终论文

## 字体说明

**本模板不包含中文字体文件**，需要使用者自行准备。默认配置调用 Windows 系统自带的宋体和黑体。

如果你仍在使用系统默认的宋体和黑体，模板开头的 `\documentclass[supercite]{HustGraduPaper}` 即可直接编译。但如果你的电脑上没有这些字体或者你想换其他字体，也需要自行下载和配置。
