---
permalink: /
title: ""
excerpt: "About me"
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

I joined the <img src="/files/fzu.png" alt="NUS" width="20" height="20"> [Fuzhou University, College of Computer and Data Science](https://ccds.fzu.edu.cn/info/1204/11289.htm), as an Associate Professor in 2025. I received my Ph.D. degree from <img src="/files/fdu.png" alt="NUS" width="20" height="20"> [Fudan University, College of Computer Science and Artificial Intelligence](https://cs.fudan.edu.cn/main.htm) in June 2025, under the supervision of [Prof. Bo Yan](https://dml.fudan.edu.cn/87/22/c35294a427810/page.htm). Prior to that, I obtained my Bachelor's degree in <img src="/files/xmu.png" alt="NUS" width="20" height="20"> [School of Informatics Xiamen University](https://informatics.xmu.edu.cn/) in 2020. 

My primary research interests include low-level vision, multimodal learning, semantic segmentation, and AI for Science. <span style="color:red"> I'm looking for master and undergraduate students with strong self-drive and a deep passion for research.</span>

# 📜 Research Area
1. Low-level Vision, Real-world Super Resolution, Video-Frame Interpolation
2. AIGC, Multimodal, Multi-agent
3. Segmentation, Semi-supervised Learning, AI for Science


# 📝 Publications
<style type="text/css">
    /* Color scheme stolen from Sergey Karayev */
    a {
    color: #1772d0;
    text-decoration:none !important;
    }
    a:focus, a:hover {
    color: #f09228;
    text-decoration:none !important;
    }
    table,td,th,tr{
    	border:none !important;
    }
    body,td,th,tr,p,a {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px
    }
    strong {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    }
    heading {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 22px;
    }
    papertitle {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700
    }
    papertitle_just {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 14px;
    font-weight: 700;
    text-align: justify
    }
    name {
    font-family: 'Lato', Verdana, Helvetica, sans-serif;
    font-size: 32px;
    }
    .one
    {
    width: 160px;
    height: 160px;
    position: relative;
    }
    .two
    {
    width: 160px;
    height: 160px;
    position: absolute;
    transition: opacity .2s ease-in-out;
    -moz-transition: opacity .2s ease-in-out;
    -webkit-transition: opacity .2s ease-in-out;
    }
    .fade {
     transition: opacity .2s ease-in-out;
     -moz-transition: opacity .2s ease-in-out;
     -webkit-transition: opacity .2s ease-in-out;
    }
    span.highlight {
        background-color: #ffffd0;
    }
</style>
<!-- ################################  CONTENT START  ##################################################-->
<table width="100%" align="center" border="0" cellspacing="0" cellpadding="10">
<tbody>
<!-- ############################ Put your publications below this! ####################################-->

<!-- ###################################################################################################-->
<!-- Paper 10 EndmemberNet -->
<tr onmouseout="NP26_EndmemberNet_stop()" onmouseover="NP26_EndmemberNet_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'NP26_EndmemberNet_image'>
<img src="./files/NP26_EndmemberNet_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/NP26_EndmemberNet_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function NP26_EndmemberNet_start() {
document.getElementById('NP26_EndmemberNet_image').style.opacity = "1";
}
function NP26_EndmemberNet_stop() {
document.getElementById('NP26_EndmemberNet_image').style.opacity = "0";
}
NP26_EndmemberNet_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://www.nature.com/articles/s41566-025-01736-8">
    <papertitle_just>Excitation-encoded single-emission shortwave infrared lanthanide fluorophore palette for real-time in vivo multispectral imaging</papertitle_just>     
  </a>
  <br>
  Lu Zhang*, <strong>Ri Cheng*</strong>, Zuyang He, Mei Mei, Bin Wu, Weimin Tan†, Bo Yan†, Shangfeng Wang†, Fan Zhang†
  <br>
<em>Nature Photonics</em>, 2025 <br>
<a href="https://www.nature.com/articles/s41566-025-01736-8">Paper</a>
|
<a href="https://github.com/Orange066/EndmemberNet">Github</a>
| 
<a href="./files/NP26_EndmemberNet_bibtex_bibtex.txt">BibTeX</a>
|
<a href="https://news.fudan.edu.cn/2025/0826/c1247a146475/page.htm">link</a>  
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->



