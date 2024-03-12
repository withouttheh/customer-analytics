# Chocolate Candy Sales Analytics with STP Approach

## Project Overview
In this project, we leverage the STP marketing approach—Segmentation, Targeting, and Positioning—to analyze and formulate effective marketing strategies for chocolate candy bar sales. The focus is primarily on Segmentation and Positioning, as Targeting involves more of marketing and finance expertise than analytical processes.

### What is STP Marketing?
STP marketing is an acronym for Segmentation, Targeting, and Positioning. It is a three-step model that scrutinizes products or services and their communication strategies to specific customer segments. More information can be found [here](https://www.yieldify.com/blog/stp-marketing-model/).

## Data Explanation
The dataset used in this project consists of chocolate candy bar sales data from a local store in the Fast-Moving Consumer Goods (FMCG) market. The data has been modified to ensure customer privacy protection. Two data files are provided: one for segmentation and one for analysis, each with its corresponding data-legend.

### Dataset Files
- Segmentation Data: `data/segmentation data.csv`
- Purchase Data: `data/purchase data.csv`

## Action Plan:
1. **Preprocess Data:**
   - Clean and prepare the data for analysis.
2. **Segmentation Analysis:**
   - Perform clustering analysis using KMeans and PCA on the segmentation data.
   - Export necessary models (scaler, PCA, and KMeans) for later use.
   - Visualize segments and draw insights.
3. **Exploratory Analysis:**
   - Analyze customer proportions, key indicators, and brand choices for each cluster.
   - Explore revenue distribution across brands and clusters.
4. **Predictive Analytics:**
   - Utilize Logistic Regression for predicting Price Elasticity of Purchase Probability.
   - Analyze and visualize price elasticity across all brands and clusters.
   - Calculate cross price elasticity and own price elasticity for selected brands.

## Libraries Used
- numpy
- scipy
- pandas
- scikit-learn (sklearn)
- matplotlib
- seaborn
- pickle

## Results
While a comprehensive overview is provided in the associated Jupyter notebooks, here are some key insights:

### Segmentation Analysis
- Identified and named four distinct clusters: Standard, Fewer-Opportunity, Career-Focused, and Well-Off.
- Utilized PCA to enhance feature separation for more accurate clustering.

### Exploratory Analysis
- Explored customer proportions, average visits, average purchases, and brand choices for each cluster.
- Unveiled insightful marketing strategies based on customer behavior within different segments.

TODO:

- Purchase Data Analytics
  
---

*Note: This readme provides a summary; for a comprehensive understanding, refer to the individual Jupyter notebooks in the repository.*
