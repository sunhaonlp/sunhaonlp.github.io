---
permalink: /
title: ""
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

I am a 4th-year PhD candidate in [School of Intelligence Science and Technology](https://www.cis.pku.edu.cn/index.htm) at [Peking University](https://www.pku.edu.cn/), working with Prof. [Y. Zhang](http://www.cis.pku.edu.cn/jzyg/szdw/zy.htm). I obtained my bachelor's degree from the [School of Computer Science and Engineering](https://www.scse.uestc.edu.cn/), [UESTC](https://www.uestc.edu.cn/) in June 2021, under the supervision of Prof. [K. Zheng](http://zheng-Kai.com/). I’ve also spent time at [ByteDance Seed](https://seed.bytedance.com/en/), [Tongyi Lab](https://tongyi.aliyun.com/), [Baidu Reserch](http://research.baidu.com/), [MSRA](https://www.msra.cn/), [DAMO Academy]([https://www.alibaba.com/](https://damo.alibaba.com/)) and [Huawei](https://www.huawei.com/).

My research interests include **Agent**, **RAG** and **LLM**. If you are also interested, please feel free to drop me an email.

<p><span style="color: red;"><strong>I am expected to complete my Ph.D. in June 2026 and will be actively seeking opportunities in both industry and academia. If you are interested, please feel free to reach out.</strong></span></p>


# 🔥 News

- *2025.06*: &nbsp;🎉🎉  My paper [ZeroSearch](https://github.com/Alibaba-NLP/ZeroSearch), which explores reinforcement learning for search agent, has surpassed **1,000 stars**!
- *2025.06*: &nbsp;🎉🎉  Honored to receive the **Presidential Scholarship** (the highest honor for PhD students at PKU)!
- *2025.05*: &nbsp;🎉🎉  Three papers on multimodal retrieval and RAG were accepted by [ACL 2025](https://2025.aclweb.org/)!
- *2025.04*: &nbsp;🎉🎉  Honored to receive the **Academic Star Award** (Top-5 students in School of Intelligence Science and Technology)!
- *2024.09*: &nbsp;🎉🎉  One papers on efficient LLM tuning were accepted by [NeurIPS 2024](https://neurips.cc/Conferences/2024)!
- *2024.09*: &nbsp;🎉🎉  Three papers on RAG and Agent were accepted by [EMNLP 2024](https://2024.emnlp.org/)!
- *2023.10*: &nbsp;🎉🎉  One paper on dense retrieval was accepted by [WSDM 2024](https://www.wsdm-conference.org/2024/)!
- *2023.10*: &nbsp;🎉🎉  One paper on multi-hop QA was accepted by [EMNLP 2023](https://2023.emnlp.org/)!
- *2023.08*: &nbsp;🎉🎉  Honored to receive **Stars of Tomorrow Award** during an internship at Microsoft!
- *2023.05*: &nbsp;🎉🎉  One paper on multi-turn conversation was accepted by [ACL 2023](https://2023.aclweb.org/)!


# 🌟 Highlight
<div class='paper-box'>
<div class='paper-box-image' style="display: inline-block; width: 100%;">
<div>
<div class="badge">Under Review</div>
<img src='../images/zerosearch.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;">
</div>
</div>
<div class='paper-box-text' markdown="1">
[ZeroSearch: Incentivize the Search Capability of LLMs without Searching](https://arxiv.org/pdf/2505.04588) 

**Hao Sun**, Z. Qiao, J. Guo, X. Fan, Y. Hou, Y. Jiang, P. Xie, F. Huang, J. Zhou

 <a href="https://alibaba-nlp.github.io/ZeroSearch/"><strong>Homepage</strong></a>
 \|
 <a href="https://arxiv.org/pdf/2505.04588"><strong>Paper</strong></a>
 \|
 <a href="https://github.com/Alibaba-NLP/ZeroSearch"><strong>Code</strong></a>
 \|
 <a href="https://huggingface.co/collections/sunhaonlp/zerosearch-policy-google-v2-6827f4ee6b6265069d443d4e"><strong>Model</strong></a> 
 🏆 <span style="color: red;"><strong>1000+ stars</strong></span>

<a href="https://mp.weixin.qq.com/s/fq3F4OnOaG9PaF4_NKuRyg"><strong>机器之心</strong></a>
 \|
 <a href="https://mp.weixin.qq.com/s/8l-larvoLPg1aTZXA5EAXg"><strong>量子位</strong></a>
 \|
 <a href="https://www.bilibili.com/video/BV166j9zkEnK/?spm_id_from=333.1387.upload.video_card.click&vd_source=8929f8de0a49705a032c1321cbed3911h"><strong>通义大模型</strong></a>
\|
 <a href="https://x.com/AlibabaGroup/status/1924729349221318957"><strong>Twitter</strong></a>
\|
 <a href="https://huggingface.co/papers/2505.04588"><strong>Huggingface</strong></a>
\|
 <a href="https://venturebeat.com/ai/alibabas-zerosearch-lets-ai-learn-to-google-itself-slashing-training-costs-by-88-percent/"><strong>VentureBeat</strong></a>


**A novel reinforcement learning framework that incentivizes the search capability of LLMs with simulated searches during training.**

</div>
</div>



# 📝 Publications
<div class='paper-box'>
<div class='paper-box-image' style="display: inline-block; width: 100%;">
<div>
<div class="badge">ACL 2025</div>
<img src='../images/unveil.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;">
</div>
</div>
<div class='paper-box-text' markdown="1">
[Unveil: Unified Visual-Textual Integration and Distillation for Multi-modal Document Retrieval](https://arxiv.org)

**Hao Sun**, Y. Hou, J. Guo, B. Wang, C. Yang, J. Ni, Y. Zhang

_The Annual Meeting of the Association for Computational Linguistics_ (**ACL**), 2025

**We propose a novel visual-textual embedding framework that effectively integrates textual and visual features.**

</div>
</div>

<div class='paper-box'>
<div class='paper-box-image' style="display: inline-block; width: 100%;">
<div>
<div class="badge">ACL 2025</div>
<img src='../images/ets.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;">
</div>
</div>
<div class='paper-box-text' markdown="1">
[Enhancing Retrieval-Augmented Generation via Evidence Tree Search](https://arxiv.org) 

**Hao Sun**, H. Cai, Y. Li, X. Fan, X. Wei, S. Wang, Y. Zhang, D. Yin

_The Annual Meeting of the Association for Computational Linguistics_ (**ACL**), 2025

**We propose a novel framework that reformulates evidence retrieval as a dynamic tree expansion process.**

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image' style="display: inline-block; width: 100%;">
<div>
<div class="badge">EMNLP 2024</div>
<img src='../images/vtg.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;">
</div>
</div>
<div class='paper-box-text' markdown="1">
[Towards Verifiable Text Generation with Evolving Memory and Self-Reflection](https://arxiv.org/pdf/2312.09075.pdf) 

**Hao Sun**, H. Cai, B. Wang, Y. Hou, X. Wei, S. Wang, Y. Zhang, D. Yin 

_The Conference on Empirical Methods in Natural Language Processing_ (**EMNLP**), 2024

 <a href="https://arxiv.org/pdf/2312.09075.pdf"><strong>Paper</strong></a>

**Improving citation generation with a two-tier verifier and active retrieval mechanism.**

</div>
</div>



<div class='paper-box'>
<div class='paper-box-image' style="display: inline-block; width: 100%;">
<div>
<div class="badge">EMNLP 2024</div>
<img src='../images/ricp.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;">
</div>
</div>
<div class='paper-box-text' markdown="1">
[Retrieved In-Context Principles from Previous Mistakes](https://arxiv.org/pdf/2407.05682) 

**Hao Sun**, Y. Jiang, B. Wang, Y. Hou, Y. Zhang, P. Xie, F. Huang 

_The Conference on Empirical Methods in Natural Language Processing_ (**EMNLP**), 2024

<a href="https://arxiv.org/pdf/2407.05682"><strong>Paper</strong></a>

**Enabling LLMs to learn from mistakes by proving question-level and task-level principles.**


</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div>
<div class="badge">EMNLP 2024</div>
<img src='../images/adaswitch.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[AdaSwitch: Adaptive Switching between Small and Large Agents for Effective Cloud-Local Collaborative Learning](https://arxiv.org/pdf/2410.13181) 

**Hao Sun**, J. Wu, H. Cai, X. Wei, Y. Feng, B. Wang, S. Wang, Y. Zhang, D. Yin 

_The Conference on Empirical Methods in Natural Language Processing_ (**EMNLP**), 2024

 <a href="https://arxiv.org/pdf/2410.13181"><strong>Paper</strong></a>

**Enabling adaptive switching between local agent and cloud agent through collaborative learning.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">WSDM 2024</div><img src='../images/LEAD.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[LEAD: Liberal Feature-based Distillation for Dense Retrieval](https://arxiv.org/pdf/2212.05225.pdf) 

**Hao Sun**, X. Liu, Y. Gong, A. Dong, J. Lu, Y. Zhang, L. Yang, R. Majumder, N. Duan 

_The ACM International Conference on Web Search and Data Mining_ (**WSDM**), 2024, Oral

<a href="https://arxiv.org/pdf/2212.05225.pdf"><strong>Paper</strong></a>
\|
<a href="https://github.com/microsoft/SimXNS/tree/main/LEAD"><strong>Code</strong></a>

**Distill the intermediate features from teacher to student without the constraints on model architecture or tokenizers.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">EMNLP 2023</div><img src='../images/allies.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[Allies: Prompting Large Language Model with Beam Search](https://aclanthology.org/2023.findings-emnlp.247.pdf)  

**Hao Sun**, X. Liu, Y. Gong, Y. Zhang, N. Duan

_The Conference on Empirical Methods in Natural Language Processing_ (**EMNLP**), 2023, Findings

<a href="https://aclanthology.org/2023.findings-emnlp.247.pdf"><strong>Paper</strong></a>
\|
<a href="https://github.com/microsoft/SimXNS/tree/main/ALLIES"><strong>Code</strong></a>

**Improving the knowledge scope and robustness of LLMs with Beam Search.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">ACL 2023</div><img src='../images/hsge.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[History Semantic Graph Enhanced Conversational KBQA with Temporal Information Modeling](https://arxiv.org/pdf/2306.06872.pdf)  

**Hao Sun**, Y.g Li, L. Deng, B. Li, B. Hui, B. Li, Y. Lan, Y. Zhang, Y. Li

_The Annual Meeting of the Association for Computational Linguistics_ (**ACL**), 2023

<a href="https://arxiv.org/pdf/2306.06872.pdf"><strong>Paper</strong></a>

**Modeling history conversation information with History Semantic Graph.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">SDM 2022</div><img src='../images/conlearn.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[ConLearn: Contextual-knowledge-aware Concept Prerequisite Relation Learning with Graph Neural Network](https://epubs.siam.org/doi/pdf/10.1137/1.9781611977172.14)  

**Hao Sun**, Y. Li, Y. Zhang

_The SIAM International Conference on Data Mining_ (**SDM**), 2022

<a href="https://epubs.siam.org/doi/pdf/10.1137/1.9781611977172.14"><strong>Paper</strong></a> 
\|
<a href="https://github.com/sunhaonlp/ConLearn"><strong>Code</strong></a>

**Capturing complex transition patterns between concepts through Graph Neural Network.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">CIKM 2021</div><img src='../images/periodicmove.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[PeriodicMove: Shift-aware Human Mobility Recovery with Graph Neural Network](https://dl.acm.org/doi/pdf/10.1145/3459637.3482284) 

**Hao Sun**, C. Y.g, L. Deng, F. Zhou, F. Huang, K. Zheng

_The ACM International Conference on Information and Knowledge Management_ (**CIKM**), 2021

<a href="https://dl.acm.org/doi/pdf/10.1145/3459637.3482284"><strong>Paper</strong></a>
\|
<a href="https://github.com/sunhaonlp/PeriodicMove"><strong>Code</strong></a>

**Capturing multi-level periodicity and shifting periodicity of human mobility using attention mechanism.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">DASFAA 2021</div><img src='../images/pdkr.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[Personalized Dynamic Knowledge-Aware Recommendation with Hybrid Explanations](https://link.springer.com/chapter/10.1007/978-3-030-73200-4_10)  

**Hao Sun**, Z. Wu, Y. Cui, L. Deng, Y. Zhao, K. Zheng

_The International Conference on Database Systems for Advanced Applications_ (**DASFAA**), 2021

<a href="https://link.springer.com/chapter/10.1007/978-3-030-73200-4_10"><strong>Paper</strong></a>

**Providing personalized and hybrid explanations for the recommendations.**

</div>
</div>


<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">NeurIPS 2025</div><img src='../images/cmc.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[Cross-model Control: Improving Multiple Large Language Models in One-time Training](https://arxiv.org/pdf/2410.17599) 

J. Wu, **Hao Sun**, H. Cai, L. Su, S. Wang, D. Yin, X. Li, M. Gao


_The Annual Conference on Neural Information Processing Systems_ (**NeurIPS**), 2024

<a href="https://arxiv.org/pdf/2410.17599"><strong>Paper</strong></a>
\|
<a href="https://github.com/wujwyi/CMC"><strong>Code</strong></a>

**Improves multiple LLMs in one-time training with a portable tiny language model.**

</div>
</div>


<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">NeurIPS 2022</div><img src='../images/nci.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[A Neural Corpus Indexer for Document Retrieval](https://arxiv.org/pdf/2206.02743.pdf) 

Y. Wang, Y. Hou, H. Wang, Z. Miao, S. Wu, **Hao Sun**, Q. Chen, Y. Xia, C. Chi, G. Zhao, Z. Liu, X. Xie, H. Allen Sun, W. Deng, Q. Zhang, M. Yang

_The Annual Conference on Neural Information Processing Systems_ (**NeurIPS**), 2022

<a href="https://arxiv.org/pdf/2206.02743.pdf"><strong>Paper</strong></a>
\|
<a href="https://github.com/solidsea98/Neural-Corpus-Indexer-NCI"><strong>Code</strong></a>
🏆 <span style="color: red;"><strong>Outstanding Paper Award</strong></span>

**Propose an end-to-end differentiable document retrieval model that can significantly outperform both inverted index and dense retrieval solutions.**

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image' style="display: inline-block; width: 100%;">
<div>
<div class="badge">ACL 2025</div>
<img src='../images/icl.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;">
</div>
</div>
<div class='paper-box-text' markdown="1">
[Unraveling the Mechanics of Learning-Based Demonstration Selection for In-Context Learning](https://arxiv.org/pdf/2406.11890) 

H Liu, W. Wang, **Hao Sun**, C. Tian, C. Kong, X. Dong, H. Li

_The Annual Meeting of the Association for Computational Linguistics_ (**ACL**), 2025

 <a href="https://arxiv.org/pdf/2406.11890"><strong>Paper</strong></a>

**Investigate the working mechanism of In-Context Learning.**

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image' style="display: inline-block; width: 100%;">
<div>
<div class="badge">NAACL 2025</div>
<img src='../images/parag.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;">
</div>
</div>
<div class='paper-box-text' markdown="1">
[PA-RAG: RAG Alignment via Multi-Perspective Preference Optimization](https://arxiv.org/pdf/2412.14510) 

J Wu, H Cai, L Yan, **Hao Sun**, X Li, S Wang, D Yin, M Gao

_The 2025 Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics_ (**NAACL**), 2025

 <a href="https://arxiv.org/pdf/2412.14510"><strong>Paper</strong></a>

**Optimize the RAG generator to align with RAG requirements comprehensively.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">TOIS 2021</div><img src='../images/skr.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[Sequential-Knowledge-Aware Next POI Recommendation: A Meta-Learning Approach](https://dl.acm.org/doi/pdf/10.1145/3460198) 

Y. Cui, **Hao Sun**, Y. Zhao, H. Yin, K. Zheng

_The ACM Transactions on Information Systems_ (**TOIS**), 2021

 <a href="https://dl.acm.org/doi/pdf/10.1145/3460198"><strong>Paper</strong></a> 

**Utilize sequential, spatiotemporal, and social knowledge to recommend the next POI for a location-based social network user.**

</div>
</div>


<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">TIFS 2023</div><img src='../images/dg.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[Robust Domain Misinformation Detection via Multi-modal Feature Alignment](https://arxiv.org/pdf/2311.14315) 

H Liu, W Wang, **Hao Sun**, A Rocha, H Li

_IEEE Transactions on Information Forensics and Security_ (**TIFS**), 2023

 <a href="https://arxiv.org/pdf/2311.14315"><strong>Paper</strong></a> 

**Reduces the domain shift by aligning the joint distribution of textual and visual modalities through an inter-domain alignment module.**

</div>
</div>


<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">WSDM 2023</div><img src='../images/s2tul.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[S2TUL: A Semi-Supervised Framework for Trajectory-User Linking](https://dl.acm.org/doi/pdf/10.1145/3539597.3570410)  

L. Deng, **Hao Sun**, Y. Zhao, S. Liu, K. Zheng 

_The ACM International Conference on Web Search and Data Mining_ (**WSDM**), 2023

<a href="https://dl.acm.org/doi/pdf/10.1145/3539597.3570410"><strong>Paper</strong></a>

**Capture fine-grained intra-trajectory information by passing the trajectories into the sequential neural networks.**
</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">CIKM 2022</div><img src='../images/CL-TSim.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[Efficient Trajectory Similarity Computation with Contrastive Learning](https://dl.acm.org/doi/pdf/10.1145/3511808.3557308) 

L. Deng, Y. Zhao, Z. Fu, **Hao Sun**, S. Liu, K. Zheng 

_The ACM International Conference on Information and Knowledge Management_ (**CIKM**), 2022

<a href="https://dl.acm.org/doi/pdf/10.1145/3511808.3557308"><strong>Paper</strong></a> 

**Employ a contrastive learning mechanism to learn the representations of trajectories, which are then used to calculate the dissimilarity between them.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">TIST 2022</div><img src='../images/3SGNN.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[Efficient and Effective Similar Subtrajectory Search: A Spatial-aware Comprehension Approach](https://dl.acm.org/doi/pdf/10.1145/3456723) 

L. Deng, **Hao Sun**, R. Sun, Y. Zhao, H. Su

_The ACM Transactions on Intelligent Systems and Technology_ (**TIST**), 2022

<a href="https://dl.acm.org/doi/pdf/10.1145/3456723"><strong>Paper</strong></a> 

**Propose a Similar Subtrajectory Search with a Graph Neural Networks framework.**

</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">CIKM 2022</div><img src='../images/trill.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">

[Fusing Local and Global Mobility Patterns for Trajectory Recovery](https://link.springer.com/chapter/10.1007/978-3-031-30637-2_29) 

L. Deng, Y. Zhao, **Hao Sun**, C. Yang, J. Xie, K. Zheng

_The ACM International Conference on Information and Knowledge Management_ (**CIKM**), 2022

 <a href="https://link.springer.com/chapter/10.1007/978-3-031-30637-2_29"><strong>Paper</strong></a> 

 **Propose a neural attention model based on graph convolutional networks to enhance the accuracy of trajectory recovery.**
</div>
</div>



<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">ICME 2024</div><img src='../images/DisAug.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[Boosting Disfluency Detection with Large Language Model as Disfluency Generator](https://arxiv.org/pdf/2403.08229.pdf)

Z. Cheng, J. Guo, **Hao Sun**, Y. Zhang

_The IEEE International Conference on Multimedia & Expo_ (**ICME**), 2024

 <a href="https://arxiv.org/pdf/2403.08229.pdf"><strong>Paper</strong></a> 

**Propose a framework that addresses data sparsity issues by generating disfluent data using LLM as augmentation data.**

</div>
</div>






# 📒 Preprint

<div class='paper-box'><div class='paper-box-image' style="display: inline-block; width: 100%;"><div><div class="badge">Under Review</div><img src='../images/simcns.jpg' alt="sym" style="width: 100%; height: 160px; object-fit: contain;"></div></div>
<div class='paper-box-text' markdown="1">
[SimCNS: Simple Curriculum Negative Sampling for Multi-Source Dense Retrieval](https://arxiv.org/)

**Hao Sun**, X. Liu, Y. Gong, A. Dong, G. Shi, Y. Zhang, L. Yang, N. Duan

_Under Review_

 <a href="https://arxiv.org"><strong>Paper</strong></a>

**Select the most important negative samples for multi-source dense retrieval**

</div>
</div>


# 🎖 Honors and Awards

- *2025.06* Presidential Scholarship, Peking University.
- *2025.04* Academic Star Award, Peking University.
- *2024.06* First Prize of Challenge Cup Competition, Peking University.
- *2023.09* Merit Student, Peking University.
- *2023.09* Schlumberger Scholarship, Peking University.
- *2023.08* Stars of Tomorrow Award, Microsoft.
- *2023.06* First Prize of Challenge Cup Competition, Peking University.
- *2022.12* Outstanding Paper Award, NeurIPS 2022.
- *2021.06* Outstanding Graduation Thesis for Undergraduates, UESTC.
- *2021.06* Outstanding Graduate, UESTC.
- *2019.12* National Scholarship.
- *2018.09* National Scholarship.

# 📖 Educations

- *2021.09 - Present*, Ph.D. Candidate, Peking University.
- *2017.09 - 2021.06*, Undergraduate, University of Electronic Science and Technology of China.

# 📚 Services

- **Program Committee / Reviewer**: NeurIPS 2024-25, ICLR 2024-25, ICML 2024-25, ACL 2022-25, EMNLP 2022-25
- **Secondary Reviewer**: AAAI 2022, CIKM 2021-22, ICDM 2021-23, COLING 2022-23, DASFAA 2022-23

# 👩🏻‍🏫 Teaching

- *Teaching Assistant,* Computer Networks and Web Technologies, Peking University, Fall 2023

# 💻 Internships
- [ByteDance Seed](https://seed.bytedance.com/en/), focusing on DeepResearch.
- [Tongyi Lab](https://tongyi.aliyun.com/), focusing on Agent and RAG.
- [Baidu Research](http://research.baidu.com/), focusing on RAG and LLM.
- [Microsoft Research Asia (MSRA)](https://www.msra.cn/), focusing on dense retrieval.
- [DAMO Academy](https://damo.alibaba.com/), focusing on multi-turn conversation.
- [HUAWEI Research](https://www.huawei.com/en/), focusing on spatial-temporal data analysis.
