# paper-sharing
## Table of Content

* [Object Reidentification](#Object_Reidentification)
   * [Text-Image Reidentification](#Text_Image_Reidentification)
   * [Visible-Infrared Reidentification](#Visible_Infrared_Reidentification)
* [Masked Vision and Language Model](#Masked_Vision_and_Language_Model)
   * Masked Image Model
   * Masked Language Model
* [Pre-training](#Pre_training)
* [Prompting Learning](#Prompting_Learning)
* [Multimodal Large Language Models](#Multimodal_Large_Language_Models)
* [Cross-modal Retrieval](#Cross_modal_Retrieval)
* [Fine Tuning](#Fine_Tuning)
<span id="Object_Reidentification"></span>
## Object Reidentification
<span id="Text_Image_Reidentification"></span>
### Text-Image Reidentification
| Date   | keywords   | Institute   | Paper | Publication|  code  |
| :-------:| :-----:  | :----:  |:----:  |:----:  |:----:  |
| 2023  | Text-to-Image Person Retrieval |Wuhan University|  [Cross-Modal Implicit Relation Reasoning and Aligning for Text-to-Image Person Retrieval](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_Cross-Modal_Implicit_Relation_Reasoning_and_Aligning_for_Text-to-Image_Person_Retrieval_CVPR_2023_paper.pdf)   |CVPR   |https://github.com/anosorae/IRRA|
| 2023  | Person re-identification |Wuhan University|  [Towards Modality-Agnostic Person Re-identification with Descriptive Query](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_Towards_Modality-Agnostic_Person_Re-Identification_With_Descriptive_Query_CVPR_2023_paper.pdf)   |CVPR   |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification |Shenzhen International Graduate School|  [CLIP-based Synergistic Knowledge Transfer for Text-based Person Retrieval](https://arxiv.org/pdf/2310.11210.pdf)   |	arXiv  |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification |South China University of Technology|  [Unified Pre-training with Pseudo Texts for Text-To-Image Person Re-identification](https://arxiv.org/pdf/2310.11210.pdf)   |	 ICCV |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification |Sichuan University|  [BDNet: A BERT-based dual-path network for text-to-image cross-modal person re-identification](https://www.sciencedirect.com/science/article/pii/S0031320323003370)   |	 Pattern Recognition |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification |Kunming University of Science and Technology|  [Progressive Feature Mining and Externa Knowledge-Assisted Text-Pedestrian Image Retrieval](https://arxiv.org/pdf/2308.11994.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Sichuan University|  [Noisy-Correspondence Learning for Text-to-Image Person Re-identification](https://arxiv.org/pdf/2308.09911.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Xi’an Jiaotong University|  [Towards Unified Text-based Person Retrieval: A Large-scale Multi-Attribute and Language Search Benchmark](https://arxiv.org/pdf/2308.09911.pdf)   |	 ACMM |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Nanjing Tech University Nanjing|  [TVPR:Text-to-Video Person Retrieval and a New Benchmark](https://arxiv.org/pdf/2307.07184.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | -|  [Flare-Aware Cross-modal Enhancement Network for Multi-spectral Vehicle Re-identification](https://arxiv.org/pdf/2307.07184.pdf)   |	 arXiv  |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification |  Nanjing University of Science and Technology|  [Image-Specific Information Suppression and Implicit Local Alignment for Text-based Person Search](https://arxiv.org/pdf/2208.14365.pdf)   |	 IEEE T NEUR NET LEAR |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Fudan University|  [Calibrating Cross-modal Features for Text-Based Person Searching](https://arxiv.org/pdf/2304.02278.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Fudan University|  [UNIMO-3: Multi-granularity Interaction for Vision-Language Representation Learning](https://arxiv.org/pdf/2304.02278.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Zhejiang University|  [Transformer-Based Domain-Specific Representation for Unsupervised Domain Adaptive Vehicle Re-Identification](https://ieeexplore.ieee.org/abstract/document/9967437/authors#authors)   |	 IEEE T NEUR NET LEAR |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification |-|  [IIITD-20K: Dense captioning for Text-Image ReID](https://arxiv.org/pdf/2305.04497.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | University of Liverpool|  [FindVehicle and VehicleFinder: A NER dataset for natural language-based vehicle retrieval and a keyword-based cross-modal vehicle retrieval system](https://arxiv.org/pdf/2304.10893.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Shenzhen University|  [Mask-Aware Pseudo Label Denoising for Unsupervised Vehicle Re-Identification](https://ieeexplore.ieee.org/abstract/document/10007428)   |	 IEEE T INTELL TRANSP |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | -|  [Exploiting the Textual Potential from Vision-Language Pre-training for Text-based Person Search](https://arxiv.org/pdf/2303.04497.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Zhejiang University|  [Transformer-Based Domain-Specific Representation for Unsupervised Domain Adaptive Vehicle Re-Identification](https://ieeexplore.ieee.org/abstract/document/9967437)   |	 IEEE T INTELL TRANSP |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Chung-Ang University|  [Person Re-identification Method Using Text Description Through CLIP](https://ieeexplore.ieee.org/abstract/document/10049924)   |	 ICEIC |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Tianjin University|  [USER: Unified Semantic Enhancement with Momentum Contrast for Image-Text Retrieva](https://arxiv.org/pdf/2301.06844.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | University of Chinese Academy of Sciences|  [Refined Knowledge Transfer for Language-Based Person Search](https://ieeexplore.ieee.org/abstract/document/10056995/authors#authors)   |	 IEEE T MULTIMEDIA|https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification |  Sichuan University|  [An Image–Text Dual-Channel Union Network for Person Re-Identification](https://research.edgehill.ac.uk/ws/portalfiles/portal/68212565/TIM.pdf)   |	 IEEE T INSTRUM MEAS |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Northwestern Polytechnical University|  [Improving Inconspicuous Attributes Modeling for Person Search by Language](https://ieeexplore.ieee.org/abstract/document/10149813/authors#authors)   |	 IEEE T IMAGE PROCESS |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Northwestern Polytechnical University|  [Addressing Information Inequality for Text-Based Person Search via Pedestrian-Centric Visual Denoising and Bias-Aware Alignments](https://ieeexplore.ieee.org/abstract/document/10121152)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Kunming University of Science and Technologyy|  [Person Text-Image Matching via Text-Feature Interpretability Embedding and External Attack Node Implantation](https://arxiv.org/pdf/2211.08657.pdf)   |	 arXiv |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Nanjing University|  [CLIP-Driven Fine-grained Text-Image Person Re-identification](https://arxiv.org/pdf/2210.10276.pdf)   |	 IEEE T IMAGE PROCESS |https://github.com/ccq195/UNIReID|
| 2023  | Person re-identification | Nanjing Tech University|  [Capturing All-round Information Beyond Color for Text-based Person Retrieval](https://arxiv.org/pdf/2211.08657.pdf)   |	 CAIBC |https://github.com/ccq195/UNIReID|
| 2022  | Person re-identification | Anhui University|  [See Finer, See More: Implicit Modality Alignment for Text-based Person Retrieval](https://arxiv.org/pdf/2208.08608.pdf)   |	 ECCV |https://github.com/ccq195/UNIReID|
| 2022  | Person re-identification |DEVCOM Army Research Laboratory, Adelphi, USA|  [Negative Samples are at Large: Leveraging Hard-Distance Elastic Loss for Re-identification](https://link.springer.com/chapter/10.1007/978-3-031-20053-3_35)   |	 ECCV |https://github.com/ccq195/UNIReID|
| 2022  | Person re-identification | South China University of Technology Guangzhou|[Learning Granularity-Unified Representations for Text-to-Image Person Re-identification](https://arxiv.org/pdf/2207.07802.pdf)   |	 ECCV |https://github.com/ccq195/UNIReID|
| 2022  | Person re-identification | University of Surrey|  [AXM-Net: Implicit Cross-Modal Feature Alignment for Person Re-identification](https://ojs.aaai.org/index.php/AAAI/article/view/20370)   |	  AAAI |https://github.com/ccq195/UNIReID|


| 手机    |   \$12   |   12   |
| 管线    |    \$1    |  234  |
<span id="Visible_Infrared_Reidentification"></span>
### Visible-Infrared Reidentification

<span id="Masked_Vision_and_Language_Model"></span>
## Masked Vision and Language Model

<span id="Pre_training"></span>
## Pre-training
| Date   | keywords   | Institute   | Paper | Publication|  code  |
| :-------:| :-----:  | :----:  |:----:  |:----:  |:----:  |
| 2022  | Vision-and-Language Pre-Training  |The Chinese University of Hong Kong  |  [Multi-Modal Masked Autoencoders for Medical Vision-and-Language Pre-Training](https://arxiv.org/pdf/2209.07098.pdf)   |MICCAI   |  https://github.com/zhjohnchan/M3AE|
| 手机    |   \$12   |   12   |
| 管线    |    \$1    |  234  |
<span id="Prompting_Learning"></span>
## Prompting Learning
| Date   | keywords   | Institute   | Paper | Publication|  code  |
| :-------:| :-----:  | :----:  |:----:  |:----:  |:----:  |
| 2023  | Attributes Prompt  |Harbin Institute of Technology  |  [FashionSAP: Symbols and Attributes Prompt for Fine-grained Fashion Vision-Language Pre-training](https://openaccess.thecvf.com/content/CVPR2023/papers/Han_FashionSAP_Symbols_and_Attributes_Prompt_for_Fine-Grained_Fashion_Vision-Language_Pre-Training_CVPR_2023_paper.pdf)   |CVPR   | https://github.com/hssip/FashionSAP|
| 2022  | Prompt  |Tsinghua University  |  [DenseCLIP: Language-Guided Dense Prediction with Context-Aware Prompting](https://openaccess.thecvf.com/content/CVPR2022/papers/Rao_DenseCLIP_Language-Guided_Dense_Prediction_With_Context-Aware_Prompting_CVPR_2022_paper.pdf)   |CVPR   | https://github.com/raoyongming/DenseCLIP|
| 2023  | Prompt  |  |  [Dual Modality Prompt Tuning for Vision-Language Pre-Trained Model](https://ieeexplore.ieee.org/abstract/document/10171397)   |IEEE Transactions on Multimedia   |  https://github.com/fanrena/DPT|
| 手机    |   \$12   |   12   |
| 管线    |    \$1    |  234  |
<span id="Multimodal_Large_Language_Models"></span>
## Multimodal Large Language Models
| Date   | keywords   | Institute   | Paper | Publication|  code  |
| :-------:| :-----:  | :----:  |:----:  |:----:  |:----:  |
| 2022  | masked image reconstruction |Alibaba |  [Masked Vision-Language Transformer in Fashion](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_Cross-Modal_Implicit_Relation_Reasoning_and_Aligning_for_Text-to-Image_Person_Retrieval_CVPR_2023_paper.pdf)   |Machine Intelligence Research   | https://github.com/GewelsJI/MVLT |
| 2023  | CLIP | Microsoft&Tsinghua|  [Attentive Mask CLIP](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_Attentive_Mask_CLIP_ICCV_2023_paper.pdf)   |ICCV   | https://github.com/microsoft/A-CLIP |
| 手机    |   \$12   |   12   |
| 管线    |    \$1    |  234  |
<span id="Cross_modal_Retrieval"></span>
## Cross-modal Retrieval
| Date   | keywords   | Institute   | Paper | Publication|  code  |
| :-------:| :-----:  | :----:  |:----:  |:----:  |:----:  |
| 2022  | masked image reconstruction |Alibaba |  [Masked Vision-Language Transformer in Fashion](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_Cross-Modal_Implicit_Relation_Reasoning_and_Aligning_for_Text-to-Image_Person_Retrieval_CVPR_2023_paper.pdf)   |Machine Intelligence Research   | https://github.com/GewelsJI/MVLT |
| 2023  | Composed Image Retrieval | Chinese Academy of Sciences |  [Context-I2W: Mapping Images to Context-dependent Words for Accurate Zero-Shot Composed Image Retrieval](https://arxiv.org/pdf/2309.16137.pdf)   |arXiv | https://github.com/Pter61/context i2w |
| 手机    |   \$12   |   12   |
| 管线    |    \$1    |  234  |
<span id="Fine_Tuning"></span>
## Fine Tuning
| Date   | keywords   | Institute   | Paper | Publication|  code  |
| :-------:| :-----:  | :----:  |:----:  |:----:  |:----:  |
| 2023  | Fine Tuning |Tsinghua University |  [CogVLM: Visual Expert for Pretrained Language Models](https://arxiv.org/pdf/2311.03079.pdf)   |arXiv   | [https://github.com/GewelsJI/MVLT](https://github.com/THUDM/CogVLM) |
| 手机    |   \$12   |   12   |
| 管线    |    \$1    |  234  |
