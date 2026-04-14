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

Hi there! My name is Xiaomin Li (李小民), currently a fourth-year PhD student at the [IIAU-Lab](https://iiaulab.github.io/), Dalian University of Technology, advised by [Prof. Huchuan Lu（IEEE Fellow）](https://scholar.google.com/citations?user=D3nE0agAAAAJ&hl=zh-CN) and [Prof. Xu Jia](https://stephenjia.github.io/). I obtained my Master's degree and Bachelor's degree from Jilin University supervised by [Prof. Hao Xu](https://scholar.google.com/citations?user=9KW7Z-oAAAAJ&hl=zh-CN).
My current research interests primarily focus on **Video/Image Generation** and **Multimodal Large Language Models**. Please feel free to contact me if you are interested in my research or potential collaborations.


# 🔥 News
- *2026.04*: &nbsp;🎉🎉 One Paper is accepted by ACL Findings 2026. 
- *2026.03*: &nbsp;🎉🎉 One Paper is accepted by CVPR 2026.
- *2025.06*: &nbsp;🎉🎉 One Paper is accepted by ICCV 2025.
- *2025.03*: &nbsp;🎉🎉 One Paper is accepted by CVPR 2025 Highlight.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL Findings 2026</div><img src='images/dailyclue.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Seek-and-Solve: Benchmarking MLLMs for Visual Clue-Driven Reasoning in Daily Scenarios](https://arxiv.org/abs/2412.19637)

**Xiaomin Li**<sup>\*</sup>, Tala Wang<sup>\*</sup>, Zichen Zhong<sup>\*</sup>, Ying Zhang, Zirui Zheng, Takashi Isobe, Dezhuang Li, Huchuan Lu, You He, Xu Jia<sup>✉</sup>

<sup>\*</sup>Equal Contribution    <sup>✉</sup>Corresponding Author

[[**Code**](https://github.com/LemonTwoL/ReNeg)]
[[**Paper**](https://arxiv.org/pdf/2412.19637)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 Highlight</div><img src='images/reneg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ReNeg: Learning Negative Embedding with Reward Guidance](https://arxiv.org/abs/2412.19637)

**Xiaomin Li**<sup>\*</sup>, Yixuan Liu<sup>\*</sup>, Takashi Isobe, Xu Jia<sup>✉</sup>, Qinpeng Cui, Dong Zhou, Dong Li, You He, Huchuan Lu, Zhongdao Wang<sup>✉</sup>, Emad Barsoum

<sup>\*</sup>Equal Contribution    <sup>✉</sup>Corresponding Author

[[**Code**](https://github.com/LemonTwoL/ReNeg)]
[[**Paper**](https://arxiv.org/pdf/2412.19637)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/motrans.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MoTrans: Customized Motion Transfer with Text-driven Video Diffusion Models](https://dl.acm.org/doi/pdf/10.1145/3664647.3680718)

**Xiaomin Li**<sup>\*</sup>, Xu Jia<sup>✉</sup>, Qinghe Wang, Haiwen Diao, Mengmeng Ge, Pengxiang Li, You He, Huchuan Lu

<sup>\*</sup>Equal Contribution    <sup>✉</sup>Corresponding Author

[[**Paper**](https://dl.acm.org/doi/pdf/10.1145/3664647.3680718)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2024</div><img src='images/mobox.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MoBox: Enhancing Video Object Segmentation with Motion-Augmented Box Supervision](https://ieeexplore.ieee.org/document/10659037/)

**Xiaomin Li**<sup>\*</sup>, Qinghe Wang, Dezhuang Li, Mengmeng Ge, Xu Jia<sup>✉</sup>, You He, Huchuan Lu

<sup>\*</sup>Equal Contribution    <sup>✉</sup>Corresponding Author

[[**Paper**](https://ieeexplore.ieee.org/document/10659037/)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/ccl-lgs.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CCL-LGS: Contrastive Codebook Learning for 3D Language Gaussian Splatting](https://openaccess.thecvf.com/content/ICCV2025/papers/Tian_CCL-LGS_Contrastive_Codebook_Learning_for_3D_Language_Gaussian_Splatting_ICCV_2025_paper.pdf)

Lei Tian, **Xiaomin Li**, Liqian Ma, Hao Yin, Zirui Zheng, Hefei Huang, Taiqing Li, Huchuan Lu, Xu Jia<sup>✉</sup>

<sup>✉</sup>Corresponding Author

[[**Paper**](https://openaccess.thecvf.com/content/ICCV2025/papers/Tian_CCL-LGS_Contrastive_Codebook_Learning_for_3D_Language_Gaussian_Splatting_ICCV_2025_paper.pdf)]
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/StyleGRPO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Style-GRPO: Semantic-Aware Preference Optimization for Image Style Transfer Guided by Reward Modeling](https://www.falcary.com/assets/files/StyleGRPO.pdf)

Jianbin Zhao<sup>\*</sup>, Chaoran Feng<sup>\*</sup>, Miao Yu<sup>\*</sup>, Yingtao Li, Zhenyu Tang, Wangbo Yu, Yian Zhao, **Xiaomin Li**, Li Yuan<sup>✉</sup>, Yonghong Tian<sup>✉</sup>.

<sup>\*</sup>Equal Contribution    <sup>✉</sup>Corresponding Author

[[**Paper**](https://www.falcary.com/assets/files/StyleGRPO.pdf)]
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- </div>
</div> --> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIP 2025</div><img src='images/characterfactory.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CharacterFactory: Sampling Consistent Characters with GANs for Diffusion Models](https://qinghew.github.io/CharacterFactory/)

Qinghe Wang, Baolu Li, **Xiaomin Li**, Bing Cao, Liqian Ma, Huchuan Lu, Xu jia✉.
<sup>✉</sup>Corresponding Author

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
[[**Project Page**](https://qinghew.github.io/CharacterFactory/)]
[[**Gradio Demo🤗**](https://huggingface.co/spaces/DecoderWQH666/CharacterFactory)]
[[**Paper**](https://arxiv.org/pdf/2404.15677)]
[[**Code**](https://github.com/qinghew/CharacterFactory)]
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>


# 🎖 Honors and Awards
- *2025.12* Awarded as an Outstanding Graduate of Liaoning Province.
- *2025.03* One paper accepted as CVPR 2025 Highlight.
- *2025.10* Received the Sonosray Scholarship.
- *2025.09* Received the Doctoral Dissertation Excellence Scholarship.
- *2024.10* Received the Doctoral Graduate Excellence Scholarship.
- *2021.10* Received the National Scholarship.


# 📖 Educations
- *2022.06 - now*, PhD, Dalian University of Technology, Dalian. 
- *2019.09 - 2022.06*, Master, Jilin University, Changchun.
- *2015.09 - 2019.06*, Undergraduate, Jilin University, Changchun.


# 💻 Internships
- *2025.09 - now*, Tencent WeChat, China.
- *2024.05 - 2025.08*, AMD, China.
