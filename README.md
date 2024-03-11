# Machine Learning Researcher
I am a PhD candidate at the Department of [Electrical and Computer Engineering at Purdue University](https://engineering.purdue.edu/ECE) where I am advised by [Professor Kaushik Roy](https://engineering.purdue.edu/NRL/Group). I am also affiliated as a graduate student researcher at the [Center for Brain-Inspired Computing (C-BRIC)](https://engineering.purdue.edu/C-BRIC) at Purdue. During my PhD, I spent time at the Memory Solution Team at [GlobalFoundries](https://gf.com/) as a research intern.

During my PhD, I worked on deep learning optimizer and algorithm design, specifically within the application domains of computer vision and reinforcement learning. My expertise extends to various areas, including online learning, continual learning, meta-learning, and decentralized learning algorithms. Furthermore, I gained valuable industry experience through my involvement in hardware-software co-design for ML acceleration during my internship.  I am deeply passionate about advancing the field of AI, particularly in the areas of computer vision, natural language processing, autonomous AI, and generative AI applications, with a strong emphasis on scalability and efficiency.

[Email](mailto:gsaha@purdue.edu)  |  [Resume](/assets/docs/GobindaSaha_Resume.pdf)  |  [LinkedIn](https://www.linkedin.com/in/gobinda-saha) | [Google Scholar](https://scholar.google.com/citations?user=Y7I-7EsAAAAJ&hl=en)  |  [Github](https://github.com/sahagobinda) 

<!---
#### Technical Skills: Python, PyTorch, C, C++, AWS, MATLAB

## Education
- Ph.D., Electrical and Computer Engineering | Purdue University (_October 2023_)								       		
- M.S., Electrical and Electronic Engineering	| Bangladesh University of Engineering and Technology (_Aughts 2015_)	 			        		
- B.S., Electrical and Electronic Engineering | Bangladesh University of Engineering and Technology (_February 2013_)

-->

## Work Experience
**Graduate Research Assistant @ Purdue University (_August 2017 - Present_)**
- Project 1: Efficient Continual Learning in Deep Neural Networks
- Project 2: Decentralized Learning with non-IID data and in Continual Learning setups
- Project 3: Machine Unlearning Algorithms for Removing Effect of Data Noise and Anomalies and to Preserve Privacy in Vision/Language/Multimodal Models  
- Project 4: Hardware accelerator design with Photonic in-memory-computing primitives for Spiking Neural Networks

**Research Intern, Memory Solution Team @ GlobalFoundries, USA (_June 2019 - August 2019_)**
- Project: Software framework development for hardware-algorithm co-design for deep learning applications 



## News
- **01/10/2024**: Served as a reviewer for CVPR 2024. 
- **09/27/2023**: Presented a collection of works done during my PhD at [Boston Dynamics AI Institute](https://theaiinstitute.com/), Cambridge, MA, USA. 
- **02/11/2023**: Presented our paper [Continual Learning with Scaled Gradient Projection](https://ojs.aaai.org/index.php/AAAI/article/view/26157) at [AAAI 2023]([https://wacv2023.thecvf.com/node/174](https://aaai-23.aaai.org/)), Washington, DC, USA. 
- **01/07/2023**: Our paper [Saliency Guided Experience Packing for Replay in Continual Learning](https://openaccess.thecvf.com/content/WACV2023/html/Saha_Saliency_Guided_Experience_Packing_for_Replay_in_Continual_Learning_WACV_2023_paper.html) made the [WACV 2023 Award finalist](https://wacv2023.thecvf.com/node/174) list.
- **07/27/2022**: Passed the PhD preliminary exam!
- **07/10/2022**: Our perspective on [A cross-layer approach to cognitive computing](https://dl.acm.org/doi/abs/10.1145/3489517.3530642) was presented at ACM/IEEE Design Automation Conference 2022.
- **10/5/2020**: Attended and presented a poster at [C-BRIC](https://engineering.purdue.edu/C-BRIC) annual review at Purdue. 
- **07/01/2021**: Gave a talk on Continual Learning at [C-BRIC](https://engineering.purdue.edu/C-BRIC) Industry Meeting.
- **01/12/2021**: Our paper [Gradient Projection Memory for Continual Learning](https://openreview.net/forum?id=3AOj0RCNC2) is selected for Oral presentation at [ICLR 2021](https://iclr.cc/Conferences/2021).
- **10/6/2020**: Attended and presented a poster at [C-BRIC](https://engineering.purdue.edu/C-BRIC) annual review at Purdue. 
  
## Publications 

---

### [Continual Learning with Scaled Gradient Projection](blue) 

**Gobinda Saha**, Kaushik Roy<br>
*AAAI Conference on Artificial Intelligence (**AAAI 2023**)*<br> 
[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/26157) [[Code]](https://github.com/sahagobinda/SGP) [[Talk Video]](/assets/videos/sgp_saha_aaai_presentation.mp4) 

- A scaled gradient projection algorithm for balancing stability and plasticity during continual learning.
- Attained up to 2% higher accuracy in image classification and ~12% more reward in reinforcement learning (Atari games) tasks than SOTA with minimal forgetting. 

![SGP overview](/assets/Images/sgp.png)


### [Saliency Guided Experience Packing for Replay in Continual Learning](blue)

**Gobinda Saha**, Kaushik Roy<br>
*IEEE/CVF Winter Conference on Applications of Computer Vision (**WACV 2023**)*<br>
[[Paper]](https://openaccess.thecvf.com/content/WACV2023/html/Saha_Saliency_Guided_Experience_Packing_for_Replay_in_Continual_Learning_WACV_2023_paper.html) [[Code]](https://github.com/sahagobinda/EPR) [[Talk Video]](/assets/videos/wacv_presentation.wmv)

- A new experience replay method for continual learning where explainable AI (XAI) tools such as saliency maps are used for memory selection.
- Attained up to 5% accuracy improvement over SOTA on online continual object classification benchmarks with tiny episodic memories.

![EPR overview](/assets/Images/epr3.png)


### [Gradient Projection Memory for Continual Learning](blue)

**Gobinda Saha**, Isha Garg, Kaushik Roy<br>
*International Conference on Learning Representations (**ICLR 2021**)* (**Oral - top 1% paper**)<br>
[[Paper]](https://openreview.net/forum?id=3AOj0RCNC2) [[Code]](https://github.com/sahagobinda/GPM) [[Talk Video]](https://slideslive.com/38953615/gradient-projection-memory-for-continual-learning?ref=account-84503-popular) [[Poster]](/assets/docs/GPM_poster_final.pdf)

- A novel orthogonal gradient descent algorithm for forget-free continual learning in deep neural networks. 
- Obtained near zero forgetting on continual object classification tasks.  

![GPM overview](/assets/Images/gpm.png)


### [SPACE: Structured Compression and Sharing of Representational Space for Continual Learning](blue)

**Gobinda Saha**, Isha Garg, Aayush Ankit, Kaushik Roy<br>
*IEEE Access 2021*<br> 
[[Paper]](https://ieeexplore.ieee.org/document/9605653) [[Code]](https://github.com/sahagobinda/CL_PCA) 

- A PCA-driven network pruning and growth method for forget-free continual learning. 
- Achieved zero forgetting with up to 5x energy efficiency during inference due to emerging sparsity.

![SPACE overview](/assets/Images/space.png)

---

### [CoDeC: Communication-Efficient Decentralized Continual Learning](blue)

Sakshi Choudhary, Sai Aparna Aketi, **Gobinda Saha**, Kaushik Roy<br>
*Transactions on Machine Learning Research (TMLR), 2024* 
[[Paper]](https://openreview.net/forum?id=N05OnQG1BA&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DTMLR%2FAuthors%23your-submissions)) 


- A decentralized continual learning algorithm that combines orthogonal gradient projections with gossip-averaging among distributed agents.
- Achieved SOTA accuracy on image classification tasks with up to 4.8x reduced communication ensuring  inter-agent data privacy.  

![codec overview](/assets/Images/codec.PNG)

### [Homogenizing Non-IID datasets via In-Distribution Knowledge Distillation for Decentralized Learning](blue)

Deepak Ravikumar, **Gobinda Saha**, Sai Aparna Aketi, Kaushik Roy<br>
*Preprint (arxiv), 2023* [[Paper]](https://arxiv.org/abs/2304.04326) 

- A new distillation-based approach - IDKD to handle non-IID data distribution in a decentralized setting.

---
### [Deep Unlearning: Fast and Efficient Training-free Approach to Controlled Forgetting](blue)

Sangamesh Kodge, **Gobinda Saha**, Kaushik Roy<br>
*Preprint (arxiv), 2023* [[Paper]](https://arxiv.org/abs/2312.00761) 

- A new Singular Value decomposition-based algorithm that unlearns requested classes of data from a pre-trained model without any retraining or finetuing!

![Unlearning overview](/assets/Images/unlearning.PNG)

---

### [An Energy-Efficient and High Throughput in-Memory Computing Bit-Cell With Excellent Robustness Under Process Variations for Binary Neural Network](blue)

**Gobinda Saha**, Zhewei Jiang, Sanjay Parihar, Cao Xi, Jack Higman, Muhammed Ahosan Ul Karim<br>
*IEEE Access, 2021*<br> 
[[Paper]](https://ieeexplore.ieee.org/abstract/document/9091590) 


- Proposed a 10T bit-cell based IMC primitive for accelerating binary neural network inference.
- Developed a Python-HSPICE based software framework for hardware-algorithm co-design.
- Analysized performance of in-memory computing (IMC) arrays on DL workloads under nonidealities and process variations.  

![Global overview](/assets/Images/global.png)

### [Photonic In-Memory Computing Primitive for Spiking Neural Networks Using Phase-Change Materials](blue)

Indranil Chakraborty, **Gobinda Saha**, Kaushik Roy<br>
*Physical Review Applied, 2019*<br> 
[[Paper]](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.11.014063) 


- Designed optical spiking neural network based on photonic computing primitives to realize energy-efficient and fast computing.
- Developed a device-circuit-algorithm co-design framework to evaluate their performance as SNN inference engine.  

![Optical overview](/assets/Images/optical.png)

### [Toward Fast Neural Computing using All-Photonic Phase Change Spiking Neurons](blue)

Indranil Chakraborty, **Gobinda Saha**, Abhronil Sengupta, Kaushik Roy<br>
*Scientific Reports, 2018*<br> 
[[Paper]](https://www.nature.com/articles/s41598-018-31365-x) 

- Designed spiking neuron based on GST (phase change material) embedded optical micro-ring resonators.

---
