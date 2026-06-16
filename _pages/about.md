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

## About Me

I am a Master’s student at <a href="https://www.zju.edu.cn/english/"><strong>Zhejiang University</strong></a>, advised by 
<a href="https://person.zju.edu.cn/shengyuzhang"><strong>Prof. Shengyu Zhang</strong></a>. 
My research focuses on <strong>3D content generation</strong> and <strong>efficient inference for visual generative models</strong>.

Specifically, I work on <strong>Speech-driven Talking Face</strong> & <strong>Text/Image-to-3D Generation</strong>, 
as well as <strong>Step Distillation</strong> & <strong>Training-free Acceleration Methods</strong> for Diffusion and Visual Autoregressive (VAR) models. I have published some papers with total google scholar citations <a href='https://scholar.google.com/citations?user=SnxhOBYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

My goal is to make <strong>high-fidelity visual generation</strong>—spanning <strong>3D, images, and video</strong>—
more practical and efficient for <strong>real-world and real-time applications</strong>.


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 1 paper accepted to ICLR 2025.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/ecoface.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ecoface: Audio-visual emotional co-disentanglement speech-driven 3d talking face generation](https://openreview.net/pdf?id=iDcWYtYUwX).

**Jiajian Xie**, Shengyu Zhang, Mengze Li, Chengfei Lv, Zhou Zhao, Fei Wu

</div>
</div>

- <a><img src="https://img.shields.io/badge/Arxiv-2025-red"></a> [ETC: training-free diffusion models acceleration with Error-aware Trend Consistency](https://arxiv.org/pdf/2510.24129). 

**Jiajian Xie**, Hubery Yin, Chen Li, Zhou Zhao, Shengyu Zhang

- <a><img src="https://img.shields.io/badge/Arxiv-2025-red"></a> [EC-Diff: Fast and High-Quality Edge-Cloud Collaborative Inference for Diffusion Models](https://arxiv.org/pdf/2507.11980).  

**Jiajian Xie**, Shengyu Zhang, Zhou Zhao, Fan Wu, Fei Wu


# 🎖 Honors and Awards
- *2025.10* National Scholarship (P.R. China)​.
- *2023.10* National Scholarship (P.R. China)​.

# 📖 Educations
- *2024.09 - 2027.06*, Master, Software Engineering, Institute of Artificial Intelligence, Zhejiang University.
- *2020.09 - 2024.06*, Undergraduate, Electronic Business and Computer Science (Dual Degree), SouthChina University of Technology.

# 💻 Internships
- *2026.4 - now*, Tencent, TEG, Hunyuan3D <img src='./images/tencent.png' style="width: 5em;">, **Qingyun Program**, ShenZhen.
- *2025.06 - 2025.12*, Tencent, WXG, WeChat Vision <img src='./images/tencent.png' style="width: 5em;">, Technical Research Intern, ShenZhen.