<!-- ###################################################################################################-->
<!-- Paper 9 mdsr -->
<tr onmouseout="aaai25_mdsr_stop()" onmouseover="aaai25_mdsr_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'aaai25_mdsr_image'>
<img src="./files/aaai25_mdsr_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/aaai25_mdsr_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function aaai25_mdsr_start() {
document.getElementById('aaai25_mdsr_image').style.opacity = "1";
}
function aaai25_mdsr_stop() {
document.getElementById('aaai25_mdsr_image').style.opacity = "0";
}
aaai25_mdsr_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32354">
    <papertitle_just>Efficient Online Training for Zero-Shot Time-Lapse Microscopy Denoising and Super-Resolution</papertitle_just>     
  </a>
  <br>
  Ruian He, <strong>Ri Cheng</strong>, Xinkai Lyu, Weimin Tan†, Bo Yan†
  <br>
<em>AAAI</em>, 2025 <br>
<a href="https://ojs.aaai.org/index.php/AAAI/article/view/32354">Paper</a>
| 
<a href="./files/aaai25_mdsr_bibtex.txt">BibTeX</a>
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- Paper 8 dynamic -->
<tr onmouseout="aaai24_dynamic_stop()" onmouseover="aaai24_dynamic_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'aaai24_dynamic_image'>
<img src="./files/aaai24_dynamic_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/aaai24_dynamic_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function aaai24_dynamic_start() {
document.getElementById('aaai24_dynamic_image').style.opacity = "1";
}
function aaai24_dynamic_stop() {
document.getElementById('aaai24_dynamic_image').style.opacity = "0";
}
aaai24_dynamic_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://arxiv.org/abs/2312.07180">
    <papertitle_just>Context-Aware Iteration Policy Network for Efficient Optical Flow Estimation</papertitle_just>     
  </a>
  <br>
  <strong>Ri Cheng</strong>, Ruian He, Xuhao Jiang, Shili Zhou, Weimin Tan†, Bo Yan†
  <br>
<em>AAAI</em>, 2024 <br>
<a href="https://arxiv.org/abs/2312.07180">arXiv</a>
|
<a href="https://github.com/Orange066/DFlow">Github</a>
| 
<a href="./files/aaai24_dynamic_bibtex.txt">BibTeX</a>
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- Paper 7 MGQFormer -->
<tr onmouseout="aaai2024_MGQFormer_stop()" onmouseover="aaai2024_MGQFormer_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'aaai2024_MGQFormer_image'>
<img src="./files/aaai2024_MGQFormer_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/aaai2024_MGQFormer_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function aaai2024_MGQFormer_start() {
document.getElementById('aaai2024_MGQFormer_image').style.opacity = "1";
}
function aaai2024_MGQFormer_stop() {
document.getElementById('aaai2024_MGQFormer_image').style.opacity = "0";
}
aaai2024_MGQFormer_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/28520">
    <papertitle_just>MGQFormer: Mask-Guided Query-Based Transformer for Image Manipulation Localization</papertitle_just>     
  </a>
  <br>
  Kunlun Zeng*, <strong>Ri Cheng*</strong>, Weimin Tan†, Bo Yan†
  <br>
<em>AAAI</em>, 2024 <br>
<a href="https://ojs.aaai.org/index.php/AAAI/article/view/28520">Paper</a>
| 
<a href="./files/aaai2024_MGQFormer_bibtex.txt">BibTeX</a>
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->

<!-- ###################################################################################################-->
<!-- Paper 6 STSSNet -->
<tr onmouseout="aaai2024_STSSNet_stop()" onmouseover="aaai2024_STSSNet_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'aaai2024_STSSNet_image'>
<img src="./files/aaai2024_STSSNet_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/aaai2024_STSSNet_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function aaai2024_STSSNet_start() {
document.getElementById('aaai2024_STSSNet_image').style.opacity = "1";
}
function aaai2024_STSSNet_stop() {
document.getElementById('aaai2024_STSSNet_image').style.opacity = "0";
}
aaai2024_STSSNet_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://arxiv.org/abs/2312.10890">
    <papertitle_just>Low-Latency Space-Time Supersampling for Real-Time Rendering</papertitle_just>     
  </a>
  <br>
  Ruian He, Shili Zhou, Yuqi Sun, <strong>Ri Cheng</strong>, Weimin Tan, Bo Yan†
  <br>
