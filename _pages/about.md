---
permalink: /
title: "Siyuan Cen"
excerpt: "MSCS @ UMass Amherst"
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

I’m Siyuan Cen (岑思远), a first year master at [UMass Amherst](https://www.umass.edu), advised by [Prof. Chuang Gan](https://people.csail.mit.edu/ganchuang/). Currently, I’m a research intern at CMU, co-advised by Prof. [Deva Ramanan](https://www.cs.cmu.edu/~deva/) and [Yilun Du](https://yilundu.github.io/). Before that, I got my becholar degree from Nanjing University, where I'm lucky to work with Prof. [Ying Tai](https://tyshiwo.github.io/).

My current focus is on video understanding, video editing and robotics.

# 📝 Publications 

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <span class="badge">arXiv</span>
      <img src="papers/camerabench/imgs/3.gif" alt="CameraBench teaser" style="width:100%;">
    </div>
  </div>

  <div class="paper-box-text">
    <h3>Towards Understanding Camera Motions in Any Video</h3>
    <p>
      Zhiqiu Lin*, <strong>Siyuan Cen*</strong>, Daniel Jiang, Jay Karhade, Hewei Wang, Chancharik Mitra,
      Yu Tong Tiffany Ling, Yuhan Huang, Sifan Liu, Mingyu Chen, Rushikesh Zawar, Xue Bai,
      Yilun Du, Chuang Gan, Deva Ramanan
    </p>
    <p>
      <a href="https://linzhiqiu.github.io/papers/camerabench/">Website</a> |
      <a href="https://arxiv.org/abs/2504.15376">arXiv</a> |
      <a href="https://github.com/sy77777en/CameraBench">
        <img
          src="https://img.shields.io/github/stars/sy77777en/CameraBench?style=social&label=Code+Stars"
          alt="GitHub stars">
      </a>
    </p>
    <p>
        We present <strong>CameraBench</strong>, a large-scale dataset and benchmark for evaluating and
        improving camera motion understanding in both SfM/SLAM systems and VLMs.
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <span class="badge">arXiv</span>
      <img src="papers/rapverse/imgs/fig_rapverse.png" alt="CameraBench teaser" style="width:100%;">
    </div>
  </div>

  <div class="paper-box-text">
    <h3>RapVerse: Coherent Vocals and Whole-Body Motions Generations from Text</h3>
    <p>
      Jiaben Chen, Xin Yan, Yihang Chen, <strong>Siyuan Cen</strong>, Qinwei Ma, Haoyu Zhen, Kaizhi Qian, Lie Lu, and Chuang Gan
    </p>
    <p>
      <a href="https://vis-www.cs.umass.edu/RapVerse/">Website</a>
      <a href="https://arxiv.org/abs/2405.20336">arXiv</a> 
    </p>
    <p>
      In this paper, we introduce a challenging task for simultaneously generating 3D holistic body motions and singing vocals directly from textual lyrics inputs. To facilitate this, we first collect the RapVerse dataset, a large dataset containing synchronous rapping vocals, lyrics, and high-quality 3D holistic body meshes.
    </p>
  </div>
</div>

<div class="paper-box">
  <div class="paper-box-image">
    <div>
      <span class="badge">Security and Communication Networks</span>
      <img src="papers/advattack/imgs/1.jpg" alt="CameraBench teaser" style="width:100%;">
    </div>
  </div>

  <div class="paper-box-text">
    <h3>Adversarial Attacks on Large Language Model-Based System and Mitigating Strategies: A Case Study on ChatGPT</h3>
    <p>
      Bowen Liu, Boao Xiao, Xutong Jiang, <strong>Siyuan Cen</strong>, Xin He, Wanchun Dou
    </p>
    <p>
      <a href="">Website</a>
      <a href="https://onlinelibrary.wiley.com/doi/pdf/10.1155/2023/8691095">arXiv</a> 
    </p>
    <p>
        The paper exposes how adversarial prompts can bypass ChatGPT's safeguards and proposes two defenses—a prefix prompt and a RoBERTa-based detector—that effectively block such attacks, with the latter achieving perfect accuracy.
    </p>
  </div>
</div>

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations

<div class="paper-box-right"
     style="display: flex; align-items: center; justify-content: flex-start; gap: 20px; padding: 0 35px; margin-bottom: 25px;">
  <div class="paper-box-text" style="flex: 1;">
    <p>UMass Amherst</p>
    <p><em>M.S. in Computer Science, 2024.09 – now</em></p>
    <p>Advisor: <a href="https://people.csail.mit.edu/ganchuang/">Chuang Gan</a></p>
  </div>
  <div class="paper-box-image" style="flex: 0 0 auto;">
    <a href="">
      <img
        src="images/umass.png"
        alt="UMass Amherst logo"
        width="100"
        style="display: block;
               transition: transform 0.2s ease;
               cursor: pointer;"
        onmouseover="this.style.transform='scale(1.1)';"
        onmouseout="this.style.transform='scale(1)';" />
    </a>
  </div>
</div>

<div class="paper-box-right"
     style="display: flex; align-items: center; justify-content: flex-start; padding: 0 35px; gap: 20px;">
  <div class="paper-box-text" style="flex: 1;">
    <p>Nanjing University</p>
    <p><em>Undergraduate, 2020.09 – 2024.06</em></p>
    <p>Advisor: <a href="https://tyshiwo.github.io/">Ying Tai</a></p>
  </div>
  <div class="paper-box-image" style="flex: 0 0 auto;">
    <a href="https://www.nju.edu.cn/en">
      <img
        src="images/nju.jpg"
        alt="Nanjing University logo"
        width="100"
        style="display: block;
               transition: transform 0.2s ease;
               cursor: pointer;"
        onmouseover="this.style.transform='scale(1.1)';"
        onmouseout="this.style.transform='scale(1)';" />
    </a>
  </div>
</div>

# 💻 Internships

<div class="paper-box-right"
     style="display: flex; align-items: center; justify-content: flex-start; padding: 0 35px; gap: 20px; margin-bottom: 25px;">
  <div class="paper-box-text" style="flex: 1;">
    <p>MIT-Deva's Lab</p>
    <p><em>Research Intern, 2025.05 – now</em></p>
    <p>Advisor: <a href="https://www.cs.cmu.edu/~deva/">Deva Ramanan</a></p>
  </div>
  <div class="paper-box-image" style="flex: 0 0 auto;">
    <a href="https://www.cs.cmu.edu/~deva/">
      <img
        src="images/CMU.webp"
        alt="CMU logo"
        width="100"
        style="display: block;
               transition: transform 0.2s ease;
               cursor: pointer;"
        onmouseover="this.style.transform='scale(1.1)';"
        onmouseout="this.style.transform='scale(1)';" />
    </a>
  </div>
</div>

<div class="paper-box-right"
     style="display: flex; align-items: center; justify-content: flex-start; padding: 0 35px; gap: 20px;">
  <div class="paper-box-text" style="flex: 1;">
    <p>MIT-IBM Watson AI Lab</p>
    <p><em>Research Intern, 2023.09 – 2024.06</em></p>
    <p>Advisor: <a href="https://people.csail.mit.edu/ganchuang/">Chuang Gan</a></p>
  </div>
  <div class="paper-box-image" style="flex: 0 0 auto;">
    <a href="https://mitibmwatsonailab.mit.edu/">
      <img
        src="images/mitibm.png"
        alt="mitibm logo"
        width="100"
        style="display: block;
               transition: transform 0.2s ease;
               cursor: pointer;"
        onmouseover="this.style.transform='scale(1.1)';"
        onmouseout="this.style.transform='scale(1)';" />
    </a>
  </div>
</div>
