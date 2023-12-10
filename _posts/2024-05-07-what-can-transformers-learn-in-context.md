---
layout: distill
title: What can Transformers learn In-C
description: In-context learning is a phenomena that involves learning a new task by a Language Model without any weight updates. However, it is still unknown (to an extent) as to how this behaviour pops up in these Language Models. Is it possible to train models to elicit ICL, to what extent we can expect ICL to last, for what tasks and the list of questions goes on. In this blog, I shall tackle one part of ICL which is to elicit ICL behaviour by training a transformer based model to learn simple functions by exploring What Can Transformers Learn In-Context? A Case Study of Simple Function Classes paper that was accepted at NeurIPS 2022.
date: 2024-05-07
future: true
htmlwidgets: true

Anonymize when submitting
authors:
  - name: Anonymous

# must be the exact same name as your blogpost
bibliography: 2024-05-07-what-can-transformers-learn-in-context.bib

toc:
 - name: Introduction and Motivation
 - name: Experiments
   - subsections:
     - name: In-context learning of linear functions
     - name: ICL beyond the training distribution
     - name: Learning more complex functions
 - name: What actually matters for ICL?
 - name: Conclusion


## Introduction and Motivation