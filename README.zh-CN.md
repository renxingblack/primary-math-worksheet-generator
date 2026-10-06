# primary-math-worksheet-generator
Printable primary-school math worksheet generator for Chinese Grades 1–6. Single HTML file, no install, works offline. 131 grade presets, 32 mental-math shortcut rules, export to PDF / Word / PNG.
面向中国小学 1–6 年级的可打印数学计算练习卷生成器：单 HTML 文件、免安装、可离线。内置 131 套年级预设与 32 条巧算规则，支持导出 PDF / Word / 图片。

# 小学数学计算练习卷生成器（口算|脱式|竖式|方程）

> 面向中国小学数学（1–6 年级）的**可打印计算类练习题生成器**——单个 HTML 文件，双击即用，免安装、免联网、免构建。

<p align="center">
  <img src="assets/screenshot.png" alt="小学数学练习卷生成器 界面" width="900">
</p>

<p align="center">
  <img alt="单文件" src="https://img.shields.io/badge/%E5%8D%95%E6%96%87%E4%BB%B6-HTML-blue">
  <img alt="免安装" src="https://img.shields.io/badge/%E5%AE%89%E8%A3%85-%E6%97%A0-success">
  <img alt="可离线" src="https://img.shields.io/badge/%E7%A6%BB%E7%BA%BF-%E5%8F%AF%E7%94%A8-brightgreen">
  <img alt="预设" src="https://img.shields.io/badge/%E9%A2%84%E8%AE%BE-131%E5%A5%97-orange">
  <img alt="协议" src="https://img.shields.io/badge/%E5%8D%8F%E8%AE%AE-MIT-lightgrey">
</p>

[English](README.md) · **简体中文**

---

## 这是什么

一个完全自包含的 HTML 出题工具，用于生成**可打印的小学数学练习卷**，覆盖 1–6 年级上下册。
内置 **131 套年级预设** 与 **32 条巧算（简便计算）规则**，出的题按"先定好算数再反推算式"
的方式构造，接近老师手写讲义的效果，而不是随机凑数。

全部计算都在浏览器本地完成：没有后端、没有账号、不采集任何数据。

## 出题样例

<p align="center">
  <img src="assets/sample-shortcut-rules.png" alt="脱式巧算练习卷" width="440">
  <img src="assets/sample-decimals.png" alt="小数练习卷" width="440">
</p>

左：由巧算规则反向构造的**脱式**题，递等式写出每一步中间结果。
右：小数"找朋友"乘法。两张图都截自工具的实时预览，可直接导出 PDF / Word。

## 功能

### 一、四大题型

| 题型 | 说明 |
|---|---|
| **口算** | 横式，直接写得数 |
| **二项竖式** | 加减乘除竖式，按单元格排列 |
| **脱式计算** | 递等式，逐步求值（巧算/简算的主战场） |
| **方程** | 一元一次方程，解为有理数 |

脱式题型由 **32 条巧算规则**驱动，题目**反向构造**（先定好算数，再回填算式）：

> 提公因数 · 分配律（正向）· 加法凑整 · 减法性质 · 带符号搬家 · 乘法凑整 · 除法性质 ·
> 接近整百拆分 · 隐藏的"×1" · 接近整百加法 · 多减要加 / 多加了要减 · 基准数法 ·
> 借一换一（等比数列）· 高斯配对（等差数列求和）· 提取公除数 · 去括号变号 · 积的变化规律 ·
> 两位数乘 11 · 头同尾合十 · 平方差公式 · 叠字型多位数（×101）· 裂项相消 · 小数凑整 ·
> 小数找朋友 · 小数乘法分配律 · 换元法（小数）· 商不变性质 · 分数提取公因数 ·
> 添加因数"1" · 分数加减凑整 · 分数与小数混合简算 · 尾同头合十

每条规则都可单独勾选/关闭。

### 二、131 套年级预设（1–6 年级 · 上下册）

| 一年级上册 | 一年级下册 | 二年级上册 | 二年级下册 | 三年级上册 | 三年级下册 |
|---:|---:|---:|---:|---:|---:|
| 4 | 5 | 8 | 4 | 12 | 7 |

| 四年级上册 | 四年级下册 | 五年级上册 | 五年级下册 | 六年级上册 | 六年级下册 |
|---:|---:|---:|---:|---:|---:|
| 31 | 18 | 16 | 9 | 11 | 5 |

选定预设即**一键套用整套设置**（题型、数值范围、小数、分数、百分数、排版…），12 秒内可撤销。

### 三、打印排版

- **纸张**：A3 / A4 / B5 / Letter，横向或纵向，页边距、对称页边距
- **网格**：列数 × 排数、列间距、行间距、自动均衡
- **字体**：中文（宋体 / 黑体 / 楷体 / 仿宋 + 本机字体选择）、西文（Times New Roman / Arial /
  Georgia / Consolas / Courier New / DejaVu Mono）；完整中文字号（初号 → 小五）；加粗；变量字母斜体
