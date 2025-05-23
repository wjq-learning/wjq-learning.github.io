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

I am currently a research fellow at the State Key Laboratory of Brain-Machine Intelligence, Zhejiang University, collaborating with [Asst. Prof. Sha Zhao](http://www.shazhao.net/) and [Prof. Gang Pan](https://person.zju.edu.cn/gpan).

I received my Ph.D. degree in Computer Science and Technology from the College of Computer Science and Technology, Zhejiang University, under the supervision of [Asst. Prof. Sha Zhao](http://www.shazhao.net/) and [Prof. Gang Pan](https://person.zju.edu.cn/gpan).

I earned my bachelor's degree in Software Engineering from the College of Computer Science and Technology at Harbin Institute of Technology.

My research interests include EEG decoding, Brain-Computer Interfaces, Artificial Intelligence, and Deep Learning.

[//]: # (I am looking for **highly-motivated💪** students to work with me. If interested, please drop me a message by email.)

---

我目前是浙江大学脑机智能全国重点实验室的研究员，与[赵莎研究员](http://www.shazhao.net/)和[潘纲教授](https://person.zju.edu.cn/gpan )合作。

我在浙江大学计算机科学与技术学院获得计算机科学与技术专业的博士学位，导师为[赵莎助理教授](http://www.shazhao.net/)和[潘纲教授](https://person.zju.edu.cn/gpan )。

我本科就读于哈尔滨工业大学计算机科学与技术学院，获软件工程学士学位。

我的研究兴趣包括脑电信号解码、脑机接口、人工智能和深度学习。

# 🔥 News

- *2025.01*: &nbsp;🎉🎉 Our paper "_CBraMod: A Criss-Cross Brain Foundation Model for EEG Decoding_" (**EEG Foundation
  Model 🤖**) is accepted by **ICLR
  2025**!
- *2025.01*: &nbsp;🎉 Our paper "_BrainUICL: An Unsupervised Individual Continual Learning Framework for EEG
  Applications_" is accepted by **ICLR 2025**!
- *2024.12*: &nbsp;🎉 Our paper "_CareSleepNet: A Hybrid Deep Learning Network for Automatic Sleep Staging_" is
  published as a **Cover Article 🏆** in **IEEE Journal of Biomedical and Health Informatics (JBHI)**!
- *2024.12*: &nbsp;🎉 Our paper "_Personalized Sleep Staging Leveraging Source-Free Unsupervised Domain Adaptation_" is
  accepted by **AAAI 2025**!
- *2023.12*: &nbsp;🎉 Our paper "_Generalizable Sleep Staging via Multi-level Domain Alignment_" is accepted by **AAAI
  2024**!
- *2023.09*: &nbsp;🎉 Our paper "_Narcolepsy Diagnosis With Sleep Stage Features Using PSG Recordings_" is
  published in **IEEE Transactions on Neural Systems and Rehabilitation Engineering (TNSRE)**!

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/papers/CBraMod.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CBraMod: A Criss-Cross Brain Foundation Model for EEG Decoding](https://openreview.net/forum?id=NPNUHgHF2w)

**Jiquan Wang**, Sha Zhao, Zhiling Luo, Yangxuan Zhou, Haiteng Jiang, Shijian Li, Tao Li, Gang Pan

[![Paper](https://img.shields.io/badge/arXiv-2412.07236-red)](https://arxiv.org/abs/2412.07236)
[![Paper](https://img.shields.io/badge/Paper-ICLR-008B8B)](https://openreview.net/forum?id=NPNUHgHF2w)
[![huggingface](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-FFD21E)](https://huggingface.co/weighting666/CBraMod)
[![GitHub Repo stars](https://img.shields.io/github/stars/wjq-learning/CBraMod)](https://github.com/wjq-learning/CBraMod)

- This paper proposes a novel **EEG Foundation Model 🤖** called **CBraMod**, with **criss-cross transformer** as the backbone and **ACPE** as the positional encodings.
- **CBraMod** achieves superior performance across up to **10 downstream BCI tasks with 12 public datasets**, proving its strong capability and generalizability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='images/papers/SleepDG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalizable Sleep Staging via Multi-Level Domain Alignment](https://ojs.aaai.org/index.php/AAAI/article/view/27779)

**Jiquan Wang**, Sha Zhao, Haiteng Jiang, Shijian Li, Tao Li, Gang Pan

[![Paper](https://img.shields.io/badge/arXiv-2401.05363-red)](https://arxiv.org/abs/2401.05363)
[![Paper](https://img.shields.io/badge/Paper-AAAI-008B8B)](https://ojs.aaai.org/index.php/AAAI/article/view/27779)
[![GitHub Repo stars](https://img.shields.io/github/stars/wjq-learning/SleepDG)](https://github.com/wjq-learning/SleepDG)

- This paper introduces **domain generalization** into automatic sleep staging and proposes the task of **generalizable sleep staging**.
- This paper proposes a framework called **SleepDG**, which adopting a **Multi-Level Feature Alignment** to learn domain-invariant feature representations.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JBHI 2024</div><img src='images/papers/CareSleepNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CareSleepNet: A Hybrid Deep Learning Network for Automatic Sleep Staging](https://ieeexplore.ieee.org/document/10595067)

**Jiquan Wang**, Sha Zhao, Yangxuan Zhou, Haiteng Jiang, Zhenghe Yu, Tao Li, Shijian Li, Gang Pan

[![Paper](https://img.shields.io/badge/Paper-JBHI-008B8B)](https://ieeexplore.ieee.org/document/10595067)
[![GitHub Repo stars](https://img.shields.io/github/stars/wjq-learning/CareSleepNet)](https://github.com/wjq-learning/CareSleepNet)

- This paper proposes **CareSleepNet**, a novel hybrid deep learning network for automatic sleep staging from PSG recordings.
- This paper is selected as the **Cover Article 🏆** of the corresponding issue by **IEEE Journal of Biomedical and Health Informatics (JBHI)**.
</div>
</div>

- `ICLR 2025` [BrainUICL: An Unsupervised Individual Continual Learning Framework for EEG Applications](https://openreview.net/forum?id=6jjAYmppGQ), Yangxuan Zhou, Sha Zhao, **Jiquan Wang**, Haiteng Jiang, Shijian Li, Tao Li, Gang Pan
- `AAAI 2025` [Personalized Sleep Staging Leveraging Source-free Unsupervised Domain Adaptation](https://arxiv.org/abs/2412.12159), Yangxuan Zhou, Sha Zhao, **Jiquan Wang**, Haiteng Jiang, Benyan Luo, Tao Li, Gang Pan
- `TNSRE 2024` [Simplifying Multimodal with Single EOG Modality for Automatic Sleep Staging](https://ieeexplore.ieee.org/document/10504925), Yangxuan Zhou, Sha Zhao, **Jiquan Wang**, Haiteng Jiang, Zhenghe Yu, Shijian Li, Tao Li, Gang Pan
- `TNSRE 2023` [Narcolepsy Diagnosis With Sleep Stage Features Using PSG Recordings](https://ieeexplore.ieee.org/document/10242085), **Jiquan Wang**, Sha Zhao, Yangxuan Zhou, Haiteng Jiang, Zhenghe Yu, Tao Li, Shijian Li, Gang Pan
- `ACL 2022` [Multimodal sarcasm target identification in tweets](https://aclanthology.org/2022.acl-long.562/), **Jiquan Wang**, Lin Sun, Yi Liu, Meizhi Shao, Zengwei Zheng
- `AAAI 2021` [RpBERT: a text-image relation propagation-based BERT model for multimodal NER](https://ojs.aaai.org/index.php/AAAI/article/view/17633), Lin Sun<sup>#</sup>, **Jiquan Wang<sup>#</sup>**, Kai Zhang, Yindu Su, Fangsheng Weng
- `COLING 2020` [RIVA: a pre-trained tweet multimodal model based on text-image relation for multimodal NER](https://aclanthology.org/2020.coling-main.168/), Lin Sun, **Jiquan Wang**, Yindu Su, Fangsheng Weng, Yuxuan Sun, Zengwei Zheng, Yuanyi Chen

<sup>**✉**</sup> denotes corresponding author and <sup>**#**</sup> denotes equal contribution.

[//]: # (# 🎖 Honors and Awards)

[//]: # ()

[//]: # ()

[//]: # ()

[//]: # (- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo)

[//]: # ()

[//]: # (  dapibus sit amet.)

[//]: # ()

[//]: # (- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo)

[//]: # ()

[//]: # (  dapibus sit amet.)

# 📖 Educations

- *2019.06 - 2025.03*, PhD candidate, Computer Science and Technology, Zhejiang University, Hanzhou, China.
- *2015.09 - 2019.06*, Undergraduate, Software Engineering, Harbin Institute of Technology, Harbin, China.

[//]: # (# 💬 Invited Talks)

[//]: # ()

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo)

[//]: # (  dapibus sit amet.)

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo)

[//]: # (  dapibus sit amet. \| [\[video\]]&#40;https://github.com/&#41;)

[//]: # ()

[//]: # (# 💻 Internships)

[//]: # ()

[//]: # (- *2019.05 - 2020.02*, [Lorem]&#40;https://github.com/&#41;, China.)

<div style="width: 50%; margin: 0 auto; text-align: center;">
  <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=TzqIOasqA-EsJJYPt2cMXeu2O3Yj6LcQzlC9QoFWe3o&cl=ffffff&w=a"></script>
</div>

