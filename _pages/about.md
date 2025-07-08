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

**Ruiyun Yu (于瑞云)**'s academic page. Thanks for the template provided by [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io)!

# 🧍‍♂️ Biography

I am a professor at the the [Software College](http://sc.neu.edu.cn/), [Northeastern University](https://www.neu.edu.cn/) (Shenyang, China), and the director of the [Office of Information Construction and Network Security](http://xwb.neu.edu.cn/).

My main research directions are **Industrial Vision**, **Temporal Perception Data Analysis**, and **3D Spatial Intelligence**. I actively promote technological innovation in the fields of **Industrial Internet** and **Artificial Intelligence** in scientific research, and carry out research on intelligent software, algorithms and application systems in the fields of integrated circuits, precision manufacturing and other choke fields.

If you have any questions or wish to cooperate with us, please feel free to contact me. Email: yury@mail.neu.edu.cn

# 🔥 News
- *2025.07*: &nbsp;🎉🎉 Our paper addressed [3D scene reconstruction](https://www.sciencedirect.com/science/article/pii/S2352864825001051) is accepted by Digital Communications and Networks!
- *2025.06*: &nbsp;🎉🎉 Our paper addressed Integrated circuits package substrate anomaly detection is accepted by ICCV 2025! The new dataset CPS2D-AD proposed in the paper is currently the largest integrated circuit defect detection dataset in the world!
- *2025.05*: &nbsp;🎉🎉 Our paper addressed [Temporal Perception Data Analysis](https://www.sciencedirect.com/science/article/abs/pii/S0166361525000788) is accepted by Computer in Industry!
- *2025.03*: &nbsp;🎉🎉 Our paper addressed [Few-shot metal surface segmenation](https://ieeexplore.ieee.org/abstract/document/10898041) is accepted by IEEE TIM!
- *2025.02*: &nbsp;🎉🎉 Our paper addressed [Temporal Perception Data Analysis](https://www.sciencedirect.com/science/article/pii/S0925231224019088) is accepted by Neurocomputing!
- *2024.10*: &nbsp;🎉🎉 Our paper addressed [Recommendation System](https://www.sciencedirect.com/science/article/pii/S0950705124009195) is accepted by KBS!
- *2024.09*: &nbsp;🎉🎉 We acquire the funding from the key research and development projects of Liaoning Province (**Research and Application of Key Technologies for Multi-modal Industrial Product Surface Defect Detection Large Model**)!
- *2024.04*: &nbsp;🎉🎉 Our paper addressed [Transferable recommendation]([https://ieeexplore.ieee.org/abstract/document/10018467/](https://ieeexplore.ieee.org/abstract/document/10491370/)) is accepted by IEEE TKDE (CCF A)!
- *2024.03*: &nbsp;🎉🎉 Our paper addressed [Weakly-supervised metal surface segmenation](https://ieeexplore.ieee.org/abstract/document/10483094/) is accepted by IEEE TIM!
- *2023.12*: &nbsp;🎉🎉 Our large vision model for industrial surface defect detection **Qing Que** obtained Huawei Ascend Technology Certification!
- *2023.05*: &nbsp;🎉🎉 We acquire the funding from the Fundamental Research Funds for the Central Universities.
- *2023.01*: &nbsp;🎉🎉 Our paper addressed [Real-time metal surface segmenation](https://ieeexplore.ieee.org/abstract/document/10018467/) is accepted by IEEE TII!
- *2022.08*: &nbsp;🎉🎉 Our paper addressed [Few-shot metal surface segmenation](https://ieeexplore.ieee.org/abstract/document/9855496/) is accepted by IEEE TIM!

# 📖 Educations
- *2005.03 - 2009.01*, Northeastern University, College of Information Science & Engineering, ***M.S.*** in Computer Application Technology
- *2001.09 - 2004.03*, Northeastern University, College of Information Science & Engineering, ***M.S.*** in Computer Application Technology
- *1993.08 - 1997.07*, Northeastern University, School of Mechanical Engineering & Automation, ***B.S.*** in Fluid Power Transmission & Control

# 📝 Publications

<span style="color:#b02418; font-weight:bold;">#</span> co-first author

<span style="color:#b02418; font-weight:bold;">*</span> corresponding author <br>

<h2 id="Industrial Vision" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Journal Publications</h2>
<ol reversed>
  <li id="J-Pub5">
    Anomaly Detection of Integrated Circuits Package Substrates Using the Large Vision Model SAIC: Dataset Construction, Methodology, and Application <a href="https://neunews.neu.edu.cn/info/1341/951471.htm#:~:text=%E8%AF%A5%E8%AE%BA%E6%96%87%E9%9D%A2%E5%90%91%E9%9B%86%E6%88%90%E7%94%B5%E8%B7%AF%E9%99%B6%E7%93%B7%E5%B0%81%E8%A3%85%E5%9F%BA%E6%9D%BF%E8%A1%A8%E9%9D%A2%E7%BC%BA%E9%99%B7%E6%A3%80%E6%B5%8B%E9%A2%86%E5%9F%9F%EF%BC%8C%E6%9E%84%E5%BB%BA%E4%BA%86%E5%A4%A7%E8%A7%84%E6%A8%A1%E4%BA%8C%E7%BB%B4%E5%BC%82%E5%B8%B8%E6%A3%80%E6%B5%8B%E6%95%B0%E6%8D%AE%E9%9B%86CPS2D-AD%EF%BC%8C%E5%83%8F%E7%B4%A0%E5%88%86%E8%BE%A8%E7%8E%87%E9%AB%98%E8%BE%BE5um%EF%BC%8C%E6%A0%B7%E6%9C%AC%E5%AE%B9%E9%87%8F%E8%B6%8520000%E5%BC%A0%EF%BC%8C%E4%B8%BA%E7%9B%AE%E5%89%8D%E9%9B%86%E6%88%90%E7%94%B5%E8%B7%AF%E9%A2%86%E5%9F%9F%E5%86%85%E5%85%A8%E4%B8%96%E7%95%8C%E8%A7%84%E6%A8%A1%E6%9C%80%E5%A4%A7%E3%80%81%E7%B2%BE%E5%BA%A6%E6%9C%80%E9%AB%98%E7%9A%84%E6%95%B0%E6%8D%AE%E9%9B%86%E3%80%82,%E5%90%8C%E6%97%B6%EF%BC%8C%E8%AF%A5%E8%AE%BA%E6%96%87%E9%92%88%E5%AF%B9CPS2D-AD%E6%95%B0%E6%8D%AE%E9%9B%86%E6%9E%84%E5%BB%BA%E4%BA%86%E6%97%A0%E7%9B%91%E7%9D%A3%E3%80%81%E5%8D%8A%E7%9B%91%E7%9D%A3%E3%80%81%E5%B0%8F%E6%A0%B7%E6%9C%AC%E3%80%81%E5%85%A8%E7%9B%91%E7%9D%A3%E7%AD%89%E5%A4%9A%E4%B8%AA%E4%BB%BB%E5%8A%A1%E7%9A%84Benchmark%EF%BC%8C%E4%B8%BA%E7%9B%B8%E5%85%B3%E9%A2%86%E5%9F%9F%E7%9A%84%E7%A0%94%E7%A9%B6%E4%BA%BA%E5%91%98%E6%8F%90%E4%BE%9B%E4%BA%86%E5%A4%AF%E5%AE%9E%E7%9A%84%E6%95%B0%E6%8D%AE%E5%9F%BA%E7%A1%80%E3%80%82">[Paper]</a> <br>
    <span style="color:#b02418; font-weight:bold;">Ruiyun Yu</span>, Bingyang Guo*，Haoyuan Li <br>
    <i>IEEE Transactions on Instrumentation and Measurement<strong>(TIM).</strong></i>
  </li>
  <li id="J-Pub4">
    Background-weaken Generalization Network for Few-Shot Industrial Metal Defect Segmentation <a href="https://ieeexplore.ieee.org/abstract/document/10898041">[Paper]</a> <br>
    <span style="color:#b02418; font-weight:bold;">Ruiyun Yu</span>, Haoyuan Li*, Bingyang Guo, Ziming Zhao <br>
    <i>IEEE Transactions on Instrumentation and Measurement<strong>(TIM).</strong></i>
  </li>
  <li id="J-Pub3">
    Dynamic Reasoning Network for Image-level Supervised Segmentation on Metal Surface Defect <a href="https://ieeexplore.ieee.org/abstract/document/10483094/">[Paper]</a> <br>
    <span style="color:#b02418; font-weight:bold;">Ruiyun Yu</span>, Bingyang Guo*, Kang Yang <br>
    <i>IEEE Transactions on Instrumentation and Measurement <strong>(TIM).</strong></i> 2024.
  </li>
  <li id="J-Pub2">
    SPEED: Semantic prior and extremely efficient dilated convolution network for real-time metal surface defects detection <a href="https://ieeexplore.ieee.org/abstract/document/10018467/">[Paper]</a> <br>
    Bingyang Guo, <span style="color:#b02418; font-weight:bold;">Ruiyun Yu*</span>, Kang Yang <br>
    <i>IEEE Transactions on Industrial Informatics<strong>(TII).</strong></i> 2023.
  </li>
  <li id="J-Pub1">
    Selective prototype network for few-shot metal surface defect segmentation <a href="https://ieeexplore.ieee.org/abstract/document/9855496/">[Paper]</a> <br>
    <span style="color:#b02418; font-weight:bold;">Ruiyun Yu</span>, Bingyang Guo*, Kang Yang <br>
    <i>IEEE Transactions on Instrumentation and Measurement <strong>(TIM).</strong></i> 2022.
  </li>
</ol>

<h2 id="Temporal Perception Data Analysis" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Conference Publications</h2>
<ol reversed>
  <li id="J-Pub4">
    A multiscale process-aware retention network for fault prediction in mixed-model production <a href="https://www.sciencedirect.com/science/article/abs/pii/S0166361525000788">[Paper]</a> <br>
    Mingda Chen, <span style="color:#b02418; font-weight:bold;">Ruiyun Yu*</span>, Zhiyuan Liang, Kun Li, Haifei Qi<br>
    <i>Computer in Industry<strong>(CI).</strong></i> 2025.
  </li>
    <li id="J-Pub3">
    A triple-phase boost transformer for industrial equipment fault prediction <a href="https://www.sciencedirect.com/science/article/pii/S0925231224019088">[Paper]</a> <br>
    <span style="color:#b02418; font-weight:bold;">Ruiyun Yu*</span>, Mingda Chen, Bing Liu <br>
    <i>Neurocomputing<strong>(NEUROCOMPUTING).</strong></i> 2024.
  </li>
  <li id="J-Pub2">
    Is multi-level data enhancement helpful for knowledge graph? A new perspective on multimodal fusion <a href="https://www.sciencedirect.com/science/article/pii/S0950705124009195">[Paper]</a> <br>
    Kang Yang, <span style="color:#b02418; font-weight:bold;">Ruiyun Yu*</span>, Bingyang Guo <br>
    <i>Knowledge-Based Systems<strong>(KBS).</strong></i> 2024.
  </li>
  <li id="J-Pub1">
    Interaction Subgraph Sequential Topology-Aware Network for Transferable Recommendation <a href="https://ieeexplore.ieee.org/abstract/document/10491370/">[Paper]</a> <br>
    Kang Yang, <span style="color:#b02418; font-weight:bold;">Ruiyun Yu*</span>, Bingyang Guo, Jie Li <br>
    <i>IEEE Transactions on Knowledge and Data Engineering<strong>(TKDE).</strong></i> 2024.
  </li>
</ol>


<h2 id="3D Spatial Intelligence" style="color: #2c4a88; padding-top: 60px; margin-top: -60px;">Conference Publications</h2>
<ol reversed>
  </li>
  <li id="J-Pub1">
    DWT-3DRec: DeepJSCC-based wireless transmission for efficient 3D scene reconstruction using CityNeRF <a href="https://www.sciencedirect.com/science/article/pii/S2352864825001051">[Paper]</a> <br>
    Shaung Cao, Jie Li, <span style="color:#b02418; font-weight:bold;">Ruiyun Yu*</span>, Xingwei Wang, Jianing Duan <br>
    <i>Digital Communications and Networks <strong>(DCN).</strong></i> 2025.
  </li>
</ol>

# 🎓 Academic Service
- *Journal Reviewer*, IEEE TIP, IEEE TNNLS, IEEE TII, IEEE TIM, etc.
- *Conference Reviewer*, CVPR, ACM MM, NeurIPS, etc.
