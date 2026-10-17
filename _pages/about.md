---
permalink: /
title: "Indira Sen"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a computer scientist and junior faculty at the [Chair of Data Science for the Social and Economic Sciences](https://www.bwl.uni-mannheim.de/en/information-systems/chairs/prof-dr-strohmaier/) in the [University of Mannheim](https://www.uni-mannheim.de/en/), Germany.  

My research lies at the intersection of Natural Language Processing (NLP) and Computational Social Science. I investigate the social knowledge, values, and perspectives embedded in generative AI systems, e.g., [political values in Large Language Models (LLMs)](https://aclanthology.org/2025.acl-long.1529/) and [their ability to assist and simulate](https://aclanthology.org/2025.findings-acl.1246/) [different groups of people](https://aclanthology.org/2025.findings-emnlp.1261/). Finally, I design methods for [assessing social values in LLMs](https://aclanthology.org/2026.eacl-long.89/). By interrogating and improving social knowledge in these models, I hope to build language technology that supports and reflects diverse user bases and populations.

Before Mannheim, I was a postdoc at the University of Konstanz in the Department of Politics and Public Policy. I did my PhD at RWTH-Aachen and GESIS, Leibniz Institute for the Social Sciences, advised by Claudia Wagner and Wil van der Aalst. My doctoral research focused on developing [valid and robust measurements of social constructs from digital trace data](https://academic.oup.com/poq/article-abstract/85/S1/399/6359490).

Before moving to Germany for my doctoral studies, I did my Master's at IIIT Delhi and my Bachelor's at Vellore Institute of Technology, both in India.

## News

- Oct'26: Attending EMNLP in Budapest and presenting a poster at the NLP4PI workshop on investigating how LLMs answer questions about democracy
- Oct'26: Participating in a panel discussion on ["Diversity and Gender in Research"](https://www.uni-mannheim.de/en/gender-equality-and-equal-opportunity/events/program-diversity-week-2026/#c502368) at the University of Mannheim
- Sept'26: Gave an invited lecture as a part of the [Lecture Series on AI & Survey Science](https://www.uni-mannheim.de/en/datascience/details/lecture-series-data-science-in-action-2024-interdisciplinary-and-international/). My lecture was titled ["Is AI Friend or Foe to Survey-based Data Collection?"](https://docs.google.com/presentation/d/1qvdSdyV_5t_TILtKTCoM6GTcRvzolx5c5sAE0PWryfw/edit?usp=sharing) 
- Fall-Winter Semester'26: teaching the 2nd iteration of ["Large Language Models for the Economic and Social Sciences"](https://github.com/dess-mannheim/LLM4ESS-HWS25/tree/main)
- I'm one of the program chairs of [ICWSM'27](https://www.icwsm.org/2027/)! 
- July'26: We organized a tutorial at IC2S2'26 on ["Simulating Human Survey Responses with Large Language Models: Potentials and Pitfalls"](https://dess-mannheim.github.io/tutorial_simulating_survey_responses/) 
- June'26: Gave an invited talk at the University of Innsbruck's Digital Science Center on ["Measuring Political Values in Large Language Models"](https://www.youtube.com/watch?v=OTYezztx_2g)
- June'26: We organized a workshop at the University of Mannheim on ["Shaping the Future of AI-Enabled Surveys"](https://www.bwl.uni-mannheim.de/strohmaier/news/workshop-ai-enabled-surveys/). Thanks to the Fritz-Thyssen Foundation, the Mannheim Centre for European Social Research, and the Mannheim Center for Data Science for supporting the workshop!

{% for item in site.data.news %}
* **{{ item.date }}**: {{ item.text | markdownify | remove: '<p>' | remove: '</p>' | strip }}
{% endfor %}
