# reasearch Projext for XAI tool investigation 
## University Stuttgart
## Group  Member:
# Installation

Python 3.7+ | Linux, Mac, Windows
```sh
pip install interpret
# OR
conda install -c conda-forge interpret

## XAI Tools
| Interpretability Technique  | Type               |
|-----------------------------|--------------------|
| [Explainable Boosting](https://interpret.ml/docs/ebm.html)        | glassbox model     |
| [Decision Tree](https://interpret.ml/docs/dt.html)                | glassbox model     |
| [Decision Rule List](https://interpret.ml/docs/dr.html)           | glassbox model     |
| [Linear/Logistic Regression](https://interpret.ml/docs/lr.html)   | glassbox model     |
| [SHAP Kernel Explainer](https://interpret.ml/docs/shap.html)      | blackbox explainer |
| [LIME](https://interpret.ml/docs/lime.html)                       | blackbox explainer |
| [Morris Sensitivity Analysis](https://interpret.ml/docs/msa.html) | blackbox explainer |
| [Partial Dependence](https://interpret.ml/docs/pdp.html)          | blackbox explainer |