- **标题**：大标题、副标题、间距规则、数学符号与英文单词两边加空格
- **页面**：页码（起始页、`(1)` / `（一）` / `第 X 页`）、页眉页脚、水印、多页分段
  （＋ 添加分段、分段重排、分段重设页码）
- **答案区**：答案汇总、辅导做题区、显示序号
- **去重**：同页去重 / 同段去重 / 连续去重

### 四、数值与内容控制

每项行的整数位、小数位、取值上下限；商 / 积 / 被除数 / 除数约束（整除、有余、禁止 0 或 1、
禁止末尾零）；分数设置（真分数 / 假分数 / 最简分数、分数题包含）；百分数应用；解比例；文字题。

### 五、导出

| 格式 | 说明 |
|---|---|
| **文字版 PDF** | 文字可选中、可搜索，保真度高 |
| **图片版 PDF** | 整页为一张图片，体积小、不依赖字体 |
| **PNG / JPEG / SVG** | 单页图片导出 |
| **Word（.docx）** | 浏览器内直接生成 OOXML（不依赖第三方文档库） |
| **ZIP** | 打包批量导出 |
| **JSON** | 导出 / 导入**全部设置**，精确复现某一份卷子 |
| **打印** | 调用浏览器原生打印 |

支持"全部页"或按页码范围导出。公式渲染使用 MathJax。

## 快速开始

### 方式 A —— 直接使用（推荐）

1. 下载 [`primary-math-worksheet-generator.html`](primary-math-worksheet-generator.html)
2. 双击打开（Edge / Chrome / Firefox / Safari 均可）
3. 左侧选一个年级预设，点 **打印** 或 **开始导出**

> 免安装；出题与打印无需联网。
> 仅在导出 PDF / 图片 / ZIP 与渲染公式时**按需**联网加载 JSZip、jsPDF、html2canvas（jsDelivr）与 MathJax。

### 方式 B —— 在线使用（GitHub Pages）

若本仓库已开启 Pages，直接访问
`https://renxingblack.github.io/primary-math-worksheet-generator/`
即可，`primary-math-worksheet-generator.html` 会被直接托管，无需下载。

### 方式 C —— 克隆

```bash
git clone https://github.com/renxingblack/primary-math-worksheet-generator.git
cd primary-math-worksheet-generator
# 然后用浏览器打开 primary-math-worksheet-generator.html
```

### 方式 C —— 下载exe文件（需要WebView支持）


## 使用说明

### 使用预设
1. **选预设**：右上角“常见题型”下拉框（按年级 / 册分组）挑一个基础题型。
2. **详细微调**：在左侧设置栏目，详细微调达到自己需要的效果。
### 自定义
1. **设置题量**：在页面设置中设置列数、排数（列数 × 排数的结果即为一页总题数）。
2. **选题型**：口算 / 二项竖式 / 脱式计算 / 方程，并设定是否需要分数、括号。
3. **设数值范围**：打开各类题型的具体设置，根据需要设置每项的整数位、小数位与上下限；展开 巧算（简便计算） 勾选要练的规则（巧算为实验性栏目，可不勾选）。
4. **调打印排版**：纸张、页边距、列数、标题、字体、字号、行间距、页码、水印——右侧预览实时更新。
5. **导出或打印**：**打印** 出纸质卷；**开始导出** 出 PDF / 图片 / Word / ZIP。
### 导入配置
用 **导出设置**（JSON）保存配置，**导入设置** 下次一键还原。

## 仓库结构

```
primary-math-worksheet-generator.html          # 全部功能都在这一个文件里（约 570 KB）
assets/
  screenshot.png            # 整体界面
  sample-shortcut-rules.png # 出题样例 — 脱式巧算
  sample-decimals.png       # 出题样例 — 小数
  social-preview.png        # 1280×640 社交预览图
README.md           # English
README.zh-CN.md     # 简体中文
LICENSE
```

## 技术说明

- **单文件**：一个 `primary-math-worksheet-generator.html`，内联 `<style>` 与内联 IIFE `<script>`，约 12,000 行 / 570 KB。
  无框架、无打包器、无 `node_modules`。
- **零依赖设计**：随机出题、有理数运算、表达式树、排版计算、`.docx`（OOXML + ZIP）写出，
  全部用原生 JS 从头实现。
- **可选 CDN**（仅导出或需渲染公式时）：MathJax(tex-svg)、jsPDF、html2canvas、JSZip。
- **界面语言**：简体中文。

## 常见问题

**需要联网吗？**
出题与打印不需要；导出 PDF / 图片 / Word / ZIP 需要首次联网（这些库按需从 jsDelivr 拉取），
之后一般走浏览器缓存。

**有答案吗？**
有。可开启**答案汇总**随卷打印；脱式题的递等式包含每一步中间结果。

**题目会重复吗？**
在设定范围内不会——提供"同页 / 同段 / 连续"三种去重开关。

**数据会被上传吗？**
不会。所有内容都不离开你的浏览器。

## 参与贡献

欢迎分享自己的预设。bug修复随缘，本人小白，全AI对话生成程序，该项目主要是自用。

## 开源协议

[MIT](LICENSE)
