# Recommendations_Book
Recommendations_Book

## Project Description
The Recommendations_Book project is a book recommendation system designed to enhance the process of selecting literature for users based on analyzing reader preferences and characteristics of books themselves. The primary goal of the project is to create personalized recommendations that help users find interesting and suitable books more quickly and efficiently.

<img src="https://abrakadabra.fun/uploads/posts/2021-12/1640424262_31-abrakadabra-fun-p-kniga-raskritaya-vektor-31.png">

## Development Stages:

***Stage 1*: Data Collection and Preparation**
* Collected data about books including genres, authors, ratings, and descriptions.
* Created a user database with information about each reader's preferences.

***Stage 2*: Data Analysis**
* Conducted preliminary analysis of the data to identify patterns and trends among user preferences.
* Used Natural Language Processing (NLP) methods such as TF-IDF and word embeddings to represent text and evaluate similarity between books.

***Stage 3*: Developing the Recommendation Model**
* Implemented collaborative filtering to recommend books based on similar user's behavior.
* Developed a hybrid model combining content-based filters and matrix factorization to improve recommendation accuracy.

***Stage 4*: Quality Evaluation**
* Evaluated the model using metrics like MAP, Precision, and Recall.
* Compared results from different approaches to recommendations.

## Tools and Technologies
For implementing the project, the following tools and libraries were used in Python:
Pandas, NumPy Scikit-Learn, Surprise, LightFM


Project structure
```
recommendation_book/
│
├── data                  
│   └── *.csv 
├── img                  
│   └── *.png                      
├── book_rec.ipynb           
├── .gitignore              
├── README.md               
└── requirements.txt         
```

## General links
* ***[solution](https://github.com/esta1d/Recommendations_Book/blob/main/book_rec.ipynb)***
* ***[libraries](https://github.com/esta1d/Recommendations_Book/blob/main/requirements.txt)***


## Conclusion
The Recommendations_Book project successfully demonstrated the possibility of creating an effective book recommendation system that enhances the reading experience for users. Machine learning techniques significantly improved recommendation accuracy, which was confirmed by positive reviews from testers. Future steps include expanding the dataset and improving model performance for larger volumes of data.