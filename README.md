Current github repo provides implementation of Semi-Automatic Explainable Machine Learning Pipeline that was initially developed under the research project of Twitter Bot detection with title: "BotArtist: Twitter bot detection Machine Learning model based on Twitter suspension"

## Requirements
Installation of required packages:
```bash
python3.9 -m pip install -r requirements.txt
```

## Model Explainability
Current implementation allows to explain the model decision under the construction of the binary and multi-class classification tasks. We are also currently working on the development of the regression explainability. As the method of the model explainability we utilise the SHAP game theoretic approach.

## Utilised models:
We are limited to models with specific functionality such as: fit, predict and predic_proba in order to fine-tune the final model decision threshold and also properly utilise the model explainability. Based on this limitations we are currently manage to import Rand
omForest, SVM and XGBoost models. The implementation is not limited to these models only and allows importing with few lines of code to import any other model, which will comply with the described limitations of functionality.

## Coomunication

Alexander Shevtsov: asevtsov[at]tuc.gr
