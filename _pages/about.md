---
permalink: /
title: "Cehao Yang - Homepage"
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

My name is Cehao Yang(杨策皓), a third-year PhD in Artificial Intelligence. Currently I'm studying the HKUST(GZ)-IDEA Joint PhD Program, proudly supervised by Prof.[Hui Xiong](https://scholar.google.com/citations?hl=en&user=cVDF1tkAAAAJ) and Prof.[Jian Guo](https://www.idea.edu.cn/person/guojian/).

🤔 Currently, my research interests primarily focus on Large Language Models (LLMs), covering the following topics:
- **Knowledge-Augmented LLMs**: utilizing external knowledge base to enhance LLMs' reasoning
- **Synthetic Data**: generating high-quality datasets for training LLMs efficiently
- **Knowledge Graph**: synergizing LLMs and knowledge graphs for application

🙌 Thanks for your reading! If you are interested in my research, welcome for discussion and collaboration!

# 🔥 News
- *2026.08*: &nbsp;🎉🎉 I’m excited to be joining Tencent Project UP as a Research Intern. Looking forward to this new journey!
- *2026.05*: &nbsp;🎉🎉 Our survey ([A Survey of Agent Skills](https://www.preprints.org/manuscript/202605.1276)) has been released on Preprint. Feel free to have a look!
- *2026.04*: &nbsp;🎉🎉 One paper ([DataArc-SynData-Toolkit](https://aclanthology.org/2026.acl-demo.31/)) is accepted by ACL 2026 Demo!
- *2026.04*: &nbsp;🎉🎉 Two paper ([Select2Reason](https://arxiv.org/abs/2505.17266)) about ***Reasoning Instruction Data Selection*** and ([ConflictsHarm](https://arxiv.org/abs/2604.09750)) about ***JailBreaking*** are accepted by ACL 2026 Findings!
- *2026.04*: &nbsp;🎉🎉 One paper ([LLM-Oriented Information Retrieval]()) about ***Information Denoising*** is accepted by SIGIR 2026 Perspectives Track!
- *2026.01*: &nbsp;🎉🎉 One paper ([Encrypted Synthetic Data](https://arxiv.org/abs/2601.05635)) about ***Privacy-Preserving*** is accepted by EACL 2026 Findings!
- *2025.12*: &nbsp;🎉🎉 One open-source project ([DataArc-SynData-Toolkit](https://github.com/DataArcTech/DataArc-SynData-Toolkit)) has been released. Feel free to have a try!
- *2025.10*: &nbsp;🎉🎉 One paper ([SoG](https://arxiv.org/abs/2505.00979)) about ***Synthetic Data Driven by Knowledge Graph*** is accepted by LoG 2025!
- *2025.08*: &nbsp;🎉🎉 One paper ([Beyond Function-Level Search](https://aclanthology.org/anthology-files/pdf/findings/2025.findings-emnlp.1147.pdf)) about ***Code Retrieval*** is accepted by EMNLP 2025 Findings! 
- *2025.05*: &nbsp;🎉🎉 One paper ([LongFaith](https://arxiv.org/abs/2502.12583)) about ***Synthetic Data for Long-Context Reasoning*** is accepted by ACL 2025 Findings!
- *2025.04*: &nbsp;🎉🎉 Our paper ([KGR3](https://arxiv.org/pdf/2411.08165)) is reported by DeepTech深科技, click ([here](https://mp.weixin.qq.com/s/mM1Z9O_bITxDHgJf8eD5Rg?poc_token=HKuTRmijNwEce9xoQjr3K2CogT5N8bWm61R9PkGX)) to read!
- *2025.01*: &nbsp;🎉🎉 One paper ([ToG2.0](https://arxiv.org/abs/2407.10805)) about ***Knowledge Graph-augmented LLM*** is accepted by ICLR 2025!
- *2025.01*: &nbsp;🎉🎉 One paper ([KGR3](https://arxiv.org/pdf/2411.08165)) about ***LLM-driven Knowledge Graph Completion*** is accepted by NAACL 2025 Main!
- *2024.12*: &nbsp;🎉🎉 One paper ([CATS](https://arxiv.org/abs/2410.16803)) about ***LLM-driven Inductive Knowledge Graph Completion*** is accepted by AAAI 2025!

# 📝 Selected Publications 
1. ``ACL 2026 Findings`` [SELECT2REASON: Efficient Instruction-Tuning Data Selection for Long-CoT Reasoning](https://arxiv.org/abs/2505.17266)  
   **Cehao Yang**<sup>&#42;</sup>, Xueyuan Lin<sup>&#42;</sup>, Xiaojun Wu<sup>&#42;</sup>, Chengjin Xu, Xuhui Jiang, Honghao Liu, Hui Xiong, Jian Guo.

3. ``ACL 2025 Findings`` [LongFaith: Enhancing Long-Context Reasoning in LLMs with Faithful Synthetic Data](https://arxiv.org/abs/2502.12583)  [![GitHub](https://img.shields.io/badge/GitHub-LongFaith-blue?logo=github)](https://github.com/IDEA-FinAI/LongFaith)  
   **Cehao Yang**<sup>&#42;</sup>, Xueyuan Lin<sup>&#42;</sup>, Chengjin Xu<sup>&#42;</sup>, Xuhui Jiang, Shengjie Ma, Aofan Liu, Hui Xiong, Jian Guo

4. ``ACL 2026 Demo`` [DataArc-SynData-Toolkit: A Unified Closed-Loop Framework for Multi-Path, Multimodal, and Multilingual Data Synthesis](https://aclanthology.org/2026.acl-demo.31/)  
   Zhichao Shi<sup>&#42;</sup>, **Cehao Yang**<sup>&#42;</sup>, Hao Zhou<sup>&#42;</sup>, Xiaojun Wu, Huajie Li, Xuhui Jiang, Chengjin Xu, Yuanzhuo Wang, Jian Guo

5. ``ICLR 2025`` [Think-on-Graph 2.0: Deep and Faithful Large Language Model Reasoning with Knowledge-guided Retrieval Augmented Generation](https://arxiv.org/abs/2407.10805)  [![GitHub](https://img.shields.io/badge/GitHub-ToG2.0-blue?logo=github)](https://github.com/IDEA-FinAI/ToG-2)  
   Shengjie Ma, Chengjin Xu, Xuhui Jiang, Muzhi Li, Huaren Qu, **Cehao Yang**, Jiaxin Mao, Jian Guo

6. ``NAACL 2025 Main`` [Retrieval, Reasoning, Re-ranking: A Context-Enriched Framework for Knowledge Graph Completion](https://arxiv.org/abs/2411.08165)  
   Muzhi Li<sup>&#42;</sup>, **Cehao Yang**<sup>&#42;</sup>, Chengjin Xu<sup>&#42;</sup>, Xuhui Jiang, Yiyan Qi, Jian Guo, Ho-fung Leung, Irwin King

7. ``AAAI 2025`` [Context-aware Inductive Knowledge Graph Completion with Latent Type Constraints and Subgraph Reasoning](https://arxiv.org/abs/2410.16803)  [![GitHub](https://img.shields.io/badge/GitHub-CATS-blue?logo=github)](https://github.com/IDEA-FinAI/CATS)  
   Muzhi Li<sup>&#42;</sup>, **Cehao Yang**<sup>&#42;</sup>, Chengjin Xu<sup>&#42;</sup>, Zixing Song, Xuhui Jiang, Jian Guo, Ho-fung Leung, Irwin King

# ✍️ Selected Pre-prints
2. [GraphSearch: An Agentic Deep Searching Workflow for Graph Retrieval-Augmented Generation](https://www.arxiv.org/abs/2509.22009)   [![GitHub](https://img.shields.io/badge/GitHub-GraphSearch-blue?logo=github)](https://github.com/DataArcTech/GraphSearch)  
   **Cehao Yang**<sup>&#42;</sup>, Xiaojun Wu<sup>&#42;</sup>, Xueyuan Lin<sup>&#42;</sup>, Chengjin Xu, Xuhui Jiang, Yuanliang Sun, Jia Li, Hui Xiong, Jian Guo

3. [Think-on-Graph 3.0: Efficient and Adaptive LLM Reasoning on Heterogeneous Graphs via Multi-Agent Dual-Evolving Context Retrieval](https://www.arxiv.org/abs/2509.21710) [![GitHub](https://img.shields.io/badge/GitHub-ToG3.0-blue?logo=github)](https://github.com/DataArcTech/RAG-Factory)   
   Xiaojun Wu<sup>&#42;</sup>, **Cehao Yang**<sup>&#42;</sup>, Xueyuan Lin<sup>&#42;</sup>, Chengjin Xu, Xuhui Jiang, Yuanliang Sun, Hui Xiong, Jia Li, Jian Guo

# 🎖 Honors and Awards
- *2024.09 - 2028.09*, Ph.D. Full Scholarship (￥720,000)
- *2022.09 - 2024.09*, M.Phil. Full Scholarship (￥240,000)

# 📖 Educations
- *2024.09 - Now*, Ph.D. in Artificial Intelligence, Hong Kong University of Science and Technology (Guangzhou). 
- *2022.09 - 2024.11*, M.Phil. in Artificial Intelligence, Hong Kong University of Science and Technology (Guangzhou). 
- *2018.09 - 2022.06*, B.S. in Computer Science and Engineering, South China University of Technology. 

# 💁 Volunteer
- Reviewer: ACL'25, AAAI PDLM'25, ACM MM'25, NeurIPS'25, ACL SRW'25, EMNLP'25, AAAI'26, AACL'26, ICLR'26, EACL'26, ACL'26, ACM MM'26, COLM'26, NeurIPS'26, EMNLP'26, AAAI'27, NAACL'27, ICLR'27
- 2025.07 - 2025.08, Red Bird Challenge Camp, HKUST(GZ), Teaching Assistant
- 2024.09 - 2024.12, AIAA5088: Natural Language Processing and Its Applications (2024-2025 Fall), Teaching Assistant
- 2023.07 - 2023.08, Red Bird Challenge Camp, HKUST(GZ), Teaching Assistant

# 💻 Internships
- *2026.09 - Now*, Technical Research Intern, Tencent LightSpeed, Shenzhen.
- *2025.01 - 2026.08*, Technical Research Intern, DataArcTech Ltd.
- *2023.08 - 2024.12*, NLP Research Intern, IDEA FinAI, Shenzhen.
- *2021.06 - 2021.09*, Back-end Research & Development Intern, ByteDance, Shenzhen.
