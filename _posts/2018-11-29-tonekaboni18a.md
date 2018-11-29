---
abstract: Cardiac arrest is a rare but devastating event in critically ill children
  associated with death, disability and significant healthcare costs. When a cardiac
  arrest occurs, the limited interventions available to save patient lives are associated
  with poor patient outcomes. The most effective way of improving patient outcomes
  and decreasing the associated healthcare costs would be to prevent cardiac arrest
  from occurring. This observation highlights the importance of prediction models
  that consistently identify high risk individuals and assist health care providers
  in providing targeted care to the right patient at the right time. In this paper,
  we took advantage of the power of convolutional neural networks (CNN) to extract
  information from high resolution temporal data, and combine this with a recurrent
  network (LSTM) to model time dependencies that exist in these temporal signals.
  We trained this CNN+LSTM model on high-frequency physiological measurements that
  are recorded in the ICU to facilitate early detection of a potential cardiac arrest
  at the level of the individual patient. Our model results in an F1 value of 0.61
  to 0.83 across six different physiological signals, the most predictive single signal
  being the heart rate. To address the issue of instances of missing data in the recorded
  physiological signals, we have also implemented an ensemble model that combines
  predictors for the signals that were collected for a given patient. The ensemble
  achieves 0.83 average F1 score on a held-out test set, on par with the best performing
  signal, even in the absence of a number of signals. The results of our model are
  clinically relevant. We intend to explore implementation of this model at the point
  of care as a means of providing precise, personalized, predictive care to an at-risk
  cohort of patients.
booktitle: Proceedings of the 3rd Machine Learning for Healthcare Conference
title: Prediction of Cardiac Arrest from Physiological Signals in the Pediatric ICU
volume: '85'
year: '2018'
layout: inproceedings
series: Proceedings of Machine Learning Research
id: tonekaboni18a
month: 0
tex_title: Prediction of Cardiac Arrest from Physiological Signals in the Pediatric
  ICU
firstpage: 534
lastpage: 550
page: 534-550
order: 534
cycles: false
bibtex_author: Tonekaboni, Sana and Mazwi, Mjaye and Laussen, Peter and Eytan, Danny
  and Greer, Robert and Goodfellow, Sebastian D. and Goodwin, Andrew and Brudno, Michael
  and Goldenberg, Anna
author:
- given: Sana
  family: Tonekaboni
- given: Mjaye
  family: Mazwi
- given: Peter
  family: Laussen
- given: Danny
  family: Eytan
- given: Robert
  family: Greer
- given: Sebastian D.
  family: Goodfellow
- given: Andrew
  family: Goodwin
- given: Michael
  family: Brudno
- given: Anna
  family: Goldenberg
date: 2018-11-29
address: 
publisher: PMLR
container-title: Proceedings of the 3rd Machine Learning for Healthcare Conference
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 11
  - 29
pdf: http://proceedings.mlr.press/v85/tonekaboni18a/tonekaboni18a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
