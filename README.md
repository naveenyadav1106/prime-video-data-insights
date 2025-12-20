# Amazon Prime Video Content Analysis

## Project Description
This project explores Amazon Prime Video titles and credits to extract actionable insights about content diversity, trends over time, ratings, popularity, and cast/crew contributions. The analysis identifies dominant genres, examines the growth of the content library, and highlights the most prominent titles, actors, and directors.

## Repository Structure
- `/notebook/Amazon_Prime_Video_Content_Analysis.ipynb` — The main Colab notebook containing all analyses, visualizations, and insights.  
- `/data/titles.csv` — Dataset with detailed information about Amazon Prime Video titles.  
- `/data/credits.csv` — Dataset containing cast and director information.  
- `/visuals/` — Folder containing exported Plotly HTML files and optional PNG images of key plots.

## Libraries Used
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Plotly  

## Key Insights
- **Content Distribution:** Movies constitute the majority of titles (~86%), while TV Shows are fewer, indicating potential for expanding series content.  
- **Genre Trends:** Drama and Comedy dominate both Movies and TV Shows, while other genres like Action, Romance, and Animation present opportunities for diversification.  
- **Library Growth:** The number of titles released per year has increased steadily, peaking at 856 in 2021, reflecting Amazon Prime’s content expansion strategy.  
- **Cast & Crew:** Certain actors and directors have a high number of titles, indicating prolific contributors that can influence marketing and content strategy.  
- **Ratings & Popularity:** Most titles cluster around moderate IMDb scores and TMDB popularity, but outliers such as classics and highly acclaimed titles highlight evergreen content that can be promoted for engagement.
