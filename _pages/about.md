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

I am a final-year PhD student at University of Illinois at Urbana-Champaign (UIUC). I am fortunate to be advised by Professor [Jingrui He](https://ischool.illinois.edu/people/jingrui-he). Before that, I completed my bachlor degree in Computer Science at University of Science and Technology of China (USTC). My research interest mainly lies in trustworthy machine learning with a special focus on fairness, robustness and scalability. I am particularly interested in applying these principles to critical real-world applications including medicare, e-commerce, and social systems. I am also interested in understanding bias in foundation models.


<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News

<div class="scroll-box">
  <p><em>2022.02</em>: &nbsp;🎉🎉 I will join Visa Research as a research intern this summer!</p>
  
  </div>


<style>
  .scroll-box {
    max-height: 150px;
    overflow-y: auto;
    background-color: #f5f5f5;
    padding: 10px;
  }
</style> -->

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2020 - 2025 (expected)*, University of Illinois Urbana-Champaign
  
  Ph.D. in Information Sciences, Advisor: Prof. [Jingrui He](https://www.hejingrui.org/)



- *2016 - 2020*, University of Science and Technology of China. 
  
  Bachelor of Computer Science, Advisor: Prof. [Xiangyang Li](http://staff.ustc.edu.cn/~xiangyangli/index.html) and Prof. [Xiangnan He](https://hexiangnan.github.io/)

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

## Preprint

- **Fair Anomaly Detection For Imbalanced Groups**

  <u>Ziwei Wu<sup>*</sup></u>, Lecheng Zheng<sup>\*</sup>, Yuancheng Yu, Ruizhong Qiu, John Birge, Jingrui He

  *preprint 2024.*

- **Preference-aware Gradient Matching for Fairness**

  <u>Ziwei Wu</u>, Yikun Ban, Jingrui He

  *preprint 2024.*

- **Rethinking Fairness in LLM Tabular Tasks: A Mixture of LoRA Experts Approach**
  
  <u>Ziwei Wu</u>, Yiwei Cai, Rashid Islam

  *preprint 2024.*

- **Language in the Flow of Time: Time-Series-Paired Texts Weaved into a Unified Temporal Narrative**

  Zihao Li, Xiao Lin, Zhining Liu, Jiaru Zou, <u>Ziwei Wu</u>, Lecheng Zheng, Dongqi Fu, Yada Zhu, Hendrik Hamann, Hanghang Tong, Jingrui He

  *preprint 2024.*

## Conference

- **Neural Active Learning Beyond Bandits.**
  
  Yikun Ban, Ishika Agarwal, <u>Ziwei Wu</u>, Yada Zhu, Kommy Weldemariam, Hanghang Tong, Jingrui He

<ul>
  {% include conference_buttons.html 
     conference='*ICLR 2024.*' 
     code_link='https://github.com/agarwalishika/NeurONAL' 
     arxiv_link='https://arxiv.org/pdf/2404.12522'
  %}
</ul>



  <!-- (Poster Session, AR: 31%) -->

- **Training Fair Deep Neural Networks by Balancing Influence.**

  Haonan Wang<sup>\*</sup>, <u>Ziwei Wu<sup>\*</sup></u>, Jingrui He

<ul>
  {% include conference_buttons.html 
     conference='*WSDM 2024.*' 
     code_link='https://github.com/hhhiddleston/FairIF' 
     arxiv_link='https://arxiv.org/pdf/2201.05759'
  %}
</ul>
  <!-- (Full Research, AR: 18%) -->

- **Deep Active Learning by Leveraging Training Dynamics.**

  Haonan Wang, Wei Huang, <u>Ziwei Wu</u>, Andrew Margenot, Hanghang Tong, Jingrui He., Jingrui He

<ul>
  {% include conference_buttons.html 
     conference='*NeurIPS 2022.*' 
     code_link='https://github.com/haonan3/Deep-Active-Learning-by-Leveraging-Training-Dynamics' 
     arxiv_link='https://arxiv.org/pdf/2110.08611'
  %}
</ul>
  <!-- (Poster Session, AR: 25.6%) -->

- **Fairness-aware Model-agnostic Positive and Unlabeled Learning.** <span style="color: red;">**Distinguished Paper Award**</span>

  <u>Ziwei Wu</u>, Jingrui He

<ul>
  {% include conference_buttons.html 
     conference='*FAccT 2022.*' 
     code_link='https://github.com/hhhiddleston/fairpul' 
     arxiv_link='https://arxiv.org/pdf/2206.09346'
  %}
</ul>
  <!-- (Full Research, AR: 25.1%)  ACM Conference on Fairness, Accountability, and Transparency -->

- **Model-Agnostic Counterfactual Reasoning for Eliminating Popularity Bias in Recommender System.**  <span style="color: red;">**Most Influential KDD Papers**</span>

  Tianxin Wei, Fuli Feng, Jiawei Chen, <u>Ziwei Wu</u>, Jinfeng Yi, Xiangnan He

<ul>
  {% include conference_buttons.html 
     conference='*SIGKDD 2021.*' 
     code_link=' https://github.com/weitianxin/MACR' 
     arxiv_link='https://arxiv.org/pdf/2010.15363'
  %}
</ul>
  <!-- (Full Research, AR: 15.4%). Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining (  -->


- **Fast Adaptation for Cold-start Collaborative Filtering with Meta-learning.**

  Tianxin Wei, <u>Ziwei Wu</u>, Ruirui Li, Ziniu Hu, Fuli Feng, Xiangnan He, Yizhou Sun, Wei Wang.

<ul>
  {% include conference_buttons.html 
     conference='*ICDM 2020.*' 
     code_link='https://drive.google.com/file/d/1_UaPcCQLaEEWUCsMTRIgsvtWqorqsnUm/view' 
     arxiv_link='https://par.nsf.gov/servlets/purl/10262216'
  %}
</ul>
  <!-- (Full Research, AR: 9.8%). IEEE International Conference on Data Mining ( -->


<!-- 
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
   -->


# 🎖 Honors and Awards
- Distinguished Paper Award of FAccT, *2022*
- Best Program Committee of CIKM, *2022*
- Most Influential KDD Papers, *2021*
- Valedictorian of Class of 2020 of USTC, *2020*
- Guo Moruo Scholarship (Summa Cum Laude), *2019*
- Tang Lixin Scholarship, *2018*
- National Scholarship of China, *2017*

<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
