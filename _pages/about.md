---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Short Bios
------
I am currently a research assistant professor at [Southern University of Science and Technology](https://www.sustech.edu.cn/en/) (SUSTech), working with [Prof. Yinqian Zhang](https://yinqian.org/). I received my Ph.D. degree from [The University of British Columbia](https://ok.ubc.ca/) (UBC) in Sep. 2021, under the supervision of [Prof. Chen Feng](https://engineering.ok.ubc.ca/about/contact/chen-feng/). 

**[Opening] I am looking for self-motivated students (1-2 Master students) to start in fall 2025 at SUSTech**

Research
------
My research fields include blockchain, distributed systems, and confidential computing.  Below are some major research projects.

**Analysis of blockchain incentive and consensus**: This project applies stochastic processes to analyze decentralized incentive and BFT consensus designs. Related works include Ethereum (selfish mining, [ICDCS'19](https://arxiv.org/abs/1901.04620)), Bitcoin-NG (selfish mining, [Performance'20](https://arxiv.org/pdf/2001.05082.pdf)), chained HotStuff (evaluation framework, [INFOCOM'21](https://arxiv.org/abs/2107.04947)),  Crystal (transparent mining protocol, [TDSC'22](https://arxiv.org/abs/2312.00741)), and private transactions ([ACSAC'24](https://jianyu-niu.github.io/)).  

**BFT consensus at scale**: This project aims to design simple and scalable BFT systems. Related works include Hermes (structured transmission, [TDSC'21](https://ieeexplore.ieee.org/document/9543565)), EBFT (extreme simplicity, [Homepage](https://ebftalgorithm.github.io/)), Fast-HotStuff (robust chained BFT, [TDSC'23](https://arxiv.org/abs/2010.11454)), Stratus (shared mempool, [ICDE'23](https://github.com/gitferry/bamboo-stratus)), and Ladon (multi-BFT consensus, [EuroSys'25](https://arxiv.org/abs/2409.10954)).

**Distributed confidential computing**: This project explores integrations of confidential computing and various distributed computing techniques like blockchains and Federated Learning. Related works include Engraft (confidential consensus, [CCS'22](https://dl.acm.org/doi/10.1145/3548606.3560639)), and Narrator/Narrator-Pro (state continuity system, [CCS'22](https://dl.acm.org/doi/10.1145/3548606.3560620)/[TDSC'24](https://ieeexplore.ieee.org/abstract/document/10480251)), and Mercury/TeeRollup ([Exchange](https://arxiv.org/abs/2409.14640)/[Layer 2](https://arxiv.org/abs/2409.14647)).  

News
------
- (2024/11)**[Service]** I am invited to serve on the technical program committee of [ACM/IFIP Middleware'25](https://middleware-conf.github.io/2025/).
- (2024/11)**[Paper]** Our work about side-channel attacks on KV cache sharing of multi-tenant LLM serving has been accepted to [NDSS'25](https://www.ndss-symposium.org/ndss2025/). 
- (2024/10)**[Service]** I am invited to serve on the technical program committee of [ACM CCS'25](https://www.sigsac.org/ccs/CCS2025/).
- (2024/08)**[Service]** I am invited to serve on the technical program committee of [AsiaCCS'25](https://asiaccs2025.hust.edu.vn/).
- (2024/07)**[Paper]** Our work, Ladon, a high-performance multi-BFT protocol has been accepted to [EuroSys'25](). 
- (2024/03)**[Paper]** Our work, Narrator-Pro (an extension to Narrator), has been accepted to [TDSC](https://ieeexplore.ieee.org/abstract/document/10480251). 
- (2024/03)**[Service]** I am invited to serve on the technical program committee of [IEEE GBC'24](http://ieee-gbc.org/).
- (2024/01)**[Service]** I am invited to serve on the technical program committee of [ACM CCS'24](https://www.sigsac.org/ccs/CCS2024/).
- (2023/08)**[Paper]** Our work, Fast-HotStuff, has been accepted to [TDSC](https://ieeexplore.ieee.org/document/10041785), respectively.
- (2023/02)**[Paper]** Our work, SodsBC, has been accepted to [TDSC](https://ieeexplore.ieee.org/document/10041785).
- (2022/10)**[Paper]** Our paper, “Crystal: Enhancing Blockchain Mining Transparency with Quorum Certificate”, has been accepted to [TDSC](https://ieeexplore.ieee.org/xpl/aboutJournal.jsp?punumber=8858).
- (2022/08)**[Paper]** Our work, Narrator, has been accepted to [CCS 2022](https://www.sigsac.org/ccs/CCS2022/).
- (2022/08)**[Paper]** Our paper, “ENGRAFT: Enclave-guarded Raft on Byzantine Faulty Nodes”, has been accepted to [CCS 2022](https://www.sigsac.org/ccs/CCS2022/).
- (2022/08)**[Paper]** Our paper, “Scaling Blockchain Consensus via a Robust Shared Mempool”, has been accepted to [ICDE 2023](https://icde2023.ics.uci.edu/).
- (2022/04)**[Paper]** Our paper, “When Power-of-d-Choices Meets Priority”, has been accepted to [IWQoS 2022](https://iwqos2022.ieee-iwqos.org/).
- (2021/12)**[Paper]** Our paper, “Publish or Perish: Defending Withholding Attack in Dfinity Consensus”, has been selected as the best paper in [MSN 2021](https://www.ieee-msn.org/2021/).

Preprints
------
1. **Analysis of Nakamoto Consensus, Revisited**  
**Jianyu Niu**, Chen Feng, Hoang Dau, Yu-Chih Huang, Jingge Zhu  
[[Paper]](https://arxiv.org/pdf/1910.08510.pdf) [[Selected as "Paper of the Week" (Issue #31) by ZK Capital]](https://zkcapital.substack.com/p/this-week-in-blockchain-research-927?token=eyJ1c2VyX2lkIjoyNzY3MzU2LCJwb3N0X2lkIjoxNTI4MDcsIl8iOiIrK24rMCIsImlhdCI6MTYzMjQ0ODMxNCwiZXhwIjoxNjMyNDUxOTE0LCJpc3MiOiJwdWItNjQ0MSIsInN1YiI6InBvc3QtcmVhY3Rpb24ifQ.n361wEaWHTRxnXO63B-vNwv9mzFIUGk5qCs0q2yScJk)  
1. **EBFT: Simplifying BFT Consensus Through Egalitarianism**  
**Jianyu Niu**, Runchao Han, <ins>Shengqi Liu</ins>, Fangyu Gai, Ivan Beschastnikh, Yinqian Zhang, Chen Feng  
**[[One variant used in VeChain]](https://github.com/vechain/VIPs/blob/master/vips/VIP-220.md) [[Paper]](https://arxiv.org/pdf/2012.01636.pdf) [[Previous version selected as reading list by Stanford EE374]](http://web.stanford.edu/class/ee374/)**  
1. **An Empirical Study on Ethereum Private Transactions and the Security Implications** [[Paper]](https://arxiv.org/abs/2208.02858)  
Xingyu Lyu, Mengya Zhang, Xiaokuan Zhang, **Jianyu Niu**, Yinqian Zhang, Zhiqiang Lin
1. **Mercury: Practical Cross-Chain Exchange via Trusted Hardware**  [[Paper]](https://arxiv.org/abs/2409.14640)  
<ins>Xiaoqing Wen</ins>, <ins>Quanbi Feng</ins>, **Jianyu Niu***, Yinqian Zhang, Chen Feng  
1. **TeeRollup: Efficient Rollup Design Using Heterogeneous TEE** [[Paper]](https://arxiv.org/abs/2409.14647)  
<ins>Xiaoqing Wen</ins>, <ins>Quanbi Feng</ins>, **Jianyu Niu***, Yinqian Zhang, Chen Feng  
1. **Klotski: Towards Consensus Enabled Collaborative Vehicles in Intelligent Transportation**  
<ins>Yuanhang Zhou</ins>, <ins>Shubo Peng</ins>, <ins>Hanzheng Lyu</ins>, Fei Tong, Chengqiang Huang, **Jianyu Niu***, in submission.
1. **Leader Rotation Is Not Enough: Scrutinizing Leadership Democracy of Chained BFT Consensus**  [[Paper]](https://arxiv.org/pdf/2501.02970)   
<ins>Yining Tang</ins>, **Jianyu Niu***, Runchao Han, Chen Feng, and Yinqian Zhang, in submission.
1. **Fides: Scalable Censorship-Resistant DAG Consensus via Trusted Components**  [[Paper]](https://arxiv.org/abs/2501.01062)  
<ins>Shaokang Xie</ins>, Dakai Kang, <ins>Hanzheng Lyu</ins>, **Jianyu Niu**, Mohammad Sadoghi.

Selected Conference Publications (*corresponding author, _ supervised students)
------
 1. **<small>[NDSS'25]</small> I Know What You Asked: Prompt Leakage via KV-Cache Sharing in Multi-Tenant LLM Serving**  
Guanlong Wu, Zheng Zhang, Weili Wang, **Jianyu Niu**, Yao Zhang, Ye Wu, Yinqian Zhang  
_The Network and Distributed System Security Symposium_, San Diego, California. Feb 2025.
 1. **<small>[EuroSys'25]</small> Ladon: High-Performance Multi-BFT Consensus via Dynamic Global Ordering** [[Extended]](https://arxiv.org/abs/2409.10954)  
<ins>Hanzheng Lyu</ins>, <ins>Shaokang Xie</ins>, **Jianyu Niu***, Chen Feng, Yinqian Zhang, Ivan Beschastnikh  
_European Conference on Computer Systems_, Rotterdam, Netherlands, Apr 2025.
 1. **<small>[ACSAC'24]</small> Breaking the Privacy Barrier: On the Feasibility of Reorganization Attacks on Ethereum Private Transaction**  
 Mengya Zhang, Xingyu Lyu, **Jianyu Niu**, Xiaokuan Zhang, Yinqian Zhang, and Zhiqiang Lin  
_Annual Computer Security Applications Conference_, December 2024.  
 1. **<small>[FORTE'24]</small> Formally Verifying a Rollback-Prevention Protocol for TEEs**  
 Weili Wang,  **Jianyu Niu**, Michael K. Reiter, Yinqian Zhang  
_International Conference on Formal Techniques for Distributed Objects, Components, and Systems_.
 1. **<small>[SEED'24]</small> SoK: Opportunities for Accelerating Multi-Party Computation via 
  Trusted Hardware**  
Tong Liu, Zhen Huang, Jiaao Li, **Jianyu Niu**, Guoxing Chen, Yinqian Zhang   
_International Symposium on Secure and Private Execution Environment Design_.  
 1. **<small>[SecureComm'23]</small> Byzantine Protocols with Asymptotically Optimal Communication Complexity**  
<ins>Hanzheng Lyu</ins>, <ins>Shaokang Xie</ins>, **Jianyu Niu**, Chen Feng   
_EAI International Conference on Security and Privacy in Communication Networks_.  
 1. **<small>[ICDE'23]</small> Scaling Blockchain Consensus via a Robust Shared Mempool**  
Fangyu Gai, **Jianyu Niu***, Ivan Beschastnikh, Chen Feng, Sheng Wang  
_IEEE International Conference on Data Engineering_.
 1. **<small>[CCS'22]</small> Narrator: Secure and Practical State Continuity for Trusted Execution in the Cloud**  
**Jianyu Niu**, Wei Peng, Xiaokuan Zhang, Yinqian Zhang  
_ACM Conference on Computer and Communications Security_.
 1. **<small>[CCS'22]</small> ENGRAFT: Enclave-guarded Raft on Byzantine Faulty Nodes**  
Weili Wang, Sen Deng, **Jianyu Niu**, Michael K. Reiter, Yinqian Zhang  
_ACM Conference on Computer and Communications Security_.
1. **<small>[MSN'21]</small> Publish or Perish: Defending Withholding Attack in Dfinity Consensus**  (<font color=Red>Best Paper Award</font>)  
<ins>Hanzheng Lyu</ins>, **Jianyu Niu**, Fangyu Gai, Chen Feng   
_IEEE International Conference on Mobility, Sensing and Networking_, Virtual, Dec. 2021.  
1. **<small>[ICDCS'21]</small> Dissecting the Performance of Chained-BFT**  
Fangyu Gai, Ali Farahbakhsh, **Jianyu Niu**, Chen Feng, Ivan Beschastnikh, Hao Duan  
_IEEE International Conference on Distributed Computing Systems_, Virtual, Jul. 2021.
1. **<small>[INFOCOM'21]</small> On the Performance of Pipelined HotStuff**  [[Blogs]](https://salemal.medium.com/on-the-performance-of-pipelined-hotstuff-a8e468f66095)  
**Jianyu Niu**, Fangyu Gai, Mohammad Mussadiq Jalalzai, Chen Feng  
_IEEE International Conference on Computer Communications_, Virtual, May. 2021.
1. **<small>[Performance'20]</small> Incentive Analysis of Bitcoin-NG, Revisited**  
**Jianyu Niu**, Ziyu Wang, Fangyu Gai, Chen Feng  
_International Symposium on Computer Performance, Modeling, Measurements and Evaluation_, Virtual, Nov. 2020.
1. **<small>[ICDCS'19]</small> Selfish Mining in Ethereum**  
**Jianyu Niu**, Chen Feng  
_IEEE International Conference on Distributed Computing Systems_, Dallas, Texas, Jun. 2019.

Selected Journal Publications
---
1. **<small>[TDSC]</small>  Ensuring State Continuity for Confidential Computing: A Blockchain-based Approach**  
Wei Peng, Xiang Li, **Jianyu Niu***, Xiaokuan Zhang, Yinqian Zhang  
_IEEE Transactions on Dependable and Secure Computing_, 2024.  
1. **<small>[TDSC]</small>  A Privacy-Preserving Incentive Mechanism for Mobile Crowdsensing based on Blockchain**  
Fei Tong, Yuanhang Zhou, Kaiming Wang, Guang Cheng, **Jianyu Niu**, Shibo He  
_IEEE Transactions on Dependable and Secure Computing_, 2024.
1. **<small>[TDSC]</small>  Fast-Hotstuff: A Fast and Resilient Hotstuff Protocol**  
Mohammad Jalalzai, **Jianyu Niu**, Chen Feng, Fangyu Gai  
[[Paper]](https://arxiv.org/pdf/2010.11454.pdf) [[Selected as reading list by Stanford EE374]](http://web.stanford.edu/class/ee374/) [\[Used in Deso](https://revolution.deso.com/) [and Zilliqa 2.0\]](https://blog.zilliqa.com/evm-and-the-road-to-zilliqa-2-0-upgrading-network-efficiency/)  
_IEEE Transactions on Dependable and Secure Computing_, 2023.  
1. **<small>[IoTJ]</small> A Secure Sidechain for Decentralized Trading in Internet of Things**  
Fangyu Gai , **Jianyu Niu***, Mohammad M. Jalalzai , Seyed Ali Tabatabaee, Chen Feng  
_IEEE Internet of Things Journal_, 2023.
1. **<small>[TDSC]</small>  SodsBC: A Practical Post-quantum by Design Asynchronous Blockchain Framework**  
Shlomi Dolev, Bingyong Guo, **Jianyu Niu**, Ziyu Wang (**Alphabetically ordered**)  
_IEEE Transactions on Dependable and Secure Computing_, 2023. 
1. **<small>[TDSC]</small> Crystal: Enhancing Blockchain Mining Transparency with Quorum Certificate**  
**Jianyu Niu**, Fangyu Gai, Runchao Han, Ren Zhang, Yinqian Zhang, Chen Feng  
_IEEE Transactions on Dependable and Secure Computing_, 2022.
1. **<small>[TDSC]</small> The Hermes BFT for Blockchains**  
Mohammad Jalalzai, Chen Feng, Costas Busch, Golden, Richard III, **Jianyu Niu**  
_IEEE Transactions on Dependable and Secure Computing_, 2021.
1. **<small>[PEVA]</small> Incentive Analysis of Bitcoin-NG, Revisited**  
**Jianyu Niu**, Ziyu Wang, Fangyu Gai, Chen Feng  
_Elsevier journal Performance Evaluation_ （**Fast tracked from Performance'20**), 2020.


Mentoring Students 
-----
**Ph.D. Students:**
- [Hanzheng Lyu](https://hanzheng2021.github.io/)  (2021.9-, UBCO, co-advised with Prof. Chen Feng)
- Xiaoqing Wen  (2022.11-, UBCO, co-advised with Prof. Chen Feng)

**Master Students:**
- Yining Tang  (2022.11-, SUSTech, co-advised with Prof. Yinqian Zhang)
- Tong Liu (2024.6-, SUSTech, co-advised with Prof. Yinqian Zhang)
- Quanbi Feng (2024.9-, SUSTech)
- Shubo Peng (2024.9-, SUSTech)

**Undergraduate Students (Thesis):**
- Qiyuan Huang (2024.9-)
- Hongjing Huang (2024.9-)
- Qihang Luo (2024.9-)
- Dahui Li (2024.9-)
- Shaokang Xie (2023.9-2024.6, next position: PhD at UC Davis)
- Quanbi Feng (2023.9-2024.6, next position:  MSc at SUSTech)
- Shubo Peng (2023.9-2024.6, next position: MSc at SUSTech)
- Hang Huang (2023.9-2024.6, next position: Huawei 2012 Lab)
- Shengqi Liu (2023.9-2024.6, next position: MSc at UIUC)

**Research Assistants & Interns:**
- Yinan Mi (2023.9-2024.10)
- Hongyan Sun (2024.4-2024.6)

**Visting Students:**
- [Yuanhang Zhou](https://scholar.google.com/citations?user=Cu431uMAAAAJ) (2023.6-2024.01, MSc at SEU, next position: PhD at HKBU)
- Shuo Yang (2023.10-2024.8, MPhil at CUHK, next position: PhD at CityU)

Professional Activities
-----
**Program Committee Member**
- ACM/IFIP International Middleware Conference (Middleware) [2025](https://middleware-conf.github.io/2025/)
- ACM Conference on Computer and Communications Security (CCS) [2024](https://www.sigsac.org/ccs/CCS2024/), [2025](https://www.sigsac.org/ccs/CCS2025/)
- IEEE International Conference on Mobility, Sensing and Networking (MSN) [2021](https://ieee-msn.org/2021/)
- ACM Asia Conference on Computer and Communications Security (AsiaCCS) [2025](https://asiaccs2025.hust.edu.vn/)

**Journal & Conference Reviewer**
- IEEE Network, 2023.
- ELSP Blockchain, 2024.
- IEEE Transactions on Computer (TC), 2023.
- IEEE Internet of Things Journal (IoTJ), 2024.
- IEEE Communications Letters (CL), Exemplary Reviewers (2019), 2019.
- IEEE Transactions on Dependable and Secure Computing (TDSC), 2024.
- IEEE Open Journal of the Communications Society, 2020, 2021, 2022, 2023, 2024.
- Asia Conference on Computer and Communications Security (AsiaCCS), 2024.
- International Conference on Parallel and Distributed Systems (ICPADS), 2024.

Last updated: 2024/11.
