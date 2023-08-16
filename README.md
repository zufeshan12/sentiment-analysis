# sentiment-analysis : comparative analysis using VADER, AWS Comprehend & roBERTa
This project demonstrates a complete comparative study of different NLP text classifiers for sentiment analysis. The dataset is based on Amazon food reviews collected from Kaggle.

How <b>VADER</b> which is a pretrained model from NLTK trained on social media texts analyzes reviews and scores them as positive , negative or neutral and how <b>AWS's Comprehend</b>, an NLP service to perform sentiment classification over variety of data , projects labels such as positive, negative, neutral and mixed over 500 food reviews given by different customers. 
The latest pretrained roberta model from Hugging Face library has been used to analyze sentiments across 500 food reviews and conclusively , Vader and Roberta gave out similar results. 
These models however fail to capture sarcasm, mockery and puns . <i>Guess we still have a long way to go!</i>

<img width="501" alt="Screenshot 2023-08-16 at 3 48 49 PM" src="https://github.com/zufeshan12/sentiment-analysis/assets/139018759/54eba932-b992-400d-9090-39f02105f3f1">
<img width="507" alt="Screenshot 2023-08-16 at 3 49 06 PM" src="https://github.com/zufeshan12/sentiment-analysis/assets/139018759/dd559216-ac7a-47bf-81e0-c49b7c3b658e">
<img width="502" alt="Screenshot 2023-08-16 at 3 49 21 PM" src="https://github.com/zufeshan12/sentiment-analysis/assets/139018759/0a4c5a05-55aa-421e-a4ff-3a7d2019ab57">
<img width="828" alt="Screenshot 2023-08-16 at 3 49 58 PM" src="https://github.com/zufeshan12/sentiment-analysis/assets/139018759/48fd3ad3-ba86-49b6-8f50-810ceb5dd8c0">
