# Project Summary:

This study aims to identify biometric patterns in PASC and explore potential digital biomarkers to assess treatment efficacy. It complements our previous study [The STOP-PASC Randomized Clinical Trial](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2819901)
[1]. This is the first longitudinal wearable device study tracking digital biometric measures in a randomized controlled pharmacologic interventional trial in PASC to our knowledge. 

# Dataset:

The STOP-PASC trial was a randomized, placebo-controlled study that assessed the effectiveness of nirmatrelvir-ritonavir (PAXLOVID) in treating post-acute sequelae of SARS-CoV-2 infection (PASC) in adults. A total of 155 participants with PASC were randomized in a 2:1 ratio to receive either the treatment or a placebo over a 15-day period. A subset participated in a wearable substudy, using an Apple Watch to continuously collect biometric data—such as physical activity, heart rate, and oxygen saturation—over a 15-week period. From this data, multiple endpoints were derived, including peak activity, step counts, heart rate variability, median oxygen saturation, and other biometric indicators.

# Repository Structure:

The repo consists of two files listed below:

1. lcmm: This file contains the necessary code for latent class mixed models to identify distinct groups of participants with similar longitudinal summary measure patterns separately for each endpoints (2). 

2. downstream_analysis: This file contains the code used for downstream analysis, including comparisons between treatment arms, clustering of summary measure trajectories, and the creation of tables and figures.


# Citations:

 1. Geng LN, Bonilla H, Hedlin H, et al. Nirmatrelvir-Ritonavir and Symptoms in Adults With Postacute Sequelae of SARS-CoV-2 Infection: The STOP-PASC Randomized Clinical Trial. JAMA Intern Med 2024; 184(9): 1024–1034. 

 2. Proust-Lima C, Philipps V, Diakite A, et al. Extended Mixed Models Using Latent Classes and Latent Processes. R package version 2.1.0, 2023. https://cecileproust-lima.github.io/lcmm/.