<em>AAAI</em>, 2024 <br>
<a href="https://arxiv.org/abs/2312.10890">arXiv</a>
|
<a href="./files/aaai2024_STSSNet_bibtex.txt">BibTeX</a>
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->

<!-- ###################################################################################################-->
<!-- Paper 5 UGSP -->
<tr onmouseout="mm23_UGSP_stop()" onmouseover="mm23_UGSP_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'mm23_UGSP_image'>
<img src="./files/mm23_UGSP_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/mm23_UGSP_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function mm23_UGSP_start() {
document.getElementById('mm23_UGSP_image').style.opacity = "1";
}
function mm23_UGSP_stop() {
document.getElementById('mm23_UGSP_image').style.opacity = "0";
}
mm23_UGSP_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://arxiv.org/abs/2307.16555">
    <papertitle_just>Uncertainty-Guided Spatial Pruning Architecture for Efficient Frame Interpolation.</papertitle_just>     
  </a>
  <br>
  <strong>Ri Cheng</strong>, Xuhao Jiang, Ruian He, Shili Zhou, Weimin Tan, Bo Yan†
  <br>
<em>ACM Multimedia (ACM'MM)</em>, 2023 <br>
<a href="https://arxiv.org/abs/2307.16555">arXiv</a>
|
<a href="https://github.com/Orange066/UGSP_Models">Github</a>
| 
<a href="./files/mm23_UGSP_bibtex.txt">BibTeX</a>
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- Paper 4 PosterCraft -->
<tr onmouseout="cvprw23_mm_stop()" onmouseover="cvprw23_mm_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'cvprw23_mm_image'>
<img src="./files/cvprw23_mm_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/cvprw23_mm_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function cvprw23_mm_start() {
document.getElementById('cvprw23_mm_image').style.opacity = "1";
}
function cvprw23_mm_stop() {
document.getElementById('cvprw23_mm_image').style.opacity = "0";
}
cvprw23_mm_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://ieeexplore.ieee.org/abstract/document/10208894">
    <papertitle_just>Motion Matters: Difference-based Multi-scale Learning for Infrared UAV Detection</papertitle_just>     
  </a>
  <br>
  Ruian He, Shili Zhou, <strong>Ri Cheng</strong>, Yuqi Sun, Weimin Tan, Bo Yan†
  <br>
<em>CVPRW</em>, 2023 <br>
<a href="https://ieeexplore.ieee.org/abstract/document/10208894">Paper</a>
| 
<a href="./files/cvprw23_mm_bibtex.txt">BibTeX</a>
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- Paper 3 IBR -->
<tr onmouseout="cvpr22_IBR_stop()" onmouseover="cvpr22_IBR_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'cvpr22_IBR_image'>
<img src="./files/cvpr22_IBR_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/cvpr22_IBR_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function cvpr22_IBR_start() {
document.getElementById('cvpr22_IBR_image').style.opacity = "1";
}
function cvpr22_IBR_stop() {
document.getElementById('cvpr22_IBR_image').style.opacity = "0";
}
cvpr22_IBR_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://openaccess.thecvf.com/content/CVPR2022/html/Sun_Learning_Robust_Image-Based_Rendering_on_Sparse_Scene_Geometry_via_Depth_CVPR_2022_paper.html">
    <papertitle_just>Learning Robust Image-Based Rendering on Sparse Scene Geometry via Depth Completion</papertitle_just>     
  </a>
  <br>
  Yuqi Sun, Shili Zhou, <strong>Ri Cheng</strong>, Weimin Tan, Bo Yan†, Lang Fu
  <br>
<em>CVPR</em>, 2022 <br>
<a href="https://openaccess.thecvf.com/content/CVPR2022/html/Sun_Learning_Robust_Image-Based_Rendering_on_Sparse_Scene_Geometry_via_Depth_CVPR_2022_paper.html">Paper</a>
|
<a href="https://github.com/Jonlysun/SIBRNet">Github</a>
| 
<a href="./files/cvpr22_IBR_bibtex.txt">BibTeX</a>
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->


