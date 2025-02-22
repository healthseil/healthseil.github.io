### Explainabiity

**Model-agnostic Interpretability for Clinical Machine Learning**

As health systems increasingly adopt black-box machine learning models for clinical and operational purposes, the need for interpretability has become critical. While these models are promising it terms of performance, their complexity often makes it difficult for end-users to understand how decisions or recommendations are made, limiting their trust and use in decision-making. Our research focuses on model-agnostic interpretability techniques specifically for temporal models. Traditional interpretability methods such as Shapley Additive Explanations (SHAP) can be computationally expensive and may not be well-suited for time-series data such as longitudinal electronic health record data and continuous monitoring data in acute care settings. We have developed, for example, a revived approach called ***WindowSHAP*** to address these challenges and advance the interpretability of clinical machine learning models, regardless of their underlying model architecture. Key research questions we are exploring in this area include: How do inherently interpretable models compare against model-agnostic interpretability methods in the context of time-series clinical data? What theories and methodological approaches challenge the notion of performance-explainability trade-off in real-world clinical applications? What are the most effective post-hoc explainability methods for various end-users, including clinicians and engineers? In what ways do those methods foster clinician trust and patient safety?

!!! abstract "Products"

    Nayebi, A., Tipirneni, S., Reddy, C. K., Foreman, B., & Subbian, V. (2023). **WindowSHAP: An efficient framework for explaining time-series classifiers based on Shapley values.** Journal of biomedical informatics, 144, 104438. 
    <a href="https://doi.org/10.1016/j.jbi.2023.104438" target="_blank">https://doi.org/10.1016/j.jbi.2023.104438</a> | Alternative Full-text Option: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10552726/" target="_blank"> PMC10552726 </a> 

    Nayebi, A., Tipirneni, S., Foreman, B., Reddy, C. K., & Subbian, V. (2023). An Empirical Comparison of Explainable Artificial Intelligence Methods for Clinical Data: A Case Study on Traumatic Brain Injury. AMIA Annual Symposium Proceedings. 2022, 815–824.<a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10148324/" target="_blank">Full-text</a>

### Digital Phenotyping

**Computable Clinical Phenotypes**

Accurate and reliable phenotyping is essential for conducting robust observational studies and designing adaptive and safe clinical decision support systems. A significant part of our research involves developing algorithms and methods to effectively identify computable phenotypes for a range of conditions including traumatic brain injury, acute respiratory failure, and post-acute sequelae of SARS-Cov-2 (PASC or Long COVID). We use both rule-based algorithms and representation learning methods to address complexities of using routinely collected clinical data for research purposes. The following are our prime examples and outcomes of our work related to computable phenotypes. 

* We have developed and validated first of its kind rule-based electronic phenotyping algorithm to classify patient records based on type and sequence of respiratory support received, among other critical factors. 
* Using a representation learning framework, which we designed, we have identified distinct phenotypes of traumatic brain injury that can potentially inform future clinical trials as well as personalized interventions. 
* We have also demonstrated computable phenotypes for defining and characterizing long-term effects of SARS-Cov-2 infection (i.e., PASC) based on symptom duration, infection severity, and the presence of specific symptom clusters. 

