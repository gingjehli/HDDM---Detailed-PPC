# HDDM---Detailed-PPC
HDDM -- Detailed Posterior Predictive Checks
Note that this script was initially created to perform posterior predictive checks (PPCs) for regression models that have been fitted within HDDM and that utilized the LAN extension. However, the script can be adjusted to be applicable to models without regression equations and/or that have been fitted using the "classical HDDM" without the LAN extension


If you have difficulties to render the notebook online, check out this link to the nbviewer: 
https://nbviewer.org/github/gingjehli/HDDM---Detailed-PPC/blob/main/PPCscript_HDDM_RegressionModels_LAN_template1.ipynb


This script was developed to perform posterior predictive checks (PPCs) for regression models fitted with the LAN extension within HDDM. However, the script can be modified to be applicable to models that do not include any regression equations (for model parameters) and/or to models that have been fitted outside the LAN extension but within HDDM.

Included are three different posterior predictive checks (subsequently referred to as PPC1 to PPC3). These three checks will help to visualize potential misfits of the model by simultaneously considering response frequency and the entire RT distribution of each response frequency. This is important because an examination of how well a model fits the data, should not only include fits for mean reaction times (RTs) or response frequency. Instead, since one of the key advantages of a DDM is that it simultaneously fits response frequency and the shape of the entire RT distribution, assessing model performance should also include such a fine-grained analysis. The differences and similarities between the three different PPCs will be explained for each PPC separately.

More details are provided in the script itself.
