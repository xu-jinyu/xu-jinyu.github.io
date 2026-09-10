---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

Hi! I am **Jinyu Xu (徐进宇)**, an undergraduate student at the School of Cyber Science and Engineering, Huazhong University of Science and Technology [(HUST)](https://www.hust.edu.cn/). My research interests include **Computer Graphics** and **Computer Vision**.

I am interested in what limited visual observations can tell us about the world, from the appearance captured in images to the structure behind it. Beyond understanding the world, I am interested in how intelligence can turn perception into action, interacting with and reshaping the world.

Following this line of thought, my current research focuses on using AI for creative design and on building interactive environments for embodied agents. Previously, advised by [Prof. Hao Lu](https://scholar.google.com/citations?user=Ly2qWWgAAAAJ&hl=zh-CN), I worked on visual dense prediction, studying fine-grained visual understanding from images.


Please feel free to reach out via **[jinyu_xu@hust.edu.cn](mailto:jinyu_xu@hust.edu.cn)** for discussion or collaboration.

# 📝 Publications

<style>
/* ===== Publications ===== */

.pub-list {
  width: 100%;
  margin-top: 18px;
}

.pub-item {
  display: grid;
  grid-template-columns: 32% 1fr;
  column-gap: 28px;
  align-items: center;

  padding: 24px 0;
  border-bottom: 1px solid #e8e8e8;
}

.pub-item:last-child {
  border-bottom: none;
}

/* 左侧图片区域：统一的是画框，不是图片比例 */
.pub-thumb {
  position: relative;

  width: 100%;
  height: 165px;

  display: flex;
  align-items: center;
  justify-content: center;

  overflow: hidden;
  background: #fff;
}

/* 图片保持原始比例 */
.pub-thumb img {
  display: block;

  max-width: 100%;
  max-height: 155px;

  width: auto;
  height: auto;

  object-fit: contain;

  border-radius: 2px;
  box-shadow: 0 2px 7px rgba(0, 0, 0, 0.16);
}

/* 左上角会议标签 */
.pub-badge {
  position: absolute;
  top: 5px;
  left: 0;

  z-index: 2;

  padding: 3px 12px;

  background: #224a91;
  color: #fff;

  font-size: 12px;
  font-weight: 500;
  line-height: 1.3;
}

/* 右侧文字 */
.pub-info {
  min-width: 0;
}

.pub-title {
  margin-bottom: 8px;

  font-size: 16px;
  font-weight: 700;
  line-height: 1.38;
}

.pub-title a {
  color: #214f91;
  text-decoration: none;
}

.pub-title a:hover {
  text-decoration: underline;
}

.pub-authors {
  margin-bottom: 9px;

  color: #555;
  font-size: 14px;
  line-height: 1.5;
}

.pub-authors strong {
  color: #333;
}

/* Venue 标签 */
.pub-venue {
  display: inline-block;

  margin-bottom: 11px;
  padding: 3px 8px;

  background: #fff7c7;
  border-radius: 6px;

  color: #333;
  font-size: 14px;
  font-weight: 700;
  line-height: 1.4;
}

.pub-highlight {
  color: #c0392b;
}

/* Paper / Code 等 */
.pub-links {
  font-size: 14px;
  font-weight: 600;
}

.pub-links a {
  margin-right: 22px;

  color: #214f91;
  text-decoration: underline;
  text-underline-offset: 2px;
}

/* 手机端 */
@media (max-width: 768px) {
  .pub-item {
    grid-template-columns: 1fr;
    row-gap: 16px;
    padding: 22px 0;
  }

  .pub-thumb {
    height: 180px;
  }

  .pub-thumb img {
    max-height: 170px;
  }

  .pub-links a {
    margin-right: 14px;
  }
}
</style>


<div class="pub-list">


  <!-- CVPR 2026 -->
  <div class="pub-item">

    <div class="pub-thumb">
      <div class="pub-badge">CVPR 2026 Oral</div>
      <img src="images/cvpr2026.png" alt="CVPR 2026">
    </div>

    <div class="pub-info">

      <div class="pub-title">
        <a href="https://arxiv.org/abs/2603.21229">
          Plant Taxonomy Meets Plant Counting: A Fine-Grained, Taxonomic Dataset for Counting Hundreds of Plant Species
        </a>
      </div>

      <div class="pub-authors">
        <strong>Jinyu Xu</strong>, Tianqi Hu, Xiaonan Hu, Letian Zhou,
        Songliang Cao, Meng Zhang, Hao Lu
      </div>

      <div class="pub-venue">
        CVPR 2026 Oral
        <span class="pub-highlight">(Best Paper Award Candidate)</span>
      </div>

      <div class="pub-links">
        <a href="https://arxiv.org/abs/2603.21229">Paper</a>
        <a href="https://github.com/tiny-smart/TPC-268">Code</a>
        <a href="https://huggingface.co/datasets/jinyu-xu/TPC-268">Dataset</a>
        <a href="https://tiny-smart.github.io/tpc268-project-page">Project Page</a>
        <a href="https://mp.weixin.qq.com/s/ivYhZqBY__eXKRvwMb-zcQ">Social Media</a>
      </div>

    </div>

  </div>


  <!-- ISPRS 2026 -->
  <div class="pub-item">

    <div class="pub-thumb">
      <div class="pub-badge">ISPRS 2026</div>
      <img src="images/tasselnetv4-2.png" alt="TasselNetV4">
    </div>

    <div class="pub-info">

      <div class="pub-title">
        <a href="https://arxiv.org/abs/2509.20857">
          TasselNetV4: A Vision Foundation Model for Cross-Scene, Cross-Scale, and Cross-Species Plant Counting
        </a>
      </div>

      <div class="pub-authors">
        Xiaonan Hua, Xuebing Li, <strong>Jinyu Xu</strong>,
        Abdulkadir Duran Adan, Letian Zhou, Xuhui Zhu, Yanan Li,
        Wei Guo, Shouyang Liu, Wenzhong Liu, Hao Lu
      </div>

      <div class="pub-venue">
        ISPRS Journal of Photogrammetry and Remote Sensing 2026
      </div>

      <div class="pub-links">
        <a href="https://arxiv.org/abs/2509.20857">Paper</a>
        <a href="https://github.com/tiny-smart/TasselNetV4/">Code</a>
        <a href="https://huggingface.co/akaxiao/TasselNetV4">Model</a>
        <a href="https://mp.weixin.qq.com/s/9Q4j4Tj4BI1Q5I4_dvdjHQ">Social Media</a>
      </div>

    </div>

  </div>


  <!-- CAG 2026 -->
  <div class="pub-item">

    <div class="pub-thumb">
      <div class="pub-badge">CAG 2026</div>
      <img src="images/cag2026.png" alt="BRecStitch">
    </div>

    <div class="pub-info">

      <div class="pub-title">
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0097849326000865">
          Revisiting Unsupervised Image Stitching via Efficient Boundary Rectification
        </a>
      </div>

      <div class="pub-authors">
        Yun Zhang, Jialing Yang, Ruiyang Liang, Yao Xu, Lang Nie,
        <strong>Jinyu Xu</strong>, Fang-Lue Zhang, Xinyuan Zheng
      </div>

      <div class="pub-venue">
        Computers &amp; Graphics 2026
      </div>

      <div class="pub-links">
        <a href="https://www.sciencedirect.com/science/article/abs/pii/S0097849326000865">Paper</a>
        <a href="https://github.com/Jialing25y/BRecStitch">Code</a>
      </div>

    </div>

  </div>


  <!-- IST 2026 -->
  <div class="pub-item">

    <div class="pub-thumb">
      <div class="pub-badge">IST 2026</div>
      <img src="images/ist2026.png" alt="TrustDA">
    </div>

    <div class="pub-info">

      <div class="pub-title">
        <a href="https://doi.org/10.1016/j.infsof.2026.108249">
          Enhancing Trustworthiness Evaluation of Large Language Models through Dataset Refinement
        </a>
      </div>

      <div class="pub-authors">
        Jinwei Xu, Xin Zhou, Yanjing Yang, Tianhao Liu,
        <strong>Jinyu Xu</strong>, Chang Zhang, Lanxin Yang, Liming Dong
      </div>

      <div class="pub-venue">
        Information and Software Technology 2026
      </div>

      <div class="pub-links">
        <a href="https://doi.org/10.1016/j.infsof.2026.108249">Paper</a>
      </div>

    </div>

  </div>


</div>

# 🏆 Honors and Awards
- *2025.10*, **National Scholarship** (Highest honor for undergraduates in China).
- *2025.10*, **Merit Student**, Huazhong University of Science and Technology.
- *2025.05*, **Excellent Undergraduate Student**, Huazhong University of Science and Technology.
- *2024.10*, **National Scholarship** (Highest honor for undergraduates in China).
- *2024.10*, **Merit Student**, Huazhong University of Science and Technology.

# 💬 Academic Presentations
- *2026.5*, **Poster Presentation,**, Vision And Learning SEminar (VALSE). 
- *2026.5*, **Poster Presentation,**, China Society of Image and Graphics (CSIG) Conference. 

# 💻 Internships
- **Research Intern**, Graphics & Geometric Computing Group, Tsinghua University.  
  - Worked on procedural 3D scene modeling for embodied simulation environments.
- **Research Intern**, State Key Laboratory for Novel Software Technology, Nanjing University.  
  - Worked on the compliance assessment of multi-party large language models.

# 📖 Educations
- *2023.9 - 2027.6 (expected)*, B.Eng, Information security, Huazhong University of Science and Technology.

# 🎨 Hobbies
Beyond my research, I enjoy exploring different forms of art:
- **Calligraphy**: I enjoy practicing calligraphy to stay focused and appreciate the beauty of its structure and lines.
- **Movies**: I’m a big movie fan who loves exploring different stories and occasionally sharing my thoughts in reviews.

<!-- git status
git add .
git commit -m "update homepage"
git push origin main
git push secondary main -->