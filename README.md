# Digix-AI-Challenge-Resources

* [Huawei Hackathon link](https://developer.huawei.com/consumer/en/activity/digixActivity/digixdetail/101592649207348035)
* [Facebook Hackathon link](https://fbai3.devpost.com/?ref_content=default&ref_feature=challenge&ref_medium=discover)
* [Dataset link](https://colab.research.google.com/drive/1uBeyAR329YQAH8h1_elwIUuc7hCCRbD7?authuser=1)

## Resources
* [Combination of Multiple Global Descriptors for Image Retrieval](https://arxiv.org/pdf/1903.10663v1.pdf)
* [PyRetri: A PyTorch-based Library for Unsupervised Image
Retrieval by Deep Convolutional Neural Networks](https://arxiv.org/pdf/2005.02154v2.pdf)
* [Deep Image Retrieval:
Learning global representations for image search](https://arxiv.org/pdf/1604.01325.pdf)
* [DeepFace: Closing the Gap to Human-Level Performance in Face Verification](https://www.cs.toronto.edu/~ranzato/publications/taigman_cvpr14.pdf)
* [Learning a Similarity Metric Discriminatively, with Application to Face
Verification
](http://yann.lecun.com/exdb/publis/pdf/chopra-05.pdf)

## Competition track A: Machine learning
Proposal 1: Advertisement CTR prediction

Advertisement CTR prediction is at the core of any advertising campaign. Increasing the accuracy of predictions is critical to improving the effectiveness of advertising.
To help contestants better and more comprehensively predict user engagement with advertising (that is, click probability), this proposal provides anonymous data with more than 40 fields that encompass the full range of user behavior data (including the resident city, active time by mobile phone, and time at which a behavior occurs), basic ad task attributes (including the creative type, asset display form, and advertiser ID), and basic user information (including the age, gender, and device information) in a real paid ad display.
Contestants are required to use algorithms to build CTR prediction models based on the given training data, and submit works based on the given test data set. Area Under Curve (AUC) is adopted to evaluate the works. This proposal aims to find talented individuals to improve CTR prediction algorithms.

Proposal 2: Search ranking prediction

Search ranking is the system for ranking selected documents by the given query-document correlation and displaying the result for users, which is a major challenge for search engines. Increasing the accuracy of rankings is critical to improving the search experience of mobile users.
This proposal provides contestants with training data for building ranking models in a content search scenario, including the correlation label, query ID, document ID, and a total of approximately 100 features across six categories: network graph (including the PageRank indicator), query (including the number of core words and search intention), text matching (including the BM25 score and tightness feature), document (including the content length, title length, and URL length), web classification (including the webpage category, and whether a page is the home page), and time (including the page publishing time).
Contestants are required to build ranking models based on the given training data, and submit works based on the given test data set. Expected Reciprocal Rank (ERR) is adopted to evaluate the works.
This proposal aims to find talented individuals to improve search engine ranking algorithms.

## Competition track B: Computer vision
Digital device image retrieval

Accurate image retrieval is a core technology for shopping by picture taking, and also becomes a hotspot in the academia and industry. This proposal provides a training dataset, including coarse-grained images of digital devices, such as mobile phones, smart wearables, PCs, tablets, speakers, and routers, as well as fine-grained images (for example, images of mobile phones with different appearance) to complete a digital device image retrieval task in a real snap-to-shop scenario. That is, algorithms can be used to find a digital device image in the gallery and return it based on the given query image of the device.
Contestants are required to build and submit models based on the given dataset. The results are then evaluated, according to their top-1 accuracy and mAP@10.
This proposal aims to find talented individuals to improve image retrieval algorithms.

## Scoring rules of competition track A
1. During the preliminary, each team must complete the two proposals and submit works as required.
The maximum score for each proposal is 100 points. During this phase, the total score is weighted by two proposals: 0.8 for the advertising CTR prediction, and 0.2 for the search ranking prediction. 15 teams will be shortlisted for the elite final, as determined by the automatic scoring and qualification review results.
If a team fails to pass the review (for example, due to cheating), all of the teams below it on the leaderboard will automatically move up by one spot.
2. During the elite final, the first prize, second prize, third prize, and honorable mentions will be determined according to the stage B and presentation results.
a. Presentation: Each team will be responsible for preparing presentation materials, and making a presentation for the judging panel.
b. Selection: The judging panel will comprehensively evaluate works according to the automatic scoring and presentation results, and determine the final ranking and award list.

## Scoring rules of competition track B
1. During the preliminary, each team must complete the proposal and submit their work, according to the outlined requirements.
The score a team obtains is weighted by the following two indicators: 0.5 for the top 1 search accuracy rate and 0.5 for mAP@10.
The total size of the model a team submits cannot exceed 500 MB; otherwise, the team cannot obtain any score.
15 teams will be shortlisted for the elite final, as determined by the automatic scoring and qualification review results.
If a team fails to pass the review (for example, due to cheating), all of the teams below it on the leaderboard will automatically move up by one spot.
2. During the elite final, the first prize, second prize, third prize, and honorable mentions will be determined according to the stage B and presentation results.
a. Presentation: Each team will be responsible for preparing presentation materials, and making a presentation for the judging panel.
b. Selection: The judging panel will comprehensively evaluate works according to the automatic scoring and presentation results, and determine the final ranking and award list.
