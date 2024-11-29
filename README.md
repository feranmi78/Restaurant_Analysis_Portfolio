 # **Restaurant Analysis Portfolio**

**Overview**
This project analyzes a comprehensive restaurant dataset to uncover actionable insights into restaurant operations, customer preferences, and geographic trends. The analysis spans multiple dimensions, including:
City-wise Insights
Price Range Distribution
Ratings and Popularity
Cuisine Combinations
Geospatial Analysis
Sentiment Analysis from Reviews
The project showcases my data cleaning, visualization, geospatial analysis, and text processing skills using Python. I completed this as part of my internship, and it highlights real-world problem-solving with data.

**Key Features**
1. City Analysis
Identifies cities with the most restaurants and the highest average ratings.
2. Price Range Trends
Analyzes restaurant distribution across price ranges and associated services like online delivery and table booking.
3. Popularity and Ratings
Explores the relationship between votes and ratings, highlighting outliers and trends.
4. Cuisine Combinations
Detects popular and high-rated cuisine pairings.
5. Geospatial Analysis
Visualizes restaurant clusters and identifies underserved areas using geospatial tools.
6. Sentiment Analysis
Extracts common keywords from reviews and evaluates the relationship between review length and ratings.

**Insights and Applications**
1. Location Planning
Use geospatial trends to target hotspots or underserved areas for restaurant openings.
2. Customer Feedback
Improve services based on sentiment analysis and keyword trends from reviews.
3. Pricing Strategy
Align pricing with customer expectations and services offered.
4. Cuisine Innovation
Experiment with high-rated cuisine combinations to attract more customers.

**Skills and Tools**
**Languages**
Python
**Libraries**
Pandas
NumPy
Seaborn
Matplotlib
Geopandas
Folium
NLTK

**Techniques**
Data Cleaning
Visualization
Geospatial Analysis
Correlation Analysis
Sentiment Analysis

### **Challenges and Solutions**
1. **Handling Missing and Inconsistent Data**  
   **Challenge**: Missing values and inconsistent data formats in key columns like `City`, `Cuisines`, and `Aggregate Rating`.  
   **Solution**: Used Pandas functions like `dropna()` and data type conversions to clean and preprocess the dataset.

2. **Working with Geospatial Data**  
   **Challenge**: Difficulty accessing deprecated geospatial datasets in GeoPandas and plotting latitude/longitude data accurately.  
     **Solution**: Researched alternative datasets from Natural Earth, integrated them manually and used `folium` for interactive mapping.

3. **Analyzing Multi-Cuisine Combinations**  
   **Challenge**: The `Cuisines` column contained multiple values in a single row (e.g., "North Indian, Chinese"), making grouping and analysis difficult.  
   **Solution**: Split and exploded the `Cuisines` column using Pandas to analyze cuisine combinations effectively.

4. **Visualizing Data Relationships**  
   **Challenge**: Scatterplots for relationships like `Votes` vs. `Aggregate Rating` became cluttered and difficult to interpret.  
   **Solution**: Transitioned to correlation heatmaps, which provided a cleaner and more interpretable visualization of relationships.

5. **Processing Text Data for Sentiment Analysis**  
   **Challenge**: Tokenizing and cleaning text reviews was a new challenge, especially handling stopwords and punctuation.  
  **Solution**: Used `CountVectorizer` and `NLTK` for text preprocessing, enabling keyword extraction and basic sentiment analysis.
