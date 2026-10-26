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

Hi, I'm Zhao Zhang, a graduate student in Electrical Engineering at the University of Pennsylvania, co-supervised by [Dr. Li Shen](https://www.med.upenn.edu/apps/faculty/index.php/g275/p9075258) and [Dr. Yong Fan](https://www.med.upenn.edu/apps/faculty/index.php/g275/p4257219). I obtained my Bachelor's degree in Applied Physics at Xidian University, supervised by [Dr. Jiajie Wang](https://faculty.xidian.edu.cn/WJJ3/zh_CN/index.htm).

My research interests include developing generalizable models to decode neural signals, and building agentic frameworks to better interact with the world.

Outside of the lab, I like music and watching movies — I'm fascinated by the ideas explored in *Ready Player One* and *The Matrix*. I'm also a big fan of FC Barcelona. ⚽🔵🔴


# 🔥 News
<!-- - *2026.11*: &nbsp;🎉🎉 Our paper ***MedSEO*** has been accepted by AAAI 2027. -->
- *2026.10*: &nbsp;🎉🎉 Our paper ***Scratch-AID+*** has been accepted by IEEE BIBM Workshop: AI4BioSig 2026.
- *2025.10*: &nbsp;🎉🎉 Our paper ***CONTINfit-GRNN*** has been published in Journal of Nanoparticle Research. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE BIBM-W 2026</div><img src='images/scratchaid_overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Robust Automated Mouse Scratching Behavior Detection for Itch Research](https://www.biorxiv.org/content/10.64898/2026.10.12.758682v1)

Shu Yang<sup>\*</sup>, Anyu Pan<sup>\*</sup>, Hyowon Shin<sup>\*</sup>, Hongzhuo Chen<sup>\*</sup>, **Zhao Zhang**, Azim Shad, William Huang, Yang Liu, Wesley Liu, Helen Luo, Chentianye Xu, Jiong Chen, Min Xu, Wenqin Luo, Huasheng Yu, Li Shen

[**Code**](https://github.com/PennShenLab/scratch-aid-plus)

- <sup>\*</sup> indicates equal contribution.
- We present Scratch-AID+, a framework for automated mouse scratching detection spanning classic ResNet-based detectors, task-adaptive fine-tuning of video foundation models, and in-context learning with multimodal large language models.
- Benchmarking on a public dataset and independent cross-laboratory recordings, we show that fine-tuned video foundation models substantially improve generalizability over classic baselines, while frozen MLLMs show promising few-shot ability out of the box.
</div>
</div>

- [Towards Robust Automated Mouse Scratching Behavior Detection for Itch Research](https://www.biorxiv.org/content/10.64898/2026.10.12.758682v1), Shu Yang<sup>\*</sup>, Anyu Pan<sup>\*</sup>, Hyowon Shin<sup>\*</sup>, Hongzhuo Chen<sup>\*</sup>, **Zhao Zhang**, Azim Shad, William Huang, Yang Liu, Wesley Liu, Helen Luo, Chentianye Xu, Jiong Chen, Min Xu, Wenqin Luo, Huasheng Yu, Li Shen, **IEEE BIBM Workshop: AI4BioSig**, 2026

<!-- MedSEO: hidden for now
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">J. AAAI 2027</div><img src='images/MedSEO.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MedSEO: A Dynamic Agentic Framework for Clinical Tasks via Interpretable Specialized Expert Orchestration]()

Farica Zhuang<sup>\*</sup>, Dinara Aliyeva<sup>\*</sup>, **Zhao Zhang**, Shu Yang, Zixuan Wen, Nicholas Knoz, Shyam Sriram, Jinhao Duan, Duy Duong-Tran, Christos Davatzikos, Tianlong Chen, Song Wang, Li Shen

- <sup>\*</sup> indicates equal contribution.
- We present a new framework, Med-MoE, a dynamic agentic framework with an adaptive agent router that assembles a patient-specific team of specialists, guided by patient context and medically-grounded concepts from the specialized MoE backbone, resulting in personalized, sequential collaboration based on the unique diagnostic relevance of each patient's data.
</div>
</div>

- [MedSEO: A Dynamic Agentic Framework for Clinical Tasks via Interpretable Specialized Expert Orchestration](), Farica Zhuang<sup>\*</sup>, Dinara Aliyeva<sup>\*</sup>, **Zhao Zhang**, Shu Yang, Zixuan Wen, Nicholas Knoz, Shyam Sriram, Jinhao Duan, Duy Duong-Tran, Christos Davatzikos, Tianlong Chen, Song Wang, Li Shen, **AAAI**, 2027
-->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">J. Nanopart. Res. 2025</div><img src='images/CONTINfit-GRNN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CONTINfit-GRNN: a hybrid method for recovering nanoparticle size distribution in dynamic light scattering](https://link.springer.com/article/10.1007/s11051-025-06469-x)

**Zhao Zhang**, Jiajie Wang, Paul Briard, Hameed Akhtar, Kewen Su

- We propose a hybrid inversion algorithm by integrating the constrained regularization method (CONTIN), the nonlinear least squares fitting and a general regression neural network (GRNN).
- Our method achieves precise inversion of the particle size distribution for unimodal and bimodal nano-spherical particle systems, with enhanced robustness against noise.
</div>
</div>

- [CONTINfit-GRNN: a hybrid method for recovering nanoparticle size distribution in dynamic light scattering](https://link.springer.com/article/10.1007/s11051-025-06469-x), **Zhao Zhang**, Jiajie Wang, Paul Briard, Hameed Akhtar, Kewen Su, **Journal of Nanoparticle Research**, 2025

# 🎖 Honors and Awards
- *2023.05* Meritorious Winner, Mathematical Contest in Modeling(MCM/ICM). 

# 📖 Educations
- *2026.01 - now*, M.S. student, Electrical Engineering, University of Pennsylvania. 
- *2021.09 - 2025.06*, B.S. student, Applied Physics, Xidian University. 

# 💻 Internships
- *2025.09 - 2025.12*, iFLYTEK, Beijing, China.
