---
title: about me
date: false
#type: "about"
academia: true
---



# Bio #

My name is Zujie Liang (梁祖杰). I am currently a Senior R&D AI Engineer at [Ant Group](https://www.antgroup.com/en) (FinTech giant in China). Now I am building LLM-based Agents to improve credit business including User Understanding, Knowledge Graph, Recommender System, and Risk Management. I have published 10+ papers at the top international AI conferences such as ICLR, ACL, EMNLP, SIGIR, CIKM. Before that, I obtained my M.S. degree from [Sun Yat-Sen University (SYSU)](https://www.sysu.edu.cn) in 2022.

My current research interests🔬 focus on:

- **LLM/VLM Agents**: Building useful LLM/VLM Agents that leverage agentic capabilities to solve real-world tasks, including Agentic Memory [[A-MEM]](https://arxiv.org/abs/2502.12110), Agentic AutoML [[I-MCTS]](https://arxiv.org/abs/2502.14693), Shopping Agents [[iAgent]](https://arxiv.org/abs/2502.14662)[[NTRD]](http://arxiv.org/abs/2109.12302), Multimodal Agents [[Maria]](https://arxiv.org/abs/2105.13073) (Probably one of the earliest attempts at VLM-based agents).

- **LLM Post-training**: Exploring post-training, dedicated to efficient knowledge distillation [[SLMRec]](https://arxiv.org/abs/2405.17890), alleviating the hallucination [[CoKE]](https://arxiv.org/abs/2406.10881), and enhancing the reasoning capabilities [[MultiLingPoT]](https://arxiv.org/abs/2412.12609).

- **Long Context Processing**: Enhancing the long context capablities of LLMs through sparse attention design [[PowerAttention]](https://arxiv.org/abs/2503.03588) and context management framework [[SEGMENT+]](https://arxiv.org/abs/2410.06519).

- **LLM PEFT**: Developing practical approaches for effectively continual training [[Lottery Prompt]](https://aclanthology.org/2023.acl-long.16.pdf) and multi-task learning [[HPT]](https://dl.acm.org/doi/10.1145/3583780.3614913).

- **LLM Benchmarking**: Benchmarking the performance of LLMs on several KG tasks, including Concept Reasoning [[CR-LLM]](https://aclanthology.org/2024.findings-acl.815.pdf), Historical Analogy [[PmP]](https://arxiv.org/abs/2409.14820), and Quotation Generation [[QUILL]](https://arxiv.org/abs/2411.03675).

- **Multimodal Hallucination**: Focusing on alleviating the multimodal hallucination caused by modality bias. [[LPF]](https://arxiv.org/abs/2105.14300)[[CL-VQA]](https://www.aclweb.org/anthology/2020.emnlp-main.265.pdf)


I'm always open to discussion or collaboration. Please check my <a href="attaches/Zujie_Liang_CV.pdf" target="_blank">CV</a> for latest update and drop me an [E-mail](mailto:jokieleung@outlook.com) if you’re interested.


# News #

- [08/2025] One paper is accepted by EMNLP 2025.
- [07/2025] [Our paper](https://arxiv.org/abs/2409.14820) on LLM Historical Analogy received an [Outstanding Paper Award](https://2025.aclweb.org/program/awards/) (Top 0.3%) in ACL 2025, Congrats to Nianqi!
- [05/2025] 2 papers are accepted by ACL 2025.
- [01/2025] One paper is accepted by ICLR 2025.
- [09/2024] One paper is accepted by EMNLP 2024.
- [05/2024] One paper is accepted by Findings of ACL 2024.
- [08/2023] One paper is accepted by CIKM 2023.
- [06/2023] Hosted Ant FinTech AI Challenge (AFAC2023) at [TIANCHI](https://tianchi.aliyun.com/competition/entrance/532088/introduction).
- [05/2023] One paper about Lottery Prompt Tuning is accepted by ACL 2023.
- [07/2022] I start my journey at Ant Group.
- [04/2022] One paper is accepted by ICMR 2022.
- [08/2021] One paper on recommender dialogue system is accepted by EMNLP 2021.
- [06/2021] I am offered an ACM SIGIR 2021 Student Travel Grant.
- [06/2021] I serve as PC Member for NLPCC 2021.
- [05/2021] One paper on visual knowledge powered conversational agent is accepted by ACL 2021.
- [03/2021] One paper on De-biased VQA is accepted by SIGIR 2021.
- [09/2020] One paper on Robust VQA is accepted by EMNLP 2020.



# Work Experiences #

- Ant Group,
  Senior R&D AI Engineer, July. 2022 - Present. 
- Alibaba,
  Ads Algorithm Intern, June. 2021 - Sept. 2021.   
- Microsoft,
  Research Intern, Oct. 2020 - June. 2021. 
- Huawei,
  SDE Intern, Jun. 2018 - Sept. 2018. 


# Publications #

## LLM/VLM Agents

- **A-MEM: Agentic Memory for LLM Agents**
    Wujiang Xu, **Zujie Liang**, Kai Mei, Hang Gao, Juntao Tan, Yongfeng Zhang
    **preprint**. [[paper]](https://arxiv.org/abs/2502.12110)[[code]](https://github.com/WujiangXu/A-mem)

- **I-MCTS: Enhancing Agentic AutoML via Introspective Monte Carlo Tree Search**
    **Zujie Liang**, Feng Wei, Wujiang Xu, Lin Chen, Yuxi Qian, Xinhui Wu
    **preprint**. [[paper]](https://arxiv.org/abs/2502.14693)[[code]](https://github.com/jokieleung/I-MCTS)

- **iAgent: LLM Agent as a Shield between User and Recommender Systems**
    Wujiang Xu, Yunxiao Shi, **Zujie Liang**, Xuying Ning, Kai Mei, Kun Wang, Xi Zhu, Min Xu, Yongfeng Zhang
    **ACL 2025** (Findings). [[paper]](https://arxiv.org/abs/2502.14662)[[code]](https://github.com/WujiangXu/iAgent)
    
- **Maria: A Visual Experience Powered Conversational Agent**
    **Zujie Liang**, Huang Hu, Can Xu, Chongyang Tao, Xiubo Geng, Yining Chen, Fan Liang, Daxin Jiang.
    **ACL 2021**. [[paper]](https://arxiv.org/abs/2105.13073)[[slides]](https://jokieleung.github.io/attaches/ACL-2021-slides.pdf)[[code]](https://github.com/jokieleung/Maria)

- **Learning Neural Templates for Recommender Dialogue System**
    **Zujie Liang***, Huang Hu*, Can Xu, Jian Miao, Yingying He, Yining Chen, Xiubo Geng, Fan Liang, Daxin Jiang
    **EMNLP 2021**. [[paper]](http://arxiv.org/abs/2109.12302)[[code]](https://github.com/jokieleung/NTRD)


## LLM Post-training

- **SLMRec: Distilling Large Language Models into Small for Sequential Recommendation**
    Wujiang Xu, Qitian Wu, **Zujie Liang**, Jiaojiao Han, Xuying Ning, Yunxiao Shi, Wenfang Lin, Yongfeng Zhang
    **ICLR 2025**. [[paper]](https://arxiv.org/abs/2405.17890)[[code]](https://github.com/WujiangXu/SLMRec)

- **Teaching Large Language Models to Express Knowledge Boundary from Their Own Signals**
    Lida Chen, **Zujie Liang**, Xintao Wang, Jiaqing Liang, Yanghua Xiao, Feng Wei, Jinglei Chen, Zhenghong Hao, Bing Han, Wei Wang
    **ACL 2025, KnowFM Workshop**. [[paper]](https://arxiv.org/abs/2406.10881)
    
- **MultiLingPoT: Enhancing Mathematical Reasoning with Multilingual Program Fine-tuning**
    Nianqi Li, **Zujie Liang**, Siyu Yuan, Jiaqing Liang, Feng Wei, Yanghua Xiao
    **EMNLP 2025** (Findings). [[paper]](https://arxiv.org/abs/2412.12609)[[code]](https://github.com/jokieleung/MultiLingPoT)

    
## Long-context LLM

- **PowerAttention: Exponentially Scaling of Receptive Fields for Effective Sparse Attention**
    Lida Chen, Dong Xu, Chenxin An, Xintao Wang, Yikai Zhang, Jiangjie Chen, **Zujie Liang**, Feng Wei, Jiaqing Liang, Yanghua Xiao, Wei Wang
    **preprint**. [[paper]](https://arxiv.org/pdf/2503.03588)[[code]](https://github.com/w568w/PowerAttention)
    
- **Segment+: Long Text Processing with Short-Context Language Models**
    Wei Shi, Shuang Li, Kerun Yu, Jinglei Chen, **Zujie Liang**, Xinhui Wu, Yuxi Qian, Feng Wei, Bo Zheng, Jiaqing Liang, Jiangjie Chen, Yanghua Xiao
    **EMNLP 2024**. [[paper]](https://arxiv.org/abs/2410.06519)


## LLM PEFT

- **Prompts Can Play Lottery Tickets Well: Achieving Lifelong Learning Information Extraction via Lottery Prompt Tuning**
    **Zujie Liang**, Feng Wei, Jie Yin, Yuxi Qian, Zhenghong Hao, Bing Han.
    
    **ACL 2023**. [[paper]](https://aclanthology.org/2023.acl-long.16.pdf)[[code]](https://github.com/jokieleung/Lottery_Prompt)
    
- **Hierarchical Prompt Tuning for Few-Shot Multi-Task Learning**
    Jingping Liu, Tao Chen, **Zujie Liang**, Haiyun Jiang, Yanghua Xiao, Feng Wei, Yuxi Qian, Zhenghong Hao, Bing Han.
    **CIKM 2023**. [[paper]](https://dl.acm.org/doi/10.1145/3583780.3614913)
    

## LLM Benchmarking

- **CR-LLM: A Dataset and Optimization for Concept Reasoning of Large Language Models**
    Nianqi Li, Jingping Liu, Sihang Jiang, Haiyun Jiang, Yanghua Xiao, Jiaqing Liang, **Zujie Liang**, Feng Wei, Jinglei Chen, Zhenghong Hao, Bing Han
    **ACL 2024** (Findings). [[paper]](https://aclanthology.org/2024.findings-acl.815.pdf)
    
- **Past Meets Present: Creating Historical Analogy with Large Language Models**
    Nianqi Li, Siyu Yuan, Jiangjie Chen, Jiaqing Liang, Feng Wei, **Zujie Liang**, Deqing Yang, Yanghua Xiao
    **ACL 2025, oral**. [[paper]](https://arxiv.org/abs/2409.14820)[[Outstanding Paper Award]](https://2025.aclweb.org/program/awards/)(Top 0.3%)
    
- **QUILL: Quotation Generation Enhancement of Large Language Models**
    Jin Xiao, Bowei Zhang, Qianyu He, Jiaqing Liang, Feng Wei, Jinglei Chen, **Zujie Liang**, Deqing Yang, Yanghua Xiao
    **preprint**. [[paper]](https://arxiv.org/abs/2411.03675)
    

## Multimodal Hallucination

- **LPF: A Language-Prior Feedback Objective Function for De-biased Visual Question Answering**
    **Zujie Liang**, Haifeng Hu, Jiaying Zhu.
    **SIGIR 2021**. [[paper]](https://arxiv.org/abs/2105.14300)[[slides]](https://jokieleung.github.io/attaches/LPF_SIGIR21_slides.pdf)[[code]](https://github.com/jokieleung/LPF-VQA)
    
- **Learning to Contrast the Counterfactual Samples for Robust Visual Question Answering**
    **Zujie Liang**, Weitao Jiang, Haifeng Hu, Jiaying Zhu.
    **EMNLP 2020**. [[paper]](https://www.aclweb.org/anthology/2020.emnlp-main.265.pdf)[[slides]](https://jokieleung.github.io/attaches/Learning_to_Contrast_EMNLP_2020_slides.pdf)[[code]](https://github.com/jokieleung/CL-VQA)


# Academic Services #

- Reviewer: ARR 2025, ARR 2024, ICLR 2023, EACL 2023, ACL 2022, NLPCC 2022, NLPCC 2021, IJCAI 2021



# Miscellanous #

- In my spare time, I maintain [Awesome-Visual-Question-Answering](https://github.com/jokieleung/awesome-visual-question-answering), which is a curated list of papers in the field of Visual QA (660+ stars now). 
- Fan of basketball/NBA. I am impressed by the application progress of AI in [basketball](https://becominghuman.ai/5-game-changing-computer-vision-applications-in-sports-5f02ec35529b), such as the [HomeCourt](https://www.homecourt.ai/) APP.
- [Silicon Valley](https://www.imdb.com/title/tt2575988/) is the funniest TV series. [Black Mirror](https://www.imdb.com/title/tt2085059/) is fantastic too.
