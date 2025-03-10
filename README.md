# AI-powered-Resume-Screening-and-Ranking-System
Introduction:

The AI Resume Screening & Candidate Ranking System is a machine learning-based tool designed to automate and streamline the recruitment process. The system evaluates resumes by comparing them with a given job description and ranks candidates based on relevance. It employs TF-IDF (Term Frequency-Inverse Document Frequency) and Cosine Similarity to determine the most suitable candidates.

Features:

-Automated Resume Parsing: Extracts text from PDF resumes.

-Job Description Input: Allows users to enter a job description.

-Feature Extraction: Uses TF-IDF for vectorization.

-Candidate Ranking: Uses Cosine Similarity to rank resumes based on relevance.

-User-Friendly Interface: Built using Streamlit for easy interaction.

Usage:

-Enter Job Description: Input the job description into the text box.

-Upload Resumes: Upload PDF files of candidate resumes.

-Processing: The system extracts text, processes it, and compares it with the job description.

-Ranking: Candidates are ranked based on their similarity scores.

-View Results: The system displays the ranking with scores.

System Design:

The system follows these steps:

-Document Parsing: Extracts and cleans text from resumes.

-Preprocessing: Removes stopwords and unnecessary characters.

-Feature Extraction: Converts text into numerical vectors using TF-IDF.

-Similarity Computation: Uses Cosine Similarity to measure relevance.

-Ranking & Output: Displays top-matching resumes in descending order.

Technologies Used:

-Programming Language: Python

-Framework: Streamlit

-Libraries: PyPDF2, pandas, scikit-learn
