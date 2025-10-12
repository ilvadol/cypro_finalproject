# cypro_pyproject
Final Project for the Data Analytics Course at CyberPro Israel
## Collaborators:
Ilia Oleinikov

Svetlana Saveleva

## 📘 Introduction

This project analyzes global video game sales data and Metacritic metascores to identify trends and strategic insights for game development in the modern market.  
Using data from **1996–2020**, our goal is to answer the question:

> _What type of game should a studio develop today to maximize both critical reception and commercial success?_

### Datasets
- **`vgsales.csv`** — Global and regional video game sales by platform, genre, publisher, and region  
- **`metacritic.csv`** — Game Metascores from Metacritic
For more information about the datasets, including sources and descriptions, please refer to the `README.md` file located in the `dataset` folder of this repository.

---

## 🧹 Data Preparation

1. **Data Import**  
   - Both datasets were imported into **Microsoft Power BI** as CSV files.

2. **Data Cleaning & Transformation**  
   - All data preparation (cleaning, transformation, type conversions, and merging) was performed **exclusively within Power BI**, without external tools or scripts.  
   - The goal was to validate Power BI’s capability to handle an end-to-end data analytics workflow on its own.  
   - Steps included:
     - Standardizing column names and data types  
     - Removing duplicates and handling missing values  
     - Creating relationships between datasets  
     - Merging on `Game Name` and unifying genre and platform categories  

3. **Data Modeling**  
   - Combined datasets into a unified model linking sales and metascore data  
   - Added calculated columns and measures (e.g., total global sales, average metascore by genre/year/platform)

> 🧩 **Project Challenge:**  
> The central challenge of this project was to perform the entire data cleaning, transformation, and visualization pipeline **using only Power BI’s native toolset**.  
> No external preprocessing (e.g., Python or Excel) was used — demonstrating that complex data preparation and analytics can be achieved within a single BI platform.

---

## 📊 Analysis & Key Methods

The analysis explored several perspectives to uncover insights about the gaming industry:

- **Annual game releases** by year, genre, and platform  
- **Top performers** by sales and metascore  
- **Correlations** between critical ratings and commercial success  
- **Publisher dominance** over time  

### 1. Release Trends (1996–2020)
Analyzing yearly release counts by genre and platform revealed:
- Shifting genre popularity over decades  
- Peaks and declines for each genre  
- Potential opportunities in genres with strong ratings but fewer recent releases  

### 2. Top Performers
- **Top 5 Publishers by Global Sales**
- **Top 5 Games by Global Sales**
- **Top 10 Games by Global Sales vs. Metascore**

This comparison highlights that **the most profitable games are not always the most critically acclaimed**, encouraging studios to balance commercial and artistic goals.

### 3. Correlation: Metascore vs. Global Sales
A key visualization explored the correlation between sales and critical ratings across genres and platforms, helping identify which combinations historically achieved both critical and financial success.

---

## 📈 Visualization

All results were visualized in a **Power BI interactive dashboard**, featuring:
- Filters for **year, genre, and platform**
- Dynamic visualizations for **sales and rating trends**
- Comparative tables for **top games and publishers**
- Scatterplots showing **Metascore vs. Global Sales correlation**

---

## 💡 Insights

### Release Dynamics by Genre
| Genre | Notable Trend |
|-------|----------------|
| **Action** | Consistently dominant — 200+ releases annually |
| **Adventure** | Peaked around 2010, declined post-2015 (~170 titles/year) |
| **Fighting** | Peaked before 2010 (<60 titles/year) |
| **Miscellaneous** | Strong 2008–2011 output (180–200 titles/year) |
| **Platform** | Peak 2000–2010 (<50 titles/year) |
| **Puzzle** | Peak 2007–2009 (<80 titles/year) |
| **Racing** | Stable (50–60 per year), peak 2003 (109) |
| **RPG** | High output 2003–2015 (~100 per year) |
| **Shooter** | Strong growth 2002–2015+ (~80 per year) |
| **Simulation** | High 2005–2012 (~100 per year), minimal outside that period |
| **Sports** | Constantly strong (~100+ per year) |
| **Strategy** | Steady (~50 per year), peak 2005–2012 |

### Top 5 Best-Selling Games (All Time)
1. **Wii Sports**  
2. **Grand Theft Auto V**  
3. **Mario Kart Wii**  
4. **Wii Sports Resort**  
5. **Pokémon Red / Blue**

- From 2010–2020, **Xbox 360** had the highest cumulative sales, led by *GTA V* and *Call of Duty*.  
- Across all platforms, **Action** and **Shooter** genres consistently dominated revenue.  
- Games like *Wii Sports*, *GTA V*, and *Call of Duty* appeared in multiple top lists, reflecting broad commercial success.

### Correlation Highlights
- **Action** and **Shooter** titles deliver the highest revenue potential.  
- Within **Action**, games like *GTA V*, *Red Dead Redemption*, *Batman: Arkham Asylum*, and *The Last of Us* excel in both sales and ratings.  
- **Shooters**, while highly profitable, tend to rank lower in average metascore.  
- Critically acclaimed titles such as *Portal*, *BioShock*, *Uncharted*, *Far Cry*, and *Overwatch* demonstrate opportunities in blending creativity with mainstream appeal.  
- The **Wii platform’s** success illustrates that accessibility and casual appeal can outperform technical complexity (*Wii Sports* was bundled with the console).

---

## ✅ Hypothesis Testing

**Hypothesis:**  
> Genres with consistent releases and strong metascores correlate with higher long-term sales potential.

**Confirmed:**  
- Action and Adventure genres maintain long-term profitability.  
- Shooter games dominate short-term sales but show lower critical reception.  
- Cross-genre hybrids (Action + Narrative depth) represent the most sustainable development direction.

---

## 📚 Conclusions & Recommendations

1. **Focus on Action–Adventure hybrids** with narrative depth and high replay value.  
2. **Blend shooter mechanics** creatively without relying solely on formulaic design.  
3. **Prioritize multi-platform releases**, especially Xbox and PlayStation ecosystems.  
4. **Revive high-rated but underproduced genres** (e.g., Puzzle, Platform) to capture nostalgia-driven audiences.  
5. **Target both quality and mass appeal:** games that appear in both *Top Sales* and *Top Metascore* lists (e.g., *GTA V*) prove that critical and financial success can coexist.

---

## 🧠 Tech Stack

- **Microsoft Power BI**  
  All data loading, transformation, analysis, and visualization were performed natively within Power BI without external preprocessing tools.