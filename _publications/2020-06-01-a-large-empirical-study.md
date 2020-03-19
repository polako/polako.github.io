---
title: "A large scale empirical study of the impact of Spaghetti Code and Blob anti-patterns on program comprehension"
collection: publications
permalink: publications/2020-06-01-a-large-empirical-study
excerpt:
date: 2020-06-01
venue: 'Information and Software Technology -- Elsevier'
paperurl: 'https://cpoli.live/files/A_Large_Scale_Study.pdf'
---

Several studies investigated the impact of anti-patterns (i.e., "poor" solutions to recurring design problems) during maintenance activities and reported that anti-patterns significantly affect the developers’ effort required to edit files. However, before developers edit files, they must understand the source code of the systems. This source code must be easy to understand by developers.

In this work, we provide a complete assessment of the impact of two instances of two anti-patterns, Blob or Spaghetti Code, on program comprehension.

We analyze the impact of these two anti-patterns through three empirical studies conducted at Polytechnique Montréal (Canada) with 24 participants; at Carlton University (Canada) with 30 participants; and at University Basilicata (Italy) with 79 participants.

We collect data from 372 tasks obtained thanks to 133 different participants from the three universities. We use three metrics to assess the developers’ comprehension of the source code: (1) the duration to complete each task; (2) their percentage of correct answers; and, (3) the NASA task load index for their effort.

We report that, although single occurrences of Blob or Spaghetti code anti-patterns have little effect on code comprehension, two occurrences of either Blob or Spaghetti Code significantly increases the developers’ time spent in their tasks, reduce their percentage of correct answers, and increase their effort. Hence, we recommend that developers act on both anti-patterns, which should be refactored out of the source code whenever possible. We also recommend further studies on combinations of anti-patterns rather than on single anti-patterns one at a time.

[Download paper here](https://cpoli.live/files/A_Large_Scale_Study.pdf)

```
@article{Politowski2020,
    title = "A large scale empirical study of the impact of Spaghetti Code and Blob anti-patterns on program comprehension",
    journal = "Information and Software Technology",
    volume = "122",
    pages = "106278",
    year = "2020",
    issn = "0950-5849",
    doi = "https://doi.org/10.1016/j.infsof.2020.106278",
    author = "Cristiano Politowski and Foutse Khomh and Simone Romano and Giuseppe Scanniello and Fabio Petrillo and Yann-Gaël Guéhéneuc and Abdou Maiga",
    keywords = "Anti-patterns, Blob, Spaghetti Code, Program comprehension, Java",
}
```

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->
