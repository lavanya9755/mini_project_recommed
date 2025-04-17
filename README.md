# Python Code for Coffee Shop Chatbot
This folder contains the Python code and notebooks necessary for building and deploying the chatbot system for the coffee shop app. The code is organized into several components, each serving a specific function within the overall project.

## 📂 Directory Structure
```bash
├── python_code
│   ├── API/               # Chatbot API for agent-based system
│   ├── dataset/           # Dataset for training recommendation engine    
│   ├── products/          # Product data (names, prices, descriptions, images)   
│   ├── build_vector_database.ipynb             # Builds vector database for RAG model   
│   ├── firebase_uploader.ipynb                 # Uploads products to Firebase    
│   ├── recommendation_engine_training.ipynb    # Trains recommendation engine 
```
## 📚 Components Overview
### API
This folder contains the code for the API that handles requests to the chatbot agent system. It serves as the bridge between the React Native app and the backend functionality.
### Dataset
This folder includes the downloaded dataset from Kaggle used for training the recommendation engine. It serves as the foundation for generating personalized product suggestions.
### Products
Contains product information utilized in the app, including names, prices, descriptions, and images. This data is essential for displaying products within the app and for the chatbot's responses.
### Notebooks
#### build_vector_database.ipynb: 
A Jupyter notebook that constructs the vector database for the Retrieval-Augmented Generation (RAG) model, facilitating efficient data retrieval for the chatbot.
#### firebase_uploader.ipynb: 
A Jupyter notebook that uploads product data to Firebase, enabling the React Native app to fetch this data dynamically.
#### recommendation_engine_training.ipynb: 
A Jupyter notebook that trains the market basket analysis recommendation model, which is used by the recommendation agent to provide personalized product suggestions.
