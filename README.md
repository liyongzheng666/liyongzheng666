<!-- ============ 样本 3：工程蓝图版 ============ -->
<!-- 最贴合 CAD 工程师身份：图纸标题栏 + Mermaid 架构图（GitHub 原生渲染）+ 工程规格表 -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&color=0:0a2540,100:1e5f8a&height=200&text=LI%20YONGZHENG%20%C2%B7%20%E6%9D%8E%E6%B0%B8%E6%AD%A3&fontSize=40&fontColor=e8f4fd&animation=fadeIn&desc=ENGINEERING%20DRAWING%20No.%20LYZ-2026%20%C2%B7%20AI%20%2B%20CAD%20KERNEL%20ENGINEER&descSize=14&descAlignY=68" alt="header" />

<div align="center">

| 图号 DWG No. | 名称 TITLE | 材料 MATERIAL | 比例 SCALE | 版本 REV |
| :-: | :-: | :-: | :-: | :-: |
| `LYZ-2026` | AI + CAD 造型内核算法工程师 | C++ / Python / OCCT | 1 : 1 | 🟢 在研 |

</div>

## 📐 总装图 · General Assembly

> 在研项目：**几何内核缺陷自动排查 Agent** —— 下面这张架构图由 GitHub 原生渲染，不是贴图：

```mermaid
flowchart LR
    A[["📥 建模操作输入<br/>Extrude / Revolve / Sweep"]] --> B{"🛡️ 退化输入防御<br/>Degenerate-Input Defense"}
    B -->|合法| C[["⚙️ 几何内核<br/>OpenCASCADE"]]
    B -->|拦截| X["⚠️ 异常用例入库"]
    C --> D["🤖 缺陷排查 Agent"]
    D --> E{"🔁 验证循环<br/>Verification Loop"}
    E -->|不通过| F["📝 上下文注入<br/>Context Injection"]
    F --> D
    E -->|通过| G[["✅ 缺陷报告<br/>Defect Report"]]
    X --> D
```

## 🔩 零件明细表 · Bill of Materials

| 序号 | 零件 PART | 规格 SPEC | 数量 |
| :-: | :-- | :-- | :-: |
| 1 | 🧱 特征建模 Feature Modeling | 拉伸 Extrude · 旋转 Revolve · 扫描 Sweep | ∞ |
| 2 | 🔁 参数化 Parametric | 阵列 Pattern · 镜像 Mirror | ∞ |
| 3 | ✏️ 直接建模 Direct Modeling | 拔模 Draft · 圆角 Fillet | ∞ |
| 4 | 🤖 AI 工程化 | Agent · 验证循环 · 上下文注入 | 1 套 |
| 5 | 🛠️ 工具链 | C++ · Python · CMake · Git · Linux · Qt | 1 套 |

## 🗂️ 部件图 · Sub-assemblies

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/liyongzheng666/Print">🖨️ Print — 部件图 A</a></h4>
      <p>基于 <b>OpenCASCADE (OCCT)</b> 的 3D 模型查看与打印工具集，浏览器内解析、预览、处理几何。</p>
      <img src="https://img.shields.io/github/stars/liyongzheng666/Print?style=flat-square&logo=github&color=1e5f8a" />
      <img src="https://img.shields.io/badge/type-CAD%20Tool-0a2540?style=flat-square" />
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/liyongzheng666/geometry-engineer-ai-road">📐 geometry-engineer-ai-road — 部件图 B</a></h4>
      <p>几何算法工程师的 <b>12 周 AI 提效课程</b>：验证循环、退化输入防御、上下文注入。</p>
      <img src="https://img.shields.io/github/stars/liyongzheng666/geometry-engineer-ai-road?style=flat-square&logo=github&color=1e5f8a" />
      <img src="https://img.shields.io/badge/type-Course-d97757?style=flat-square" />
    </td>
  </tr>
</table>

## 📏 检验记录 · Inspection Record

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=liyongzheng666&show_icons=true&theme=nord&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=liyongzheng666&layout=compact&theme=nord&hide_border=true&langs_count=8" />
</p>

<p align="center">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=liyongzheng666&theme=nord&hide_border=true&area=true" alt="activity" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/liyongzheng666/liyongzheng666/output/github-snake-dark.svg" />
    <img alt="snake" src="https://raw.githubusercontent.com/liyongzheng666/liyongzheng666/output/github-snake.svg" />
  </picture>
</p>

## 🖋️ 签字栏 · Sign-off

<div align="center">

| 设计 DESIGNED | 校核 CHECKED | 批准 APPROVED | 日期 DATE |
| :-: | :-: | :-: | :-: |
| 李永正 | [GitHub](https://github.com/liyongzheng666) | [📧 Email](mailto:zk545791580@gmail.com) | 持续更新 |

<sub>⚡ 公差范围内交付 · Build kernels · ship fast · stay curious</sub>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1e5f8a,100:0a2540&height=110&section=footer" alt="footer" />
