---
layout: page
title: MATH-AI
subtitle: "The 4th Workshop on Mathematical Reasoning and AI"
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  (West Meeting Room 118-120, Vancouver, December 14, 2024, <a href="https://neurips.cc/virtual/2024/workshop/84719" target="_blank">Website</a>)
</div>



<div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/neurips-logo-new.jpg" />

<big><b style='color:red;'><a href="https://mathai2025.github.io/">The 5th MATH-AI workshop</a> will co-locate with NeurIPS 2025!</b></big>

# Previous MATH-AI Workshops

<div class="container" style="margin-bottom: 10px;"></div>
- [AI for Math Workshop @ ICML 2024](https://sites.google.com/view/ai4mathworkshopicml2024)
- 3rd MATH-AI Workshop at NeurIPS'23: [The 3rd Workshop on Mathematical Reasoning and AI](https://mathai2023.github.io/)
- 2nd MATH-AI Workshop at NeurIPS'22: [Toward Human-Level Mathematical Reasoning](https://mathai2022.github.io/)
- 1st MATH-AI Workshop at ICLR'21: [The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- MATHAI4ED Workshop at NeurIPS'21: [Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)

<div class="container" style="margin-bottom: 10px;"></div>

# Reviewer Nomination

If you'd like to become a reviewer for the workshop, or recommend someone, [please use this form](https://forms.gle/BssMrXeGgfMfLLFH9).

# Overview

Mathematical reasoning is a fundamental aspect of human cognition that has been studied by scholars ranging from philosophers to cognitive scientists and neuroscientists. Mathematical reasoning involves analyzing complex information, identifying patterns and relationships, and drawing logical conclusions from evidence. It is central to many applications in science, engineering, finance, and everyday contexts.

Recent advancements in large language models (LLMs) have unlocked new opportunities at the intersection of artificial intelligence and mathematical reasoning, ranging from new methods that solve complex problems or prove theorems, to new forms of human-machine collaboration in mathematics and beyond. 

Our proposed workshop is centered on the intersection of deep learning and mathematical reasoning, with an emphasis on, but not limited to, large language models. 
Our guiding theme is:

*“To what extent can machine learning models comprehend mathematics, and what applications could arise from this capability?”*

To address this question, we aim to bring together a diverse group of scholars from different backgrounds, institutions, and disciplines into our workshop. Our objective is to foster a lively and constructive dialogue on areas related, but not limited, to the following:
- **Humans vs. machines**: A comparative study of human-level mathematical reasoning and current AI techniques. How do they differ, complement one another, or intersect?
- **Measuring mathematical reasoning**: How do we design benchmarks which accurately evaluate mathematical reasoning abilities, especially in an era of large language models?
- **New capabilities**: How do we move beyond our current techniques?
- **Education**: What role can deep learning models play in mathematics education, especially in contexts with limited educational resources?
- **Applications**: What applications could AI systems enable in the near- and long-term? Example domains include software verification, sciences, engineering, finance, education, and mathematics itself.


<hr>

# Speakers & Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.speakers %}
    {% if forloop.index<=5 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>5 and forloop.index<=10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
<a href="speakers">More Info</a>
</div>

<hr>

# Organizers
<!-- # Organizers -->

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <!-- <br> 
  <div class="row" style="margin: -30px;"> -->
  <div class="row">
    {% for p in site.data.organizers %}
    {% if forloop.index<=4 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>4 and forloop.index<=8%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>

<!-- # Program Committee
<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr> -->

# Related Venues

<div class="container" style="margin-bottom: 10px;"></div>
- [ICML'24 Workshop on AI4MATH - AI for Math Workshop @ ICML 2024](https://sites.google.com/view/ai4mathworkshopicml2024)
- [NeurIPS'23 Workshop on MATH-AI - The 3rd Workshop on Mathematical Reasoning and AI](https://mathai2023.github.io/)
- [NeurIPS'22 Workshop on MATH-AI - Toward Human-Level Mathematical Reasoning](https://mathai2022.github.io/)
- [NeurIPS'21 workshop on MATHAI4ED - Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)
- [ICLR'21 workshop on MATH-AI - The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- [NeurIPS'20 Workshop on KR2ML - Knowledge Representation & Reasoning Meets Machine Learning](https://kr2ml.github.io/2020)
- [NeurIPS'20 workshop on Advances and Opportunities: Machine Learning for Education](https://www.ml4ed.org/)
- [ICML'20 workshop on Bridge  Between Perception and Reasoning: Graph Neural Networks & Beyond](https://logicalreasoninggnn.github.io)

<div class="container" style="margin-bottom: 10px;"></div>

<hr>

Contact: <mathai.neurips2024@gmail.com>.
