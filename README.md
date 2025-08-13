# Data Science Portfolio - Comprehensive Analysis & Machine Learning Projects

This repository contains a diverse collection of data science projects spanning customer analytics, text analysis, real estate insights, recommendation systems, and sentiment analysis. Each project demonstrates practical applications of data science techniques including exploratory data analysis (EDA), machine learning, and natural language processing (NLP).

## 📁 Project Structure

### 1. **Client Database of Furniture Store** 📊
**Focus**: Customer Analytics & Business Intelligence

**Key Components**:
- **Datasets**: 5 CSV files (customers, products, orders, ratings, orders)
- **Analysis**: Comprehensive furniture store performance analysis
- **Techniques**: RFM analysis, customer segmentation, product performance metrics

**Insights Generated**:
- Top-performing products by revenue and units sold
- Customer lifetime value analysis
- Last month's top clients
- Product review analysis and ratings distribution
- RFM (Recency, Frequency, Monetary) customer segmentation

---

### 2. **EDA of Marvel Comics - RegEx** 🦸‍♂️
**Focus**: Text Mining & Pattern Recognition

**Key Components**:
- **Dataset**: Marvel Comics database with comic names, issues, writers, and descriptions
- **Techniques**: Regular expressions, text preprocessing, frequency analysis

**Analysis Highlights**:
- Most frequently used words/phrases in comic titles and descriptions
- Top prolific writers based on comic count
- Character/hero frequency analysis using regex patterns
- Text mining insights from comic descriptions
- Pattern recognition in comic metadata

---

### 3. **EDA of Properties** 🏠
**Focus**: Real Estate Market Analysis

**Key Components**:
- **Dataset**: Property sales data with size, location, and pricing information
- **Analysis**: Properties analysis notebook with comprehensive EDA

**Key Findings**:
- Property size vs. sale price correlation analysis
- Location-based price distribution
- Outlier detection in property pricing
- Market trend visualization
- Statistical insights into real estate patterns

---

### 4. **Movie Recommender - Cosine Vectors** 🎬
**Focus**: Recommendation Systems & NLP

**Key Components**:
- **Datasets**: Movie metadata and user ratings
- **Technique**: Content-based filtering using TF-IDF and cosine similarity

**System Features**:
- TF-IDF vectorization of movie descriptions, genres, and taglines
- Cosine similarity-based movie recommendations
- Content-based filtering without collaborative data
- Scalable recommendation engine for movie suggestions

---

### 5. **Sentiment Analysis - Naive Bayes of Reviews & Ratings** 💬
**Focus**: Sentiment Classification & NLP

**Key Components**:
- **Dataset**: User reviews and ratings for courses offered by 365
- **Techniques**: Naive Bayes classification, Bag-of-Words, text preprocessing
- **Goal**: Predict sentiment polarity (positive/negative) from textual reviews and numerical ratings

**Analysis & Model Workflow**:
- Data preprocessing: Tokenization, stopword removal, lowercase normalization
- Feature extraction: Bag-of-Words representation using `CountVectorizer`
- Model: Multinomial Naive Bayes for text classification
- Evaluation: Accuracy, precision, recall, and confusion matrix

**Insights Generated**:
- Correlation between ratings and sentiment polarity
- Most frequent keywords in positive vs. negative reviews
- Sentiment distribution across different courses

---

## 🛠️ Technologies & Libraries Used

### Core Libraries:
- **pandas** - Data manipulation and analysis  
- **numpy** - Numerical computing  
- **matplotlib** - Data visualization  
- **seaborn** - Statistical data visualization  
- **scikit-learn** - Machine learning algorithms  

### Specialized Libraries:
- **re** - Regular expressions for text processing  
- **nltk** - Text preprocessing and tokenization  
- **sklearn.feature_extraction.text** - TF-IDF & CountVectorizer  
- **sklearn.metrics.pairwise** - Cosine similarity computation  

---

## 📈 Key Data Science Techniques Demonstrated

1. **Exploratory Data Analysis (EDA)**
   - Statistical summary and distribution analysis
   - Correlation analysis and relationship discovery
   - Outlier detection and handling

2. **Customer Analytics**
   - RFM segmentation for customer value analysis
   - Purchase behavior patterns
   - Product performance metrics

3. **Text Mining & NLP**
   - Regex pattern matching
   - TF-IDF and Bag-of-Words vectorization
   - Frequency analysis and keyword extraction

4. **Machine Learning**
   - Naive Bayes text classification
   - Content-based recommendation systems
   - Similarity-based matching algorithms

5. **Data Visualization**
   - Distribution plots and histograms
   - Box plots for outlier visualization
   - Scatter plots for relationship analysis
   - Heatmaps for correlation matrices

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn nltk
