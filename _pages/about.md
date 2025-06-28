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

# 🙋‍♂️ About Me
I am currently a first-year Ph.D. candidate in the [CVMI Lab](http://cvmi.hku.hk/) at the University of Hong Kong, under the supervision of Prof. [Xiaojuan Qi](https://xjqi.github.io/). Prior to that, I worked as a research assistant at the Shanghai Qi Zhi Institute, advised by Prof. [Li Yi](https://ericyi.github.io/). Earlier, I received my M.E. degree from the Institute of Computing Technology, Chinese Academy of Sciences in Beijing, where I was advised by Prof. [Lin Gao](http://geometrylearning.com/). I obtained my B.E. degree from Tongji University in Shanghai.

My research interests include vision-language models and physics-based motion synthesis. I am particularly interested in developing embodied agents that can reason and act in 3D environments through multimodal understanding. My long-term goal is to enable simulation-trained agents to generalize to real-world settings, by leveraging the structured representations and decision-making capabilities of vision-language models. Ultimately, I aim to bridge the gap between perceptual grounding and embodied control in complex physical environments.

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">CVPR 2025</div>
    <img src="images/phys-reach-grasp.png" alt="phys-reach-grasp">
  </div>
  <div class="paper-box-text" markdown="1">
  
  **[Learning Physics-Based Full-Body Human Reaching and Grasping from Brief Walking References](http://arxiv.org/abs/2503.07481)**   
  Yitang Li*, <strong><u>Mingxian Lin*</u></strong>, Zhuo Lin, Yipeng Deng, Yue Cao, Li Yi 
  
  *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025.*

  <a class="pub-button" href="http://arxiv.org/abs/2503.07481" target="_blank">PDF</a>
  <a class="pub-button" href="https://github.com/liyitang22/phys-reach-grasp" target="_blank">Code</a>
  <a class="pub-button" href="https://liyitang22.github.io/phys-reach-grasp/" target="_blank">Project</a>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">CVPR 2025</div>
    <img src="images/DRK.gif" alt="drk">
  </div>
  <div class="paper-box-text" markdown="1">
  
  **[Deformable Radial Kernel Splatting](https://arxiv.org/pdf/2412.11752)**   
  Yihua Huang , <strong><u>Mingxian Lin</u></strong>, Yang-Tian Sun, Ziyi Yang, Xiaoyang Lyu, Yan-Pei Cao<sup>†</sup>, Xiaojuan Qi<sup>†</sup>
  
  *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2025.*

  <a class="pub-button" href="https://arxiv.org/pdf/2412.11752" target="_blank">PDF</a>
  <a class="pub-button" href="https://github.com/yihua7/Deformable-Radial-Kernel-Splatting" target="_blank">Code</a>
  <a class="pub-button" href="https://yihua7.github.io/DRK-web/" target="_blank">Project</a>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">ECCV 2024</div>
    <img src="images/freemotion.png" alt="freemotion">
  </div>
  <div class="paper-box-text" markdown="1">
  
  **[FreeMotion: MoCap-Free Human Motion Synthesis with Multimodal Large Language Models](https://arxiv.org/abs/2406.10740)**   
  Zhikai Zhang, Yitang Li, Haofeng Huang, <strong><u>Mingxian Lin</u></strong>, Li Yi  
  
  *European Conference on Computer Vision (ECCV), 2024.*

  <a class="pub-button" href="https://arxiv.org/abs/2406.10740" target="_blank">PDF</a>
  <a class="pub-button" href="https://zzk273.github.io/freemotion.github.io/" target="_blank">Project</a>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">CVPR 2023</div>
    <img src="images/compositor.png" alt="compositor">
  </div>
  <div class="paper-box-text" markdown="1">
  
  **[Compositor: Bottom-Up Clustering and Compositing for Robust Part and Object Segmentation](https://arxiv.org/abs/2306.07404)**  
  Ju He, Jieneng Chen, <strong><u>Mingxian Lin</u></strong>, Qihang Yu, Alan Yuille
  
  *IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023.*

  <a class="pub-button" href="https://arxiv.org/abs/2306.07404" target="_blank">PDF</a>
  <a class="pub-button" href="https://github.com/TACJu/Compositor" target="_blank">Code</a>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">SIGGRAPH Asia 2021</div>
    <img src="images/tmnet.png" alt="tmnet">
  </div>
  <div class="paper-box-text" markdown="1">
  
  **[TM-NET: Deep Generative Networks for Textured Meshes](https://arxiv.org/abs/2010.06217)**  
  Lin Gao, Tong Wu, Yu-Jie Yuan, <strong><u>Mingxian Lin</u></strong>, Yu-Kun Lai, Hao Zhang
  
  *ACM Transactions on Graphics (ACM SIGGRAPH Asia 2021).*

  <a class="pub-button" href="https://arxiv.org/abs/2010.06217" target="_blank">PDF</a>
  <a class="pub-button" href="https://github.com/IGLICT/TM-NET" target="_blank">Code</a>
  <a class="pub-button" href="http://geometrylearning.com/TM-NET/" target="_blank">Project</a>
  </div>
</div>


<div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">ICCV 2021</div>
    <img src="images/ibsr.png" alt="ibsr">
  </div>
  <div class="paper-box-text" markdown="1">
  
  **[Single Image 3D Shape Retrieval via Cross-Modal Instance and Category Contrastive Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Lin_Single_Image_3D_Shape_Retrieval_via_Cross-Modal_Instance_and_Category_ICCV_2021_paper.pdf)**  
  <strong><u>Mingxian Lin</u></strong>, Jie Yang, He Wang, Yu-Kun Lai, Rongfei Jia, Binqiang Zhao, Lin Gao  
  
  *IEEE/CVF International Conference on Computer Vision (ICCV), 2021.*

  <a class="pub-button" href="https://openaccess.thecvf.com/content/ICCV2021/papers/Lin_Single_Image_3D_Shape_Retrieval_via_Cross-Modal_Instance_and_Category_ICCV_2021_paper.pdf" target="_blank">PDF</a>
  <a class="pub-button" href="https://github.com/IGLICT/IBSR_jittor" target="_blank">Code</a>
  </div>
</div>

<!-- <div class="paper-box">
  <div class="paper-box-image">
    <div class="badge">ICCV 2021</div>
    <img src="images/ibsr.png" alt="ibsr">
  </div>
  <div class="paper-box-text" markdown="1">
  
  **[Single Image 3D Shape Retrieval via Cross-Modal Instance and Category Contrastive Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Lin_Single_Image_3D_Shape_Retrieval_via_Cross-Modal_Instance_and_Category_ICCV_2021_paper.pdf)**  
  **Mingxian Lin**, Jie Yang, He Wang, Yu-Kun Lai, Rongfei Jia, Binqiang Zhao, Lin Gao  
  *International Conference on Computer Vision (ICCV), 2021.*

  <a class="pub-button" href="https://openaccess.thecvf.com/content/ICCV2021/papers/Lin_Single_Image_3D_Shape_Retrieval_via_Cross-Modal_Instance_and_Category_ICCV_2021_paper.pdf" target="_blank">PDF</a>
  <a class="pub-button" href="https://github.com/IGLICT/IBSR_jittor" target="_blank">Code</a>
  <a class="pub-button" href="https://github.com/IGLICT/IBSR_jittor" target="_blank">Project</a>
  </div>
</div> -->




<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 – Present*, The University of Hong Kong, **Ph.D. in Electrical and Electronic Engineering**, Hong Kong, China
- *2020.09 – 2023.07*, Institute of Computing Technology, Chinese Academy of Sciences, **M.E. in Electrical and Electronic**, Beijing, China
- *2015.09 – 2020.06*, Tongji University, **B.E. in Computer Science and Technology**, Shanghai, China



<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.11 - 2025.11*, Tencent, China