# zhengcheng-readme
Algorithm engineer specializing in computer vision &amp; deep learning. Built end-to-end systems: 3D pose estimation from sparse point clouds, real-time human tracking &amp; sensing. Proficient in Python, PyTorch, C++, Qt. Passionate about solving complex engineering challenges and deploying efficient models. AI-assisted dev advocate.
<!-- 头部横幅 -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,100:8b5cf6&height=200&section=header&text=Zheng%20Cheng&fontSize=60&animation=fadeIn&fontAlignY=38&desc=Algorithm%20Engineer%20|%20M.S.%20in%20Software%20Engineering&descAlignY=55&descAlign=50" />
</div>

<br />

<div align="center">
  
  [![Email](https://img.shields.io/badge/Email-13138952456@163.com-blue?style=for-the-badge&logo=gmail)](mailto:13138952456@163.com)
  [![Phone](https://img.shields.io/badge/Phone-18665933659-green?style=for-the-badge&logo=phone)](tel:18665933659)
  [![Location](https://img.shields.io/badge/Location-Guangdong%20Bay%20Area-red?style=for-the-badge&logo=location)]()

</div>

---

## 👨‍ About Me

**算法工程师** | 硕士学历 | 5 年 + 研发经验

专注于**深度学习算法研发**与**工程化落地**。具备从学术研究到产业落地的完整技术栈，擅长解决**稀疏数据处理**、**时序建模**、**多模态融合**等核心算法问题。

- 🔬 **研究方向**：点云处理、人体姿态估计、时序预测、微弱信号提取
- 🏗️ **工程能力**：独立完成数据采集→模型训练→推理优化→系统部署全链路
- 📊 **学术成果**：发表 SCI 论文 2 篇（二区/三区各 1 篇）
- ⚡ **技术理念**：算法价值在于落地，追求精度、效率、稳定性的最佳平衡

---

## 🛠️ Core Competencies

| 类别 | 技术栈 |
|------|--------|
| **编程语言** | `Python`(主力) `C++` `CUDA` |
| **深度学习** | `PyTorch` `TensorFlow` `Transformer` `CNN/RNN` |
| **数据处理** | `点云处理` `时序分析` `数据增强` `特征工程` |
| **工程框架** | `Qt5` `Linux` `Docker` `Git` |
| **模型优化** | `模型剪枝` `量化加速` `边缘部署` `性能调优` |
| **AI 提效** | `Cursor` `Trae` `Copilot` (日均提升 40% 编码效率) |

---

## 🔥 Featured Projects

### 🎯 稀疏点云人体姿态估计系统
> **算法挑战**：输入数据极度稀疏（每帧 20-80 个点），需预测 32 个高维度关节点，传统方法失效。

<div align="center">
  <!-- 视频/GIF 展示区域 -->
  <img src="./demo.gif" width="600" style="border-radius: 10px; border: 2px solid #6366f1;" alt="算法演示" />
  <p><em>👆 实时稀疏点云输入 → 32 关节点输出</em></p>
</div>

**核心技术**：
┌─────────────────────────────────────────────────────────┐
│ 输入层：稀疏点云 (20-80 点/帧) │
│ ↓ │
│ 特征提取：时空卷积 + 注意力机制 │
│ ↓ │
│ 时序融合：多帧信息聚合 (解决遮挡问题) │
│ ↓ │
│ 输出层：32 个关节点坐标 (x,y,z) │
└─────────────────────────────────────────────────────────┘

**算法贡献**：
- ✅ **网络架构创新**：基于 PSTNet 进行结构性改造，引入**时空注意力机制**，适配稀疏不规则数据
- ✅ **时序建模优化**：设计**多帧融合策略**，多人场景下精度提升至接近单人水平 (+15% mAP)
- ✅ **数据工程闭环**：构建自动化标注 pipeline，完成 10W+ 帧数据清洗与时空同步

**工程落地**：
- ✅ 基于 Qt5 开发全流程 GUI 系统（采集/训练/推理/可视化）
- ✅ 服务器端实时部署，推理延迟 < 50ms
- ✅ 支持单人/多人动态切换，系统稳定性 > 99%

---

### 📈 时序信号分析与生命体征监测
> **算法挑战**：从噪声环境中提取微弱周期性信号，信噪比低，干扰因素多。

**核心技术**：
- 频域分析 + 时域滤波联合处理
- 自适应噪声消除算法
- 峰值检测与周期估计算法

**工程贡献**：
- ✅ 设计实时信号处理 pipeline，支持多通道并行处理
- ✅ 开发参数可视化调试工具，算法迭代效率提升 3 倍
- ✅ 嵌入式环境优化，算力消耗降低 60%

---

### 🤖 AI 辅助研发流程优化
> **目标**：利用 AI 工具重塑算法研发工作流

**实践成果**：
传统流程：需求分析 → 代码编写 → 调试 → 文档 (100%)
AI 赋能后：需求分析 → AI 生成 → 审查优化 → 文档 (60% 时间)

**工具链**：`Cursor` `Trae` `Claude` `DeepSeek`
**效率提升**：代码编写速度 +40%，文档撰写速度 +60%

---

## 💼 Professional Experience

| 时间 | 机构 | 角色 | 核心成就 |
|------|------|------|----------|
| **2023.07 - 至今** | 中国科学院广东大湾区空天信息研究院 | **算法工程师** | 主导姿态估计项目 (0→1 落地)，发表技术专利 2 项 |
| 2017.10 - 2019.12 | 富士康科技集团 | 软件测试工程师 | 测试流程优化，交付效率提升 25% |
| 2016.10 - 2017.10 | 摩泰光电有限公司 | 测试工程师 | 搭建自动化测试平台 |

---

## 🎓 Education
🎓 武汉纺织大学 2020.07 - 2023.09
软件工程 | 硕士研究生
└─ 图像生成方向算法研究
└─ SCI 二区论文 1 篇，SCI 三区论文 1 篇
🎓 海南大学 2012.07 - 2016.09
通信工程 | 本科
└─ 算法导论、图像处理、计算机组成原理

---


## 📬 Contact
┌─────────────────────────────────────────────────────────┐
│ 📧 Email: 13138952456@163.com │
│ 📱 Phone: 18665933659 │
│ 💼 Location: 广东·大湾区 │
│ 🎯 Status: Open to Algorithm Engineer Opportunities │
└─────────────────────────────────────────────────────────┘

<div align="center">
  <br/>
  <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&label=Profile%20Views&color=6366f1&style=flat" alt="Profile Views" />
</div>
