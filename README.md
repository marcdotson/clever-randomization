Accommodating Data Pathologies in Conjoint
================

## Abstract

Respondent behavior in conjoint studies often deviates from the
assumptions of random utility theory. We refer to deviations from
normative choice behavior as data pathologies. A variety of models have
been developed that attempt to correct for specific pathologies (i.e.,
screening rules, respondent quality, attribute non-attendance, etc.).
While useful, these approaches tend to be both conceptually complex and
computational intensive. As such, these approaches have not widely
diffused into the practice of marketing research. In this paper we draw
on innovations in machine learning to develop a practical approach that
relies on (clever) randomization strategies and ensembling to
simultaneously accommodate multiple data pathologies in a single model.
We provide tips and tricks on how to implement this approach in
practice.

## Project Organization

  - PYTHON includes code written in python that compiles the stan models
  - R includes code written in R
  - STAN includes the multinomial logit models written in Stan
  - Files ending in .ipynb are jupyter notebooks
