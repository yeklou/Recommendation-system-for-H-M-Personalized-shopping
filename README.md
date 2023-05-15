# Project Topic: Recommendation System for H&M Personalized Shopping

This is a recommendation system for H&M personalized shopping built using collaborative filtering algorithms. 
The system is designed to provide personalized product recommendations to users based on their browsing history and shopping behavior.

## Getting Started

To get started with this recommendation system, follow the instructions below:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/username/Recommendation-system-for-H-M-Personalized-shopping.git
   ```

2. Install the necessary packages:

   ```
   pip install -r requirements.txt
   ```
3. Download the datasets

   ```
   https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations
   ```  
   
5. Run the recommendation system:
  5.1. Click on any of the links below and select Google Colaboratory option to execute the Code
  
      1 Code Notebook- EDA, Content-Filter Based Recommendation 
      ```
      https://drive.google.com/file/d/1t65rv8rTuxTdPZKmlRNA6LdmKy1PbhEa/view?usp=share_link
      ```
   
      2 Code Notebook- Collaborative-Filter Based Recommendation Matrix Factorization, Feature Engineering 
      ```
      https://drive.google.com/file/d/17QfOi5uJaukzRq0cD3qJgMUh5AiEZFOG/view?usp=share_link
      ```
      
      3 Code Notebook- Collaborative-filter Recommendation Surprise, Feature Engineering 
      ```
      https://drive.google.com/file/d/17fyE1RLLTMFPAMbRvJ-OMCgikOG0Nnvr/view?usp=share_link 
      ```
   
   5.2. Execute code in terminal using prompt command
   
    ```
   jupyter notebook EDA.ipynb
   jupyter notebook MLGrouProject.ipynb
   jupyter notebook H&M-CollaborativeFilteringModeling_Final.ipynb
    ```


## How it Works

The recommendation system uses collaborative filtering algorithms to provide personalized recommendations to users. 
When a user browses a product, the system stores the product ID in a database along with the user's ID. 
The system then uses this data to build a user-item matrix, where each row represents a user and each column represents a product. 

The system then applies collaborative filtering algorithms to this user-item matrix to predict which products a user is most 
likely to purchase based on their browsing and shopping history. The top N recommended products are then displayed to the user.

## Contributing

If you would like to contribute to this project, please follow the steps below:

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make your changes and test them
4. Submit a pull request

## Code availability

3.1 Code Notebook- EDA, Content-Filter Based Recommendation 
https://drive.google.com/file/d/1t65rv8rTuxTdPZKmlRNA6LdmKy1PbhEa/view?usp=share_link

3.2 Code Notebook- Collaborative-Filter Based Recommendation Matrix Factorization, Feature Engineering 
https://drive.google.com/file/d/17QfOi5uJaukzRq0cD3qJgMUh5AiEZFOG/view?usp=share_link

3.3 Code Notebook- Collaborative-filter Recommendation Surprise, Feature Engineering 
https://drive.google.com/file/d/17fyE1RLLTMFPAMbRvJ-OMCgikOG0Nnvr/view?usp=share_link 

3.4 Kaggle Competition - 
https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations
