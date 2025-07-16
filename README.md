# Video Game Sales & Market Analysis

This project explores trends in global video game sales, platform performance, and genre popularity using historical data. I was tasked with uncovering which platforms and genres dominated the market across North America, Europe, and Japan, and how factors like critic scores and user reviews influence game success.

I used Python to clean, analyze, and visualize the data, and conducted hypothesis testing to compare user ratings across platforms and genres.

---

## Key Insights

- Action and Shooter games are consistently the highest-performing genres in North America and Europe, while RPGs dominate in Japan.
- Critic scores are moderately correlated with sales across most platforms, while user scores show weaker or inconsistent relationships.
- Platforms such as PS4, Xbox 360, and PS3 had the most stable sales before 2016, but several others showed clear signs of decline.
- ESRB ratings show regional differences in impact — with “M” and “E” ratings leading in NA/EU, and “E” preferred in Japan.

---

## Tools Used

- Python  
- Pandas  
- Seaborn  
- Matplotlib  
- SciPy (t-tests, Levene's and Bartlett’s tests)  
- Jupyter Notebook  

---

## Dataset

The dataset includes over 16,000 video games with attributes such as:
- Platform  
- Genre  
- Year of Release  
- Critic Score  
- User Score  
- ESRB Rating  
- Sales in North America, Europe, Japan, and other regions

---

## Notebook

You can view the full analysis in the Jupyter notebook:  
**[video_game_sales_analysis.ipynb](video_game_sales_analysis.ipynb)**

Or open it directly in Colab:  
[Open in Google Colab](https://colab.research.google.com/github/joecre/video-game-sales-analysis/blob/main/video_game_sales_analysis.ipynb)

---

## Summary

This analysis provides data-driven insights that could be valuable for game publishers, marketers, or investors evaluating what types of games to prioritize in specific regions and how review sentiment may factor into performance.
