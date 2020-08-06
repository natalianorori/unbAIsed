
# Identifying and mitigating bias in deep learning for biomedical data through open science practices

## Project Objectives 

1. To investigate how open science can mitigate bias in biomedical datasets; raising awareness about racial inequalities in biomedical sciences

2. to raise awareness about (a) racial inequalities in the biomedical and AI fields; (b) the negative consequences of the lack of diversity in biomedical data (c) ways to render biomedical data sharing more equitable through the open movement.


## Project Summary 

Artificial intelligence (AI) has an astonishing potential to assist clinical decision-making and revolutionize global health. However, the use of AI in the biomedical field needs to ensure that it can be accessed by everyone, taking into account the needs of diverse populations. Most AI algorithms need large datasets to learn from, but vulnerable groups have a long history of being absent or misrepresented in existing datasets. If the training data is misrepresentative of the population variability, AI is prone to reinforcing inequality and bias, which can lead to dangerous outcomes and misdiagnoses.

In one of many examples, AI algorithms used health costs as a proxy for health needs and falsely concluded that Black patients are healthier than equally sick White patients, as less money was spent on them (10.1126/science.aax2342). Biased data and dangerous AI conclusions exist in most medical fields, but attempts to control for that bias remain limited.

When it comes to dermatology,  artificial intelligence is being widely implemented to classify and diagnose skin lesions. A study published in Nature demonstrated that artificial intelligence is capable of classifying skin cancer with a level of competence comparable to dermatologists. Other studies employing similar algorithms reported the same. After widely analyzing some of the most popular open datasets used to train the algorithms in which these studies are based, we discovered the data predominantly contains images of lesions in caucasian skin. To avoid replicating existing bias, it is crucial to make sure the data collected reflects the diversity of existing populations.

In this project, we will use openly available biomedical data to explore how bias affects diagnosis in underrepresented populations. We will focus on skin lesion data, where diversity can be quantified by the data samples’ color. We will train convolutional neural networks (CNNs) to classify leasioned vs. healthy samples (10.1038/nature21056). As most available datasets are heavily biased towards caucasian samples, we will first present to the CNNs only caucasian samples and test their performance on darker skin. We will then gradually increase the number of non caucasian samples in the training data. We expect the networks’ performance on darker skin to increase as a function of the diversity in the data that the algorithm has already seen. 

To our knowledge, there are no studies that have tested the accuracy of ai-driven skin lesion classification technologies in dark-skinned patients. To quantify the problem, we are working on training a deep learning algorithm with caucasian skin samples and testing how it performs on darker skin.  Our end goal is to expand the ethnic variability of the dataset and compare how it performs against algorithms trained with imbalanced data. 

The idea of this research project started during MozFest 2019. We have since been working on it, but we unfortunately lack the resources to finalize it. This funding would be ideal, as it will allow us to (a) hire a part-time research assistant to train CNNs and test their generalizability on new skin samples; (b) fund our collaborator Natalia Norori to work with us on issuing guidelines for how open practices can mitigate bias; (c) organize an online replicable workshop to communicate our findings to the wider community.
  

## How to contribute 
This project is still in its early stages. We are currently studying existing technologies, collecting and analyzing data to develop the algorithm we will be using. If you are interested in contributing, get in touch with us. 

 
## Participants 

[Athina Tzovara](https://twitter.com/aath0) - University of Bern, Switzerland 

[Natalia Norori](https://twitter.com/natalianorori) - Universidad Latina de Costa Rica, Costa Rica 

[Florence Aellen](https://www.inf.unibe.ch/about_us/people/ccn/aellen_florence/index_eng.html) - University of Bern, Switzerland
