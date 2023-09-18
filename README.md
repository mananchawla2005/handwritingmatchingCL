# Signature Matching using Contrastive Learning

- Colab Link [Click Here](https://colab.research.google.com/drive/1aOinxHLbUtqSOjeamu7NrCsplyMhnmlI?usp=sharing)
- Dataset Used: ICDAR 
# Model

This repository explores the task of signature analysis and matching using the power of contrastive learning and Siamese networks. It helps to provide a robust solution for comparing and matching handwriting samples.
- <b>Siamese Network:</b> <br>
![image](https://github.com/mananchawla2005/handwritingmatchingCL/assets/42414965/a4e49fd0-2365-4be6-b763-eed4dd4d93b6)

- <b>Contrastive Loss:</b>
  In the below image, Dw represents the euclidian distance between two pairs of images. Y is an indicator function which is 1 for positive pairs and 0 for dissimilar pairs. For the positive part, we just calculate the euclidian distance whereas for the negative part, there is a slight change. As it is being calculate for negative pairs, there comes a minus sign in front of it and we use a small number m to set the threshold value. The loss function in all is given below:
![image](https://github.com/mananchawla2005/handwritingmatchingCL/assets/42414965/3e0f74d7-5ec4-4502-9bd0-c18fe0793010)
# Results: 
![faafcfc5-4877-40ce-8591-923238b2e8dd](https://github.com/mananchawla2005/handwritingmatchingCL/assets/42414965/05c713bb-75f9-45e3-bc07-147247d17e41)
![def2f0a0-2e99-42a3-b93e-00e65430768a](https://github.com/mananchawla2005/handwritingmatchingCL/assets/42414965/dd48d51c-c642-4fff-ada4-f54414eb5232)

