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

I am a first-year master's student in Zhejiang University now. I also worked at [MSRA-Natural Language Computing Group](https://www.microsoft.com/en-us/research/group/natural-language-computing/) <img src='./images/microsoft_logo.svg' style="width: 4em;"> as a research intern in Beijing ago, doing some LLM and speech research. 

I am now working on Text to speech, large language models, Generative model research. If you are seeking any form of **academic cooperation**, please feel free to email me at shengpengji@zju.edu.cn.

I graduate from the Department of Software Engineering in JiLin University (吉林大学软件学院) with a bachelor's degree and continue to study in Zhejiang University (浙江大学软件学院) with a master's degree now, advised by [Zhou Zhao (赵洲)](https://person.zju.edu.cn/zhaozhou). I also collaborate with [Zhou Long (周龙)](https://long-zhou.github.io/), [ShuJie Liu (刘树杰)](https://www.microsoft.com/en-us/research/people/shujliu/) from [Microsoft Research Asia](https://www.microsoft.com/en-us/research/group/machine-learning-research-group/) closely. 

My research interest includes speech synthesis, Generative model and LLM. I look forward to having more paper published at the top international AI conferences such as NeurIPS, ICLR, ACL, IJCAI, ACM MM, AAAI, ICASSP, Interspeech. I have published some papers at the top international AI conferences with total google scholar citations <a href='https://scholar.google.com/citations?user=zuRaB-oAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 💻 Important! 
最近本人在寻求一份2024春季，研究型算法实习生/学术合作的offer，Base 杭州(其次上海/北京/深圳)，可以长期线下实习。研究方向：语音合成，语音大模型相关。对AIGC生成式模型/多模态相关/有很炫酷Demo的方向也很感兴趣。**渴望在新的实习阶段学到一些新的东西，持续努力追求能做出*高引用论文*的工作**，在此基础之上期待能将论文部署成实际算法产品。这是我的[个人简历](https://github.com/novateurjsp/novateurjsp.github.io/blob/main/docs/cv20240130.pdf)，欢迎各位随时联系我，微信手机同号。




# 🔥 News
- *2024.01*：I was selected as a reviewer for ACM MM 2024!
- *2024.01*: MobileSpeech has been successfully deployed into [Magic6](https://www.hihonor.com/cn/phones/honor-magic6-pro/) series in Honor Mobile phone!
- *2024.01*: One Paper (co-worker) is accepted by 2024 ICLR (Top conference in machine learning)!
- *2023.12*: TextrolSpeech is accepted by 2024 ICASSP (Top conference in speech domain)!
- *2023.11*: One Paper (co-worker) is accepted by CCFA IEEE Transactions on Computers!
- *2023.11*: Megatts has been successfully deployed into [products](https://www.volcengine.com/product/voicecloning) at ByteDance<img src='./images/tiktok.png' style='width: 6em;'>!
- *2023.08*：I was selected as a reviewer for EMNLP 2023!
- *2023.05*: We propose Mega-TTS (co-worker) on arxiv!
- *2023.03*: 🎉🎉 I join [Microsoft Research Asia(MSRA), Natural Language Computing Group](https://www.microsoft.com/en-us/research/group/natural-language-computing/) <img src='./images/microsoft_logo.svg' style="width: 4em;"> as a research intern!
- *2022.11*: I join Ping An Technology Company <img src='./images/pingan.png' style='width: 6em;'> as a speech junior algorithm engineer in Shanghai!
- *2022.10*: I got the offer of postgraduate study in the School of Software of [Zhejiang University](http://www.cst.zju.edu.cn/). 🚧 ⛏️ 🛠️ 👷 
- *2021.11*: I join [Tsinghua Shenzhen International Graduate School](https://www.sigs.tsinghua.edu.cn/xxxb/list.htm) <img src='./images/qinghua.png' style='width: 6em;'> as a remote intern!
- *2021.10*: 🎉🎉 I win the Nation Scholarship (Top 1%) in the second year of undergraduate.

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
## 🎙 Controllable Speech Synthesis


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2024</div><img src='images\textrolspeech1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

TextrolSpeech: A Text Style Control Speech Corpus With Codec Language Text-to-Speech Models \\
Authors: **Shengpeng Ji**, Jialong Zuo, Minghui Fang, Ziyue Jiang, Feiyang Chen, Xinyu Duan, Baoxing Huai, Zhou Zhao

- Audio samples are available in this [website](https://sall-e.github.io/)
</div>
</div>

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">DiffBeautifier</div><img src='images/DiffBeautifier.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DiffBeautifier:Fast Diffusion Model for High-Fidelity Singing Voice Beautifying \\
Authors: **Shengpeng Ji**, Xulong Zhang, Jianzong Wang, Ziyue Jiang,Jing Xiao


- DiffBeautufier is the first singing voice beautifying model without paired data.
- Audio samples are available in this [website](https://diffbeautifier.github.io/)
</div>
</div>
-->


## 📚 Zero-shot TTS
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL ARR12 submit</div><img src='images\mobilespeech.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MobileSpeech: A Fast and High-Fidelity Framework for Mobile Zero-Shot Text-to-Speech \\
Authors: **Shengpeng Ji<sup>*</sup>**, Ziyue Jiang<sup>*</sup>, Hanting Wang, Jialong Zuo, Zhou Zhao

- Audio samples are available in this [website](https://mobilespeech.github.io/)
</div>
</div>
- ICLR 2024 [Boosting Prompting Mechanisms for Zero-Shot Speech Synthesis](), Ziyue Jiang, Jinglin Liu, Yi Ren, Jinzheng He, Zhenhui Ye, **Shengpeng Ji**, Chen Zhang, Pengfei Wei, Chunfeng Wang, Xiang Yin, Zejun MA, Zhou Zhao
- arxiv [Mega-TTS: Zero-Shot Text-to-Speech at Scale with Intrinsic Inductive Bias](), Ziyue Jiang, Yi Ren, Zhenhui Ye, Jinglin Liu, Chen Zhang, Qian Yang, **Shengpeng Ji**, Rongjie Huang, Chunfeng Wang, Xiang Yin, Zejun MA, Zhou Zhao

## 🧑‍🎨 Machine Learning
- ``ICML 2024 submit`` [DiscreteWM: Speech Watermarking with Discrete Representations](), Ziyue Jiang*, **Shengpeng Ji<sup>*</sup>**, Yi Ren, Zhenhui Ye, Rongjie Huang, Jinglin Liu, Chen Zhang, Tianyu Pang, Chao Du, Hongcheng Zhu, Zhou Zhao
- ``IJCAI 2024 submit`` [All in One Image Restoration under Adverse Weather Conditions using Interaction Enhanced Prompts](), Hanting Wang, Tao Jin, **Shengpeng Ji**, Zhou Zhao
- ``CCF A IEEE Transactions on Computers`` [Generating Neural Networks for Diverse Networking Classification Tasks via Hardware-Aware Neural Architecture Search](), Guorui Xie, Qing Li, Zhenning Shi, Hanbin Fang, **Shengpeng Ji**, Yong Jiang, Zhenhui Yuan, Lianbo Ma, Mingwei Xu
- ``CCF B (Chinese) Computer Science`` [A Novel College Entrance Filling Recommendation Algorithm Based on Score Line Prediction and Multi-feature Fusion](), Zeqing Wang, **Shengpeng Ji**, Xin Li, Zixuan Zhao, Pengxu Wang, Xiaosong Han

# 🎖 Honors and Awards
- *2023.06* Outstanding graduate of Jilin University (Top 5%)
- *2023.06* One-class scholarship of Jilin University (Top 1%, 1/392)
- *2022.10* Second-class scholarship of Jilin University
- *2021.10* National Scholarship (Undergraduate) (Top 1%, 5/392)
- *2020.10* Third-class scholarship of Jilin University 

# 📖 Educations
- *2023.09 - 2026.03*, Master, Software Engineering, Zhejiang University.
- *2019.09 - 2023.06*, Undergraduate, Software Engineering, JiLin Univeristy.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.09 - now*, HuaWei Honor,Speech Group, Remote.
- *2023.03 - 2023.08*, [MSRA,Natural Language Computing Group](https://www.microsoft.com/en-us/research/group/natural-language-computing/) <img src='./images/microsoft_logo.svg' style="width: 4em;">, Beijing HaiDian Area.
- *2022.11 - 2023.03*, Ping An Techology Company, ShangHai Pudong Area.
- *2021.11 - 2022.05*, [Tsinghua Shenzhen International Graduate School](https://www.sigs.tsinghua.edu.cn/xxxb/list.htm) <img src='./images/qinghua.png' style='width: 6em;'>, Remote.

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=54e0ojatafc&amp;m=7&amp;c=e63100&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;bv=90&amp;lx=-420&amp;ly=420&amp;hi=20&amp;he=7&amp;hc=a8ddff&amp;rs=80" async="async"></script>
