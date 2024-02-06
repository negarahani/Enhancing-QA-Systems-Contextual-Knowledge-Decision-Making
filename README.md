# Enhancing-QA-Systems-Contextual-Knowledge-Decision-Making
# Overview
This project focuses on developing a Question Answering (QA) model that integrates both parametric knowledge (inherent in model weights) and contextual knowledge (external information) to generate informative answers. It introduces a solution called "post-hoc knowledge injection" to enhance answer quality by leveraging external sources.
# Dataset
A subset of the Natural Questions (NQ) dataset is utilized for this project. The dataset preprocessing and creation details can be found in the provided notebooks.
Dataset Link: https://ai.google.com/research/NaturalQuestions/download
# Methodology
# Parametric Answer Generation
Utilizing RoBERTa model from the simpletransformers library, parametric answers are generated after thorough preprocessing of the NQ dataset. Training and testing details are outlined in the respective notebook.
# Contextual Answer Generation
Two approaches are explored: a literature-driven method and a proposed method. These methods aim to generate diverse contextual responses to augment parametric answers.
Knowledge Injection
Contextual knowledge is injected into the system using a probabilistic framework, enhancing the QA process. Probability assignments are discussed based on dataset segments.
# Classification
Semantic correlation between parametric and contextual answers is computed to derive a final score for selecting the most probable contextual answer.
# Results & Discussion
The parametric model achieves satisfactory accuracy, while the proposed approach for contextual answer generation shows significant improvement over the literature-driven method. The results suggest the effectiveness of the proposed approach in providing accurate contextual responses.
