# Hi, I'm Zhuoran Yang 👋

<h3 align="center">Multimodal Video Generation Researcher at Kling AI</h3>

- 💼 I currently work at **Kuaishou Kling AI**, focusing on **multimodal video generation algorithms and foundation models**.
- 🎓 I received both my Bachelor's and Master's degrees in Computer Science from the **University of Science and Technology of China (USTC)**.
- 🌱 My research interests include **Generative Models, Video Generation, World Models, Multimodal Large Language Models (MLLMs), and Large Language Models (LLMs)**.
- 📝 I have published first-author research at top-tier AI and computer vision conferences, including **ICCV 2025, ICLR 2026, and ECCV 2026**.
- 📫 How to reach me: **[shanpoyang@mail.ustc.edu.cn](mailto:shanpoyang@mail.ustc.edu.cn)**

## 💼 Work Experience

### **Kuaishou — Kling AI** | *2026 – Present*

**Multimodal Video Generation Algorithm Researcher**

- Conduct research and development on **multimodal video generation algorithms and foundation models** for Kling AI.
- Work on unified multimodal generation systems that support diverse inputs, including text, images, reference videos, and multimodal instructions.
- Contribute to **[Kling-Omni](https://app.klingai.com/global/omni/new?ac=1)**, a unified multimodal platform for intelligent video generation, editing, and content creation.
- Explore post-training and reinforcement learning techniques for improving video quality, motion quality, physical consistency, and instruction following.

## 🚀 Projects & Research

| Project | Status | Description | Tech Stack |
| :--- | :--- | :--- | :--- |
| **[InstaDrive: Driving Scene Video Generation](https://shanpoyang654.github.io/InstaDrive/page.html)** | ![ICCV2025](https://img.shields.io/badge/ICCV-2025-blue) | Developed an instance-aware world model for generating realistic and consistent driving videos. Introduced the **Spatial Geometric Aligner** and **3D Instance Flow Guider** modules to improve spatial consistency and controllability. | `PyTorch` `OpenSora` `ST-DiT` `ControlNet` |
| **[ConsisDrive: Long-Scenario Consistent Video Generation](https://shanpoyang654.github.io/ConsisDrive/page.html)** | ![ICLR2026](https://img.shields.io/badge/ICLR-2026-red) | Developed a world model for long-scenario consistent video generation. Introduced **Instance-Masked Attention** and **Instance-Masked Loss** to preserve instance identity and improve temporal consistency in foreground objects. | `PyTorch` `OpenSora` `ST-DiT` `ControlNet` |
| **[PhysPO: Physics-Aware Local Preference Optimization for Physically Consistent Video Generation](https://shanpoyang654.github.io/PhysPO/page.html)** | ![ECCV2026](https://img.shields.io/badge/ECCV-2026-blue) | Constructed **CounterPhy**, a dataset containing over 30K physics-inconsistent preference pairs, and proposed a physics-aware DPO framework with FFT-based physical-region masks for localized preference optimization. Improved physical commonsense and semantic adherence on VideoPhy1 and VideoPhy2. | `PyTorch` `Wan` `MMDiT` `ControlNet` |
| **[Multimodal 3D Perception Pre-training](https://arxiv.org/abs/2504.12709)** | ![ICLR2026](https://img.shields.io/badge/ICLR-2026-red) | Conducted large-scale multimodal 3D perception pre-training by combining image and LiDAR data, contrastive learning, and masked autoencoding. Applied prompt-based domain adaptation for joint training across multiple datasets, improving downstream 3D perception tasks. | `PyTorch` `DeepSpeed` `DSVT` `Swin Transformer` `MAE` |

## 🧑‍💻 Previous Internship Experience

### **Kuaishou — Kling AI (K-Star Talent Program)** | *2025*

**Multimodal Foundation Model Intern**

Contributed to **Keye-VL and Kelix**, focusing on multimodal understanding and unified understanding-generation foundation models.

- **Keye-VL — Multimodal Understanding Foundation Model**
  - Developed a vision-language foundation model supporting mixed text, image, and video inputs, based on a **Vision Encoder–Projector–LLM** architecture initialized from Qwen3-8B.
  - Built upon **SigLIP-SO400M** visual representations and contrastive pre-training with SigLIP loss, supporting native-resolution image processing through **NaViT**.
  - Explored a **Slow-Fast dual-tower vision architecture** with dynamic keyframe selection, improving video processing efficiency by **5.8×**.
  - Achieved competitive video understanding performance, outperforming Qwen2.5-VL-7B and InternVL-3-8B on benchmarks such as VideoMME.

- **Kelix — Unified Multimodal Understanding and Generation**
  - Extended Keye-VL with image generation capabilities, exploring a unified autoregressive modeling framework for multimodal understanding and generation.
  - Discretized continuous visual representations into high-level semantic multi-tokens aligned with the LLM, enabling autoregressive prediction of text tokens and image tokens.
  - Used predicted image tokens as semantic conditioning for **SANA-DiT** to generate images, bridging semantic understanding and visual synthesis.
  - Applied **Product Quantization (PQ)** to convert high-dimensional continuous visual representations into multiple low-dimensional discrete tokens, improving visual codebook information density.
  - Achieved competitive understanding performance on tasks such as OCR while demonstrating high-quality image generation on benchmarks such as GenEval.

### **Meituan** | *2024*

**LLM Foundation Model Intern**

- Improved the reasoning capabilities of a **70B language model** through a two-stage post-training pipeline inspired by OpenAI o1.
- Implemented supervised fine-tuning (SFT) with Megatron to teach structured chain-of-thought generation for complex reasoning tasks.
- Applied **GRPO with a Process Reward Model (PRM)** to optimize reasoning trajectories, combining correctness, format, and length-coordination rewards to improve reasoning quality and mitigate overthinking.
- Built an o1-style reasoning dataset from MCTS-generated trajectories, distilled reasoning data from models such as QwQ and DeepSeek, and human annotations.
- Achieved a **10% absolute improvement on the MATH-OAI benchmark**.

### **SenseTime** | *2024*

**World Model and Video Generation Intern**

- Researched topology and instance-level consistency in driving-scene video generation, leading to the first-author paper **InstaDrive (ICCV 2025)**.
- Developed a controllable driving-scene video generation framework based on **ST-DiT, ControlNet, and Open-Sora v1.1**.
- Proposed **3D trajectory control** and **depth-guided geometric conditioning** modules to improve spatial consistency, object relationships, and occlusion modeling in generated driving videos.

### **Microsoft Research Asia** | *2021*

**Machine Learning Algorithm Intern**

- Researched deep learning-based video thumbnail and animated preview generation for videos of arbitrary length.
- Optimized model inference using **TensorRT**, considering practical deployment constraints such as video storage formats and GPU throughput.

## 🛠️ Technical Skills

**Programming Languages:**

`C/C++` `Python` `CUDA` `SQL` `Verilog`

**Frameworks & Libraries:**

`PyTorch` `DeepSpeed` `Megatron-LM` `OpenSora` `TensorRT-LLM` `Diffusers`

## 🤝 Let's Connect

Feel free to reach out for research discussions and collaborations!

- **Email:** [shanpoyang@mail.ustc.edu.cn](mailto:shanpoyang@mail.ustc.edu.cn)
- **GitHub:** [shanpoyang654](https://github.com/shanpoyang654)
