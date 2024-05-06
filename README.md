# Causal Inference in Competing Risks Settings


This repository organizes our simulations and based on the paper [A causal framework for classical statistical estimands in failure-time settings with competing events](https://outlook.office.com/mail/safelink.html?url=https://urldefense.com/v3/__https://pubmed.ncbi.nlm.nih.gov/31985089/__;!!K-Hz7m0Vt54!lqpl1Sy9GIEKOBx3_1-lACcU0BBTCEi9LabWW31rShX6nItP8oCsHaoLXVyI0VGT6ljnPE-ZwI4VKQ$&corid=32eca395-b52f-bd10-6579-b33ebe0e5671).


Our aims are to:

(1) Demonstrate the different types of questions one can ask involving competing risks and the interpretation of corresponding estimates. We will qualitatively compare the practicality and usefulness of the estimands in applied settings.

(2) Quantitatively compare the estimators under various sample sizes, data generating processes, and forms of model misspecification. We will use R for our simulations, specifically, the sim_confounded_crisk function from the open-source adjustedCurves R package. We will simulate time-to-event data with multiple causes of failure and various underlying data generation mechanisms. We will create summary figures of our simulation results, including mean estimates, mean standard errors, and mean squared error across different sample sizes.

(3) We will conclude by reviewing the results of the simulations and briefly discuss estimation methods with improved robustness properties.
