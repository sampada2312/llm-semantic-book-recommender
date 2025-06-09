# Book Recommender System
A book recommendation engine leveraging advanced NLP, sentiment analysis, and vector similarity search. This project delivers personalized book suggestions by analyzing user preferences, book descriptions, and emotional tone.

# Project Overview
This recommender system allows users to find books based on their interests, preferred tone, and category (Fiction, Nonfiction, etc.). The system uses a combination of sentiment analysis, vector embeddings, and LLMs to deliver highly relevant recommendations.

# Key Features
1. Data Preprocessing & Exploration: Comprehensive cleaning, categorization, and analysis of book metadata.
2. Sentiment & Emotion Analysis: Determines the emotional tone of desired books using a fine-tuned model.
3. Vector Similarity Search: Utilizes vector embeddings to find books with similar content and tone.
4. Category-Based Filtering: Offers refined results by book categories (Fiction, Nonfiction, Children's Fiction, etc.).
5. LLM & Hugging Face API Integration: Uses state-of-the-art NLP models for text classification and embedding.
6. Gradio Dashboard: Interactive web interface for easy user input and visualization of recommendations.

# Technologies Used
Python

Pandas -> Data manipulation and exploration

LangChain -> Vector embeddings and similarity search

Hugging Face Transformers -> Sentiment analysis, zero-shot classification

Chroma DB -> Vector database for fast similarity search

Gradio -> Interactive web dashboard

Jupyter Notebook -> Data exploration and prototyping

# How It Works
1. User Input: The user provides a query or selects preferences (e.g., "A book to teach children about nature," "happy tone," "Nonfiction").
2. Sentiment & Category Analysis: The system analyzes the query for sentiment and category using Hugging Face models.
3. Vector Search: The system retrieves book embeddings and finds the most similar books using Chroma DB.
4. Recommendation: The system combines sentiment, category, and vector similarity to deliver a list of relevant books.
5. Dashboard Display: Results are displayed in an interactive Gradio dashboard for easy exploration.

# Conclusion
This book recommender system demonstrates how modern NLP techniques and machine learning can be leveraged to deliver highly personalized recommendations. By integrating sentiment analysis, vector similarity search, and LLMs, the system goes beyond traditional keyword matching to understand both the content and emotional tone of books, as well as user preferences. The use of Hugging Face for zero-shot classification and embeddings, along with Chroma DB for efficient vector storage and retrieval, showcases a scalable and modular architecture.
Overall, this project exemplifies a data-driven, user-centric approach to recommendation systems, combining NLP, data engineering, and interactive design to create an application in the field of machine learning.

# Demo Video
A video demonstrating the working of the recommender system is attached below. Watch it to see the system in action!

https://github.com/user-attachments/assets/61a46f42-5cf8-4fe0-b99a-61f7bb614c0c




