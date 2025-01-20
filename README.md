# 📊 IMDB Movie Data Analysis

![Project Banner](path-to-your-image/banner.png)

## 🌟 Overview
This project analyzes IMDb movie data to extract valuable insights using Python. It leverages powerful libraries like Pandas, Matplotlib, Seaborn, and others to explore trends, correlations, and patterns in the dataset.

### **Key Features**
- Data preprocessing and cleaning for missing or inconsistent entries.
- Exploratory Data Analysis (EDA) with descriptive statistics and visualizations.
- Insights into genres, revenue, ratings, and release trends.
- Advanced visualizations showcasing trends and relationships.

---

## 📂 Dataset
- **Source**: [IMDb Movie Data](https://www.kaggle.com/datasets/anandshaw2001/imdb-data)
- **Size**: ~1,048,575 movies
- **Attributes**:
  - `Title`: Name of the movie
  - `Genre`: Movie genre(s)
  - `Director`: Movie director(s)
  - `Vote_average`: IMDb user rating
  - `Vote_count`: Number of IMDb votes
  - `Release Date`: Date of release
  - `Runtime`: Movie runtime (minutes)
  - `Id` : Id in the dataset
  - `Status` : Released or to be released
  - `Revenue`: Money generated
  - `Adult`: Is it for adults
  - `Budget`: Amount spent on production
  - `Imdb_id`: Movie ID
  - `Original_language`: Language spoken in the movie
       '

---

## 🔍 Insights Gained

### Key Questions Answered:
1. **Which genres are most popular?**
2. **What are the highest-rated movies?**
3. **How do IMDb ratings vary over the years?**
4. **Are runtime and ratings correlated?**
5. **How do the runtime vary over the year?**
6. **What are the Top 10 most voted movies?**
7. **Does number of votes correlate to the IMDB rating?**

---

## 📈 Visualizations
Here are some sample visualizations generated during the analysis:

### 1.Top 10 Most Voted Movies
![Top 10 most voted movies](https://github.com/saifalibaig/IMDB-Movie-Data-Analysis-Using-Python/blob/main/assets.PNG)

### 2. Trend In Movie Runtimes 
![Trend In Movie Runtimes ](https://github.com/saifalibaig/IMDB-Movie-Data-Analysis-Using-Python/blob/main/assets1.PNG)

### 3. Trend In IMDB Rating
![Trend In IMDB Rating](https://github.com/saifalibaig/IMDB-Movie-Data-Analysis-Using-Python/blob/7f4db3fe60caae3a202c007cf481434dd3a93982/assets2.PNG)

---

## 📋 Summary & Conclusion

### Insights:
After analyzing the **1 million+ records** in the dataset, we arrived at the following conclusions:

1. The dataset contains no data related to the **director/directors** of the movies that have been released.
2. The dataset includes **many outliers**, such as release dates extending to the year **2099**.
3. There are over **13,000+ combined genres** with a rating of **10**.
4. The **runtime of movies has increased** over the past decades at a constant rate.
5. There is **no correlation** between runtime and IMDb ratings.
6. The **vote count and IMDb ratings** show a **weak positive correlation**.
7. The **maximum revenue generated** by a movie in the dataset was **$4,999,999,999**.

