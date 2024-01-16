---title: "Roadmap"author: "Joe Hou, Yunda Huang, James Kobie"date: "2024-01-16"output: html_document---<h1 align="center">CMI-PB Challenge Summary</h1># <span style="font-size:15px;"> # CMI-PB Challenge SummaryThe CMI-PB Challenge is centered around the analysis of immune responses to Pertussis booster vaccinations using systems vaccinology. Participants are provided with multi-omics datasets from a cohort of individuals primed in infancy with either acellular Pertussis (aP) or whole cell Pertussis (wP) vaccines and later boosted with Tdap. Individuals born before 1995 received wP, while those after 1996 received aP. The study design includes pre- and post-booster blood and plasma samples at intervals of 1, 3, 7, and 14 days.The datasets encompass:(1) Cell frequency in PBMCs analyzed by flow cytometry(2) Gene expression profiles covering over 50,000 genes(3) Plasma cytokine concentrations for 30 soluble proteins measured with Olink technology(4) Antibody titers against more than 7 antigens## Our Approach:In tackling the CMI-PB Challenge, my strategy involves leveraging the SuperLearner algorithm, a powerful ensemble machine learning method, to analyze the immune response data. This approach allows for the integration of various predictive models, maximizing the predictive accuracy.Key steps in my methodology include:- **Data Description and Preprocessing**: Thoroughly examining the baseline characteristics of the multi-omics datasets to ensure a robust starting point for analysis.- **Consistency Check**: Ensuring data integrity and consistency across different omics datasets, which is crucial for reliable model building.- **Model Building with SuperLearner**:    -Selecting multiple prediction methods within SuperLearner to handle the complex nature of the immune response data.    -Carefully choosing relevant data features, including considering predictions based on the target assay or incorporating additional variables from other assays.    -Finalizing the model with optimized selection of methods and data inputs to accurately predict the outcomes of the Tdap booster vaccination.</span><img src="/Users/jhou2/Documents/GitHub/CMI-PB-Challenge/CMI PB Roadmap.png" alt="SuperLearner Approach">This comprehensive approach, rooted in the capabilities of SuperLearner, is designed to untangle the intricate patterns in the immune response data, aiming to contribute meaningful insights into vaccine-induced immunity.