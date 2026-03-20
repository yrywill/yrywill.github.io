---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am **Rongyi Yu (余荣毅)**, a Master student at **Peking University, Center for Machine Learning Research**. I am currently involved in research and engineering on **large model training and alignment**, with a focus on **data attribution**, **dynamic data selection**, and **training efficiency optimization** for **Pretrain / SFT / RLHF (PPO)** settings.

My recent work centers on **data-centric AI** and **AI infrastructure**, aiming to improve the **alignment quality**, **robustness**, and **cost efficiency** of large language models. I am comfortable with the full research pipeline from algorithm design to engineering implementation, including training, evaluation, reproduction, and performance diagnosis.

My current and previous research interests include:
- Data Attribution
- Data-Centric AI
- LLM Training and Alignment
- Dynamic Data Selection
- AI Infrastructure
- Diffusion Models

# 🔥 News
- *2026*: &nbsp;🎉 I will join **Peking University** as a master's student at the **Center for Machine Learning Research**.
- *2026*: &nbsp;📝 Our paper **“LongVidSearch: An Agentic Multi-hop Search Benchmark for Long Videos”** is under submission to **SIGIR 2026**.
- *2025*: &nbsp;🚀 Participated in research and engineering for **DCAI-DataFlex**, an open-source data-centric toolkit and dynamic training framework for LLMs.
- *2025*: &nbsp;🏆 Received multiple honors including **National First Prize in the Chinese Mathematics Competition** and **Top 10 Students** at Harbin Institute of Technology.

# 📝 Publications

- **Rongyi Yu***, Chenyuan Duan*, et al.  
  **LongVidSearch: An Agentic Multi-hop Search Benchmark for Long Videos**  
  *SIGIR 2026 Submission*

# 🎖 Honors and Awards
- *2025* **National First Prize, Chinese Mathematics Competition (Mathematics Category)**  
  Highest-level national honor for mathematics undergraduates.
- *2025* **Top 10 Students, Harbin Institute of Technology**  
  Highest individual student honor at HIT; only 10 students selected across all campuses from freshman to senior year.
- *2022, 2024* **National Scholarship ×2**  
  Awarded to only about 2% of undergraduate students each year.
- *2025* **Bronze Medal, China International College Students’ Innovation Competition**  

# 📖 Education
- *2026.09 - 2028.06* **Peking University**, Center for Machine Learning Research, M.S.  
  I will join Peking University in Fall 2026 for my master's study, co-supervised by **Prof. Weinan E** and **Prof. Wentao Zhang**.
- *2022.09 - 2026.06* **Harbin Institute of Technology**, School of Mathematics, B.S.  
  GPA: **99.53/100**, Rank: **1/45**  
  CET-4: **585**, CET-6: **571**

# 🔬 Research Experience
- *2025.09 - 2026.02* **Research Assistant, Peking University, Center for Machine Learning Research**  
  Advisors: **Prof. Wentao Zhang**, **Dr. Hao Liang**
  - Worked on **data-centric LLM training** and **parameter-efficient fine-tuning (PEFT)**.
  - Studied **data quality**, **data selection**, and **training stability** for supervised fine-tuning.
  - Participated in the development of the **DataFlex** dynamic training framework.
  - Supported the full pipeline of **data scoring / sampling / training / evaluation** to improve generation quality and training efficiency.

- *2024.03 - 2025.08* **Research Assistant, Harbin Institute of Technology & HKUST School of Mathematics**
  - Collaborated closely with **Prof. Yao Li** and **Prof. Yang Xiang**.
  - Conducted research on **diffusion-model-based theory and implementation** for **satellite image alignment and fusion**.

# 💻 Selected Projects

## DCAI-DataFlex
**Open-source data-centric toolkit / dynamic training framework for large models**
- **Problem:** In SFT/RLHF training, noisy, redundant, and distribution-shifted data can lead to unstable generation quality and high training cost.
- **Method:** As a major contributor, I helped build the dynamic training framework, designed multiple offline domain data selection operators, and developed domain-mixing strategies compatible with **Qwen**, **Llama**, and related training pipelines.
- **Result:** Verified the framework’s effectiveness in SFT training: using only about **5%** of the training data can achieve **near full-data MMLU accuracy**.
- **Impact:** The method can be extended to **pretraining**, **reinforcement learning**, and **hard-example mining**, improving alignment quality and system stability.

# 🛠 Skills
- **Programming & ML:** Python, PyTorch, Transformers, vLLM, DeepSpeed, LLaMA-Factory
- **Mathematics:** Probability and Statistics, Stochastic Processes, Optimization, Numerical Analysis
- **Tools:** Git, LaTeX, Markdown, Linux