!!! abstract "Products"

    === "Acute Respiratory Failure"
        * Essay, P., Mosier, J., & Subbian, V. (2020). **Rule-Based Cohort Definitions for Acute Respiratory Failure: Electronic Phenotyping Algorithm.** JMIR medical informatics, 8(4), e18402. <a href="https://doi.org/10.2196/18402" target="_blank">Full-text</a>
        * Essay, P., Fisher, J. M., Mosier, J. M., & Subbian, V. (2022). Validation of an Electronic Phenotyping Algorithm for Patients With Acute Respiratory Failure. Critical care explorations, 4(3), e0645. <a href="https://doi.org/10.1097/CCE.0000000000000645" target="_blank">Full-text</a> 
        * Mosier, J. M., Subbian, V., Pungitore, S., Prabhudesai, D., Essay, P., Bedrick, E. J., Stocking, J. C., & Fisher, J. M. (2024). Noninvasive vs invasive respiratory support for patients with acute hypoxemic respiratory failure. PloS one, 19(9), e0307849. <a href="https://doi.org/10.1371/journal.pone.0307849" target="_blank">Full-text</a>
        

    === "Traumatic Brain Injury"
        * Ghaderi, H., Foreman, B., Nayebi, A., Tipirneni, S., Reddy, C. K., & Subbian, V. (2023). **A self-supervised learning-based approach to clustering multivariate time-series data with missing values (SLAC-Time): An application to TBI phenotyping.** Journal of biomedical informatics, 143, 104401. <a href="https://doi.org/10.1016/j.jbi.2023.104401" target="_blank">https://doi.org/10.1016/j.jbi.2023.104401</a>
        * Ghaderi, H., Foreman, B., Reddy, C. K., & Subbian, V. (2024). Discovery of generalizable TBI phenotypes using multivariate time-series clustering. Computers in biology and medicine, 180, 108997. <a href="https://doi.org/10.1016/j.compbiomed.2024.108997" target="_blank">https://doi.org/10.1016/j.compbiomed.2024.108997</a> | Alterative Full-text Option: <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10836078/" target="_blank"> PMC11401775 </a>
        * Ghaderi, H., Foreman, B., Nayebi, A., Tipirneni, S., Reddy, C. K., & Subbian, V. (2024). Identifying TBI Physiological States by Clustering Multivariate Clinical Time-Series Data. AMIA Annual Symposium proceedings. AMIA Symposium, 2023, 379–388. <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10785849/" target="_blank">Full-text</a> | :fontawesome-solid-award: _Distinguished Paper Award_

    === "PASC"
        Pungitore, S., Olorunnisola, T., Mosier, J., Subbian, V., & N3C Consortium (2024). **Computable Phenotypes for Post-acute sequelae of SARS-CoV-2: A National COVID Cohort Collaborative Analysis.** AMIA Annual Symposium Proceedings, 2023, 589–598. <a href="https://pmc.ncbi.nlm.nih.gov/articles/PMC10785914/" target="_blank">Full-text</a>

### Cognitive Informatics

**Human Factors Engineering and Clinical Decision-Making**

To support our translational work, we study how decisions are made in real-world clinical environments, where traditional decision theories often fall short in capturing the true sociotechnical dynamics. For example, decision-making related to ventilation strategies for critically ill patients is a nuanced and complex challenge in acute care settings, where care teams must balance patient needs, available resources, and documentation workflows. We focus on key questions that clinicians face when deciding on ventilation strategies: determining when to start with non-invasive or invasive ventilation, selecting appropriate forms of non-invasive respiratory, and deciding when non-invasive methods have failed, necessitating intubation. On one end, we employ cognitive engineering methods to capture both the operational complexities of acute care settings and the cognitive expertise of clinicians. On the other end, we apply computational approaches to identify when and who might fail non-invasive ventilation therapies early enough to allow clinicians to intervene and potentially improve patient outcomes. Our findings provide a holistic view of the decision-making process related to ventilation therapies, as well as insights for designing and implementing clinical decision support systems that enhance cognitive support for clinicians. 

!!! abstract "Products"

    Zhang, T., Mosier, J., Campbell, E. S., & Subbian, V. (2024). **To NIRS or not: understanding clinical decision-making of respiratory support management related to acute respiratory failure using Critical Decision Method.** IISE Transactions on Healthcare Systems Engineering, 1-12. <a href="https://doi.org/10.1080/24725579.2024.2335988" target="_blank">https://doi.org/10.1080/24725579.2024.2335988</a>

    Zhang, T., Mosier, J., & Subbian, V. (2025). **How do clinicians use electronic health records for respiratory support decisions? A qualitative study in critical care.** ACI Open, 9(01), e9-e17. <a href="10.1055/a-2521-2557" target="_blank">https://doi.org/10.1055/a-2521-2557</a>

    Essay, P. T., Mosier, J. M., Nayebi, A., Fisher, J. M., & Subbian, V. (2023). Predicting Failure of Noninvasive Respiratory Support Using Deep Recurrent Learning. Respiratory care, 68(4), 488–496. <a href="https://doi.org/10.4187/respcare.10382" target="_blank">https://doi.org/10.4187/respcare.10382</a>
