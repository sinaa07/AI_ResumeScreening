# AI Resume Filtering

## 📌 Overview
This AI-powered resume filtering tool automates the initial screening process for hiring by filtering out non-matching resumes based on job descriptions. It utilizes machine learning and natural language processing (NLP) techniques to match skills, experience, and qualifications efficiently.

## ✨ Features
- Filters resumes based on job description criteria.
- Uses cosine similarity on embeddings (TF-IDF, BERT, or Google AI Studio) to determine relevance.
- Optimized with prompt engineering for accurate filtering.
- No ranking, only filtering out non-matching resumes.
- Free approach; does not rely on paid APIs like OpenAI's text-embedding-ada-002.
- Future enhancement: Employee sentiment analysis.

## 🛠 Tech Stack
- **Backend**: Python
- **Machine Learning**: TF-IDF, BERT, Google AI Studio
- **Data Processing**: NumPy, pandas
- **Database**: MySQL (for storing processed resumes and job descriptions)
- **Deployment**:  Google AI Studio

## ⚙️ How It Works
1. **Job Description Input**: The system accepts a job description (JD) as input.
2. **Resume Preprocessing**: Resumes are converted into text format, cleaned, and tokenized.
3. **Feature Extraction**: NLP models generate embeddings to extract key skills and experience.
4. **Similarity Matching**: The system calculates the cosine similarity between JDs and resumes.
5. **Filtering**: Resumes that do not meet a predefined similarity threshold are filtered out.

## 🔮 Future Enhancements
- Improve accuracy with advanced embeddings and fine-tuning.
- Implement real-time feedback for model improvement.
- Add employee sentiment analysis to evaluate cultural fit.

## License
This project is licensed under the MIT License.