<!-- ###################################################################################################-->
<!-- Paper 2 PosterCraft -->
<tr onmouseout="mm21_MVSRnet_stop()" onmouseover="mm21_MVSRnet_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'mm21_MVSRnet_image'>
<img src="./files/mm21_MVSRnet_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/mm21_MVSRnet_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function mm21_MVSRnet_start() {
document.getElementById('mm21_MVSRnet_image').style.opacity = "1";
}
function mm21_MVSRnet_stop() {
document.getElementById('mm21_MVSRnet_image').style.opacity = "0";
}
mm21_MVSRnet_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://arxiv.org/abs/2207.08601">
    <papertitle_just>Geometry-Aware Reference Synthesis for Multi-View Image Super-Resolution</papertitle_just>     
  </a>
  <br>
  <strong>Ri Cheng</strong>, Yuqi Sun, Bo Yan†, Weimin Tan, Chenxi Ma
  <br>
<em>ACM Multimedia (ACM'MM)</em>, 2022 <br>
<a href="https://arxiv.org/abs/2207.08601">arXiv</a>
|
<a href="https://github.com/Orange066/MVSR">Github</a>
| 
<a href="./files/mm21_MVSRnet_bibtex.txt">BibTeX</a>
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->

<!-- ###################################################################################################-->
<!-- Paper 1 SIJAR -->
<tr onmouseout="mm22_SIJAR_stop()" onmouseover="mm22_SIJAR_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'mm22_SIJAR_image'>
<img src="./files/mm22_SIJAR_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/mm22_SIJAR_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function mm22_SIJAR_start() {
document.getElementById('mm22_SIJAR_image').style.opacity = "1";
}
function mm22_SIJAR_stop() {
document.getElementById('mm22_SIJAR_image').style.opacity = "0";
}
mm22_SIJAR_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://arxiv.org/pdf/2207.07335">
    <papertitle_just>Learning Parallax Transformer Network for Stereo Image JPEG Artifacts Removal</papertitle_just>     
  </a>
  <br>
  Xuhao Jiang, Weimin Tan, <strong>Ri Cheng</strong>, Shili Zhou, Bo Yan†
  <br>
<em>ACM Multimedia (ACM'MM)</em>, 2022 <br>
<a href="https://arxiv.org/pdf/2207.07335">arXiv</a>
|
<a href="./files/mm22_SIJAR_bibtex.txt">BibTeX</a> 
<p></p>
</td>
</tr>
<!-- ###################################################################################################-->

<!-- ###################################################################################################-->
<!-- Paper 0 SASR -->
<tr onmouseout="mm21_SASR_stop()" onmouseover="mm21_SASR_start()" >
<td width="20%">
<div class="one">
<div class="two" id = 'mm21_SASR_image'>
<img src="./files/mm21_SASR_after.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;"></div>
<img src="./files/mm21_SASR_before.png" style="width: 100%; aspect-ratio: 1 / 1; object-fit: cover;">
</div>
<script type="text/javascript">
function mm21_SASR_start() {
document.getElementById('mm21_SASR_image').style.opacity = "1";
}
function mm21_SASR_stop() {
document.getElementById('mm21_SASR_image').style.opacity = "0";
}
mm21_SASR_stop()
</script>
</td>
<td valign="top" width="80%">
  <a href="https://dl.acm.org/doi/abs/10.1145/3474085.3475244">
    <papertitle_just>Space-Angle Super-Resolution for Multi-View Imagesk</papertitle_just>     
  </a>
  <br>
  Yuqi Sun*, <strong>Ri Cheng*</strong>, Bo Yan†, Shili Zhou
  <br>
<em>ACM Multimedia (ACM'MM)</em>, 2021 <br>
<a href="https://dl.acm.org/doi/abs/10.1145/3474085.3475244">Paper</a>
|
<a href="https://github.com/Jonlysun/SASRNet">Github</a>
| 
<a href="./files/mm21_SASR_bibtex.txt">BibTeX</a>

<p></p>
</td>
</tr>
<!-- ###################################################################################################-->


    

<!-- ############################ Put your publications above this! ####################################-->
</tbody></table>

# 🏫 Educations
- 09.2020-06.2025: Ph.D. (Computer Science and Technology), <img src="/files/fdu.png" alt="FDU" width="20" height="20"> Fudan University (FDU), China 
- 09.2016-06.2020: B.Eng (Software Engineering), <img src="/files/xmu.png" alt="XMU" width="20" height="20"> Xiamen University (XMU), China


# 💻 Academic Services

- Reviewer: CVPR, ICCV, ECCV, AAAI, ACM MM, etc.
- Teaching Assistant: Linear Algebra at Fudan University.






