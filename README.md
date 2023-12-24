
# Suicidal Ideation Detection using Natural Language Processing

Suicidal ideation is used to describe a person who contemplates and wishes to commit suicide. Suicide ideation is one of the primary symptoms for psychiatric diagnostic and with the surge of Covid-19, stressful work environment and academic pressure has caused a surge in the number of depression and SI cases in mental health hotlines. An early detection of SI should be implemented so that people in need could potentially get the help they need in their life and gain necessary supports. This project explores the use of deep learning methods via Pytorch to detect suicidal ideation in a dataset scrapped from "SuicideWatch" and "Depression" subreddit posts.




## Project Objectives
1. To develop a deep learning model to predict suicidal ideation based on Reddit posts
2. To evaluate the deep learning model


## Problems faced during development

torch.legacy.data has been depreciated from latest version of Pytorch, making it difficult to pre-process the text data into the format required to feed into the Pytorch LSTM models. Fortunately, thanks to Anupam Sharma with the tutorial, https://pytorch.org/tutorials/beginner/torchtext_custom_dataset_tutorial.html, I was able to pre-process the data accordingly.






## Acknowledgements

 - [Dataset by NIKHILESWAR KOMATI on Kaggle](https://www.kaggle.com/datasets/nikhileswarkomati/suicide-watch/data)
 - [Tutorial on Text Preprocessing](https://pytorch.org/tutorials/beginner/torchtext_custom_dataset_tutorial.html)
 - [Architecture adapted from ARUNMOHAN_003's notebook on Kaggle](https://www.kaggle.com/code/arunmohan003/sentiment-analysis-using-lstm-pytorch)
 - [Image](https://innerbody.imgix.net/suicide-prevention-guide-header.jpeg?auto=format&ixlib=react-9.5.4&w=826&dpr=1&q=75) 

Thank you. This project is to be improved as this is my first attempt in Natural Language Processing



![Depressed Girl](https://innerbody.imgix.net/suicide-prevention-guide-header.jpeg?auto=format&ixlib=react-9.5.4&w=826&dpr=1&q=75)

## Problems faced during development

torch.legacy.data has been depreciated from latest version of Pytorch, making it difficult to pre-process the text data into the format required to feed into the Pytorch LSTM models. Fortunately, thanks to Anupam Sharma with the tutorial, https://pytorch.org/tutorials/beginner/torchtext_custom_dataset_tutorial.html, I was able to pre-process the data accordingly.





