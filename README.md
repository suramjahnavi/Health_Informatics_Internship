# Health_Informatics_Internship
Project Overview 

The project was built on the HAM10000 dermoscopic image dataset, and the system architecture was designed in a modular way using multiple intelligent agents: 

• The Triage Agent filters images based on malignancy probability. 

• The Navigation Agent manages image flow based on triage results. 

• The Decision Agent applies advanced models like ViT, CLIP, and GIT to assess malignancy, generate descriptive explanations, and output a final malignancy score. 


We developed two systems for comparison: 

• System S1: Uses only the ViT model for prediction. 

• System S2: Uses a multi-agent approach, integrating ViT with CLIP and GIT for more nuanced decision-making. 


The systems were evaluated using 10-fold cross-validation, ROC curves, and key metrics such as sensitivity, specificity, true positives, and false negatives at various triage thresholds. 
Key Achievements 

• Built an end-to-end pipeline combining image classification and vision-language modeling. 

• Computed malignancy scores and created a unified CSV summary for all models. 

• Identified that while S2 introduced complexity and explainability, S1 performed better in sensitivity and simplicity for this dataset.
