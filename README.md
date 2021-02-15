# Credit_Risk_Analysis

## Overview 
The purpose of this analysis is to employ different techniques to train and evaluate models with unbalanced classes, ultimately to solve for credit card risk.

## Results: 
- Naive Random Oversampling
	![Naive Random](/Resources/img1.png)
- SMOTE Oversampling
	![SMOTE](/Resources/img2.png)
- Undersampling
	![Under Sample](/Resources/img3.png)
- Combination (Over and Under) Sampling (SMOTEENN)
	![SMOTEENN](/Resources/img4.png)
- Balanced Random Forest Classifier
	![BRFC](/Resources/img5.png)
- Easy Ensemble AdaBoost Classifier
	![AdaBoost](/Resources/img6.png)

Accuracy scores with a notable exception of the Easy Ensemble AdaBoost Classifier that showed a .99 accuracy, all hovered between .59 and .68.

Precision was very low (.01 for high-risk applicants, but sensitivity was between .6 to .69 for most models).
Precision for low risk applicants was very high (1.00) in most models.

Recall for high-risk and low-risk applicants mirrored each other between .57 to .69.

## Summary: 
To the Grader:
I will have to come back to this.  I truly am struggling to understand this material and am not clear that I performed the analysis correctly.  Look forward to any guidance you can provide.