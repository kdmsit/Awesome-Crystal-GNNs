
# Awesome-Crystal-GNNs
Recent times, Deep ML models (Specially GNNs) achieved great success towards learning representations of Crystal Materials. This repository contains a collection of resources and papers on Deep Learning Models on ***Crystal Solid State Materials***

## Contents
- [Papers](#papers)
  - [Survey](#survey)
  - [Sequential Models](#sequential-models)
  - [GNN Based models](#gnn-based-models)
  - [Equivariant Networks](#equivariant-networks)
  - [Transformer](#transformer)
  - [Materials Generation](#materials-generation)


# Papers

## Survey

**Recent advances and applications of deep learning methods in materials science** \
*Kamal Choudhary, Brian DeCost, Chi Chen, Anubhav Jain, Francesca Tavazza, Ryan Cohn, Cheol Woo Park, Alok Choudhary, Ankit Agrawal, Simon J. L. Billinge, Elizabeth Holm, Shyue Ping Ong & Chris Wolverton*\
npj Computational Materials  2022. [[Paper](https://www.nature.com/articles/s41524-022-00734-6)] 

## Sequential Models

**Elemnet: Deep learning the chemistry of materials from only elemental composition** \
*Dipendra Jha, Logan Ward, Zijiang Yang, Christopher Wolverton, Ian Foster, Wei-keng Liao,Alok Choudhary,Ankit Agrawal* \
Scientific Reports  2018. [[Paper](https://www.nature.com/articles/s41598-018-35934-y)]

**IRNet: A General Purpose Deep Residual Regression Framework for Materials Discovery** \
*Dipendra Jha, Logan Ward, Zijiang Yang, Christopher Wolverton, Ian Foster, Wei-keng Liao, Alok Choudhary, Ankit Agrawal* \
KDD 2019. [[Paper](https://arxiv.org/pdf/1907.03222.pdf)] 

**Predicting materials properties without crystal structure: deep representation learning from stoichiometry** \
*Rhys E. A. Goodall, Alpha A. Lee* \
Nature communications  2020. [[Paper](https://www.nature.com/articles/s41467-020-19964-7)] 

**Compositionally restricted attention-based network for materials property predictions** \
*Anthony Yu-Tung Wang, Steven K. Kauwe, Ryan J. Murdock & Taylor D. Sparks* \
npj Computational Materials  2021. [[Paper](https://www.nature.com/articles/s41524-021-00545-1)] 

## GNN Based Models

**SchNet: A continuous-filter convolutional neural network for modeling quantum interactions** \
*Kristof T. Schütt, Pieter-Jan Kindermans, Huziel E. Sauceda, Stefan Chmiela, Alexandre Tkatchenko, Klaus-Robert Müller* \
NeurIPS 2017. [[Paper](https://arxiv.org/pdf/1706.08566.pdf)][[Github](https://github.com/atomistic-machine-learning/SchNet)] 

**(CGCNN) Crystal Graph Convolutional Neural Networks for an Accurate and Interpretable Prediction of Material Properties** \
*Tian Xie, Jeffrey C. Grossman* \
Phys. Rev. Lett.  2018. [[Paper](https://www.nature.com/articles/s41524-022-00734-6)][[Github](https://github.com/txie-93/cgcnn)] 

**(MEGNet) Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals** \
*Chi Chen, Weike Ye, Yunxing Zuo, Chen Zheng,Shyue Ping Ong* \
Chemistry of Materials 2019. [[Paper](https://pubs.acs.org/doi/pdf/10.1021/acs.chemmater.9b01294)][[Github](https://github.com/materialsvirtuallab/megnet)] 

**(GATGNN) Graph convolutional neural networks with global attention for improved materials property prediction** \
*Steph-Yves Louis, Yong Zhao, Alireza Nasiri, Xiran Wang, Yuqi Song, Fei Liu, Jianjun Hu* \
Physical Chemistry Chemical Physics  2020. [[Paper](https://pubs.rsc.org/en/content/articlepdf/2020/cp/d0cp01474e)][[Github](https://github.com/superlouis/GATGNN)] 

**Crystal graph attention networks for the prediction of stable materials** \
*Jonathan Schmidt, Love Pettersson, Claudio Verdozzi, Silvana Botti,Miguel A. L. Marques* \
Science Advances 2021. [[Paper](https://www.science.org/doi/epdf/10.1126/sciadv.abi7948)]

**CrysXPP: An explainable property predictor for crystalline materials** \
*Kishalay Das, Bidisha Samanta, Pawan Goyal, Seung-Cheol Lee, Satadeep Bhattacharjee, Niloy Ganguly* \
npj Computational Materials  2021. [[Paper](https://www.nature.com/articles/s41524-022-00716-8)][[Github](https://github.com/kdmsit/crysxpp)] 

**(ALIGNN) Atomistic Line Graph Neural Network for improved materials property predictions** \
*Kamal Choudhary, Brian DeCost* \
npj Computational Materials  2021. [[Paper](https://www.nature.com/articles/s41524-021-00650-1)][[Github](https://github.com/usnistgov/alignn)] 

**(ALIGNN-d) Efficient and interpretable graph network representation for angle-dependent properties applied to optical spectroscopy** \
*Tim Hsu, Tuan Anh Pham, Nathan Keilbart, Stephen Weitzner, James Chapman, Penghao Xiao, S. Roger Qiu,Xiao Chen and Brandon C. Wood* \
npj Computational Materials  2022. [[Paper](https://www.nature.com/articles/s41524-022-00841-4)][[Github](https://github.com/LLNL/graphite)] 

**CrysGNN : Distilling pre-trained knowledge to enhance property prediction for crystalline materials.** \
*Kishalay Das, Bidisha Samanta, Pawan Goyal, Seung-Cheol Lee, Satadeep Bhattacharjee, Niloy Ganguly* \
AAAI 2023 [[Paper](https://arxiv.org/abs/2301.05852)][[Github](https://github.com/kdmsit/crysgnn)] 

**Efficient Approximations of Complete Interatomic Potentials for Crystal Property Prediction.** \
*Yuchao Lin, Keqiang Yan, Youzhi Luo, Yi Liu, Xiaoning Qian, Shuiwang Ji* \
ICML 2023 [[Paper](https://arxiv.org/pdf/2306.10045.pdf)][[Github](https://github.com/divelab/AIRS/tree/main/OpenMat/PotNet)] 

**CrysMMNet: Multimodal Representation for Crystal Property Prediction.** \
*Kishalay Das, Pawan Goyal, Seung-Cheol Lee, Satadeep Bhattacharjee, Niloy Ganguly* \
UAI 2023 [[Paper](https://openreview.net/pdf?id=06jLJiUAKX)][[Github](https://github.com/kdmsit/crysmmnet)] 

**Symmetry-Informed Geometric Representation for Molecules, Proteins, and Crystalline Materials** \
*Shengchao Liu, weitao Du, Yanjing Li, Zhuoxinran Li, Zhiling Zheng, Chenru Duan, Zhi-Ming Ma, Omar Yaghi, Animashree Anandkumar, Christian Borgs, Jennifer Chayes, Hongyu Guo, Jian Tang* \
NeurIPS 2023. [[Paper](https://arxiv.org/pdf/2306.09375.pdf)][[Github](https://github.com/chao1224/Geom3D)] 

**A Diffusion-Based Pre-training Framework for Crystal Property Prediction** \
*Zixing Song; Ziqiao Meng; Irwin King* \
AAAI 2024. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28748/29440)][[Github]()] 

## Transformer

**(Matformer) Periodic Graph Transformers for Crystal Material Property Prediction** \
*Keqiang Yan, Yi Liu, Yuchao Lin, Shuiwang Ji* \
NeurIPS 2022. [[Paper](https://arxiv.org/pdf/2209.11807.pdf)][[Github](https://github.com/YKQ98/Matformer)] 

**Density of States Prediction of Crystalline Materials via Prompt-guided Multi-Modal Transformer** \
*Namkyeong Lee, Heewoong Noh, Sungwon Kim, Dongmin Hyun, Gyoung S. Na, Chanyoung Park* \
NeurIPS 2023. [[Paper]()][[Github]()] 

**Crystalformer: Infinitely Connected Attention for Periodic Structure Encoding** \
*Tatsunori Taniai, Ryo Igarashi, Yuta Suzuki, Naoya Chiba, Kotaro Saito, Yoshitaka Ushiku, Kanta Ono* \
ICLR 2024. [[Paper](https://openreview.net/pdf?id=fxQiecl9HB)][[Github]()] 

**Complete and Efficient Graph Transformers for Crystal Material Property Prediction** \
*Keqiang Yan, Cong Fu, Xiaofeng Qian, Xiaoning Qian, Shuiwang Ji* \
ICLR 2024. [[Paper](https://openreview.net/pdf?id=BnQY9XiRAS)][[Github]()] 

**Conformal Crystal Graph Transformer with Robust Encoding of Periodic Invariance** \
*Yingheng Wang; Shufeng Kong; John M. Gregoire; Carla P. Gomes* \
AAAI 2024. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/27781/27598)][[Github]()] 

## Equivariant Networks

**E(3)-equivariant graph neural networks for data-efficient and accurate interatomic potentials** \
*Simon Batzner, Albert Musaelian, Lixin Sun, Mario Geiger, Jonathan P. Mailoa, Mordechai Kornbluth, Nicola Molinari, Tess E. Smidt, Boris Kozinsky* \
Nature Communications 2022. [[Paper](https://www.nature.com/articles/s41467-022-29939-5)]

**Equivariant Networks for Crystal Structures** \
*Sékou-Oumar Kaba, Siamak Ravanbakhsh* \
NeurIPS 2022. [[Paper](https://openreview.net/pdf?id=0Dh8dz4snu)]

## Materials Generation

**Crystal Diffusion Variational Autoencoder for Periodic Material Generation** \
*Tian Xie, Xiang Fu, Octavian-Eugen Ganea, Regina Barzilay, Tommi Jaakkola* \
ICLR 2021. [[Paper](https://arxiv.org/pdf/2110.06197.pdf)][[Github](https://github.com/txie-93/cdvae)] 

**Towards Symmetry-Aware Generation of Periodic Materials** \
*Youzhi Luo, Chengkai Liu, Shuiwang Ji* \
NeurIPS 2023. [[Paper](https://arxiv.org/pdf/2307.02707.pdf)][[Github](https://github.com/divelab/AIRS/tree/main/OpenMat/SyMat)] 

**Crystal Structure Prediction  by Joint Equivariant Diffusion** \
*Rui Jiao, Wenbing Huang, Peijia Lin, Jiaqi Han, Pin Chen, Yutong Lu, Yang Liu* \
NeurIPS 2023. [[Paper](https://arxiv.org/pdf/2309.04475.pdf)][[Github](https://github.com/jiaor17/DiffCSP)] 

**MatterGen: a generative model for inorganic materials design** \
*Claudio Zeni, Robert Pinsler, Daniel Zügner, Andrew Fowler, Matthew Horton, Xiang Fu, Sasha Shysheya, Jonathan Crabbé, Lixin Sun, Jake Smith, Ryota Tomioka, Tian Xie* \
Arxiv. [[Paper](https://arxiv.org/abs/2312.03687)][[Github]()] 

**Scalable Diffusion for Materials Generation** \
*Sherry Yang, KwangHwan Cho, Amil Merchant, Pieter Abbeel, Dale Schuurmans, Igor Mordatch, Ekin Dogus Cubuk* \
ICLR 2024. [[Paper](https://openreview.net/pdf?id=wm4WlHoXpC)][[Github]()] 

**Fine-Tuned Language Models Generate Stable Inorganic Materials as Text** \
*Nate Gruver, Anuroop Sriram, Andrea Madotto, Andrew Gordon Wilson, C. Lawrence Zitnick, Zachary Ward Ulissi* \
ICLR 2024. [[Paper](https://openreview.net/pdf?id=vN9fpfqoP1)][[Github](https://github.com/facebookresearch/crystal-llm?tab=readme-ov-file)] 

**Space Group Constrained Crystal Generation** \
*Rui Jiao, Wenbing Huang, Yu Liu, Deli Zhao, Yang Liu* \
ICLR 2024. [[Paper](https://openreview.net/pdf?id=jkvZ7v4OmP)][[Github]()] 


## Benchmarks

**M2Hub: Unlocking the Potential of Machine Learning for Materials Discovery** \
*Yuanqi Du, Yingheng Wang, Yining Huang, Jianan Canal Li, Yanqiao Zhu, Tian Xie, Chenru Duan, John Gregoire, Carla Gomes* \
NeurIPS 2023. [[Paper](https://arxiv.org/pdf/2307.05378.pdf)][[Github](https://github.com/yuanqidu/M2Hub)] 

