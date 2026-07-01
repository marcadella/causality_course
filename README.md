## Effect of smoking during pregnancy on newborn weight

We study the effect of smoking during pregnancy on the weight of the newborns.

### Data

Data was found [here](https://www.kaggle.com/datasets/jacopoferretti/child-weight-at-birth-and-gestation-details/data) and originally comes from Child Health and Development Studies.

The following description was found [here](https://www.kaggle.com/code/muhammedaliyilmazz/birth-weight-analysis-ml-modeling).

Dataset Description: Child Birth Weight and Gestation Details

This dataset was compiled to investigate the influence of various factors on a child's birth weight (in ounces).
It includes demographic and health information pertaining to the mothers, as well as details related to the pregnancy period.

Features:
- case ID number: A unique identifier assigned to each birth event (case). It is generally not used directly in analyses but is important for tracking records.
- bwt (Birthweight): The weight of the baby at birth, expressed in ounces.
- gestation: The total length of the pregnancy, indicated in days. Longer gestation periods are generally expected to correlate with higher birth weights.
- parity (Parity - First Pregnancy Indicator): A binary variable indicating whether the mother's current pregnancy was her first.
  - 0: The mother's current pregnancy was not her first, meaning she has given birth previously.
  - 1: The mother's current pregnancy was her first. First pregnancies may have different effects on birth weight.
- age (Mother's Age): The age of the mother at the time of birth, expressed in years. Maternal age is known to potentially influence birth outcomes.
- height (Mother's Height): The height of the mother, measured in inches. The mother's physical characteristics may be related to birth weight.
- weight (Mother's Weight): The mother's weight prior to pregnancy or at a specific stage of pregnancy, expressed in pounds. The mother's weight can be a significant factor in the baby's development.
- smoke (Smoking Status Indicator): A binary variable indicating whether the mother smoked during pregnancy.
  - 0: The mother did not smoke.
  - 1: The mother smoked. Smoking during pregnancy is widely known to be associated with lower birth weights.

### Other resources

Most of the source code is inspired (sometimes directly copied from):
- [Causal Inference for the Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)
- [NORA Summer School 2026: Causality and Machine Learning](https://johandh2o.github.io/causal-inference-summer-school/)
