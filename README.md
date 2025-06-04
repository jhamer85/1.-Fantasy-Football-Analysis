# 🏈 Fantasy Football Projects  
Self-directed fantasy football projects combining data analysis, coding, and custom tools.

This repository showcases personal projects I created to combine my passion for fantasy football with data analytics and spreadsheet modeling. Each project reflects hands-on learning and practical problem-solving with real-world application.

---

## 📈 Project 1: Fantasy Football Auction Draft Tool (Excel)

🎯 **Goal:**  
Design a practical, real-time budget tracker and team builder for in-person auction league drafts.

🧠 **What It Does:**  
- Tracks budget per team with real-time updates  
- VLOOKUP integration to match player data across worksheets  
- Built-in formulas to calculate remaining money in the auction

🛠️ **Tools Used:**  
- Microsoft Excel  
- VLOOKUP
- conditional formatting
- dynamic formulas

🚧 **Status:**  
Complete and available for review. Updated tweaks as I learn new code and think of improvements.

📎 **Why It Matters:**  
Auction drafts can get chaotic. This tool brings structure, strategy, and sanity to a high-stakes environment.

---

## 📊 Project 2: 2024 Tight End Scoring Box Plot (Python)

🎯 **Goal:**  
Explore scoring trends for Tight Ends in the 2024 season using a box plot to identify outliers and consistency.

🧠 **What I Did:**  
- Collected scoring data from fantasypros.com
- Cleaned and structured dataset using Pandas  
- Created custom box plots with Matplotlib  
- Interpreted data for positional tiering and player evaluation

🛠️ **Tools Used:**  
- Python  
- Pandas
- Matplotlib

🚧 **Status:**  
Complete and available for review. Potential future expansion to WR and RB positions.

📎 **Conclusions:**
- Njoku was a strong value last year.
- I was surprised by LaPorta's lack of ceiling.
- Several popular TEs, such as LaPorta, Kraft, Freirermuth, etc., provided steady weekly points but were not difference makers at the position.
  
---

## 📈 Project 3: 2025 Rookie ADP Trends (Excel + Python)

🎯 **Goal:**
-Track and visualize how rookie players' Average Draft Position (ADP) changes over time.

🧠 **What I Did:**
- Collected ADP data from multiple time points via DynastyDataLab.com
- Used Python to merge the data tables into a unified dataset by player
- Imported the dataset into Excel to build trend visualizations
- Created sparklines to show each player's ADP trajectory over time
- Applied formatting to invert the Y-axis appearance (so lower ADP values appear higher on the graph)
- Color-coded sparklines to reflect whether a player's ADP was trending up or down

🛠️ **Tools Used:**
- Python
- Pandas
- Microsoft Excel
- sparklines
- conditional formatting

🚧 Status:
Complete and available for review.

📎 Why it matters:
Rookie ADP can shift significantly before and after the NFL Draft, and websites may lag in reflecting these changes. This tool makes it easy to spot rising or falling players and capitalize on that movement during drafts.

---

## 📊 Project 4: Top 12 WR Scoring Consistency Analysis (Python & PDF Report)

🎯 **Goal:**
Analyze the year-over-year consistency of top-performing Wide Receivers in fantasy football, quantifying how often elite players maintain their status.

🧠 **What I Did:**
- Collected historical wide receiver fantasy scoring data from fantasypros.com (2016-2024 seasons).
- Utilized Python (Pandas) for data cleaning, structuring, and in-depth analysis.
- Calculated both total fantasy points (FPTS) and fantasy points per game (FPPG) for each player.
- Implemented a filter requiring a minimum of 10 games played for FPPG analysis to ensure per-game consistency.
- Identified the top 12 WRs for each season based on both FPTS and FPPG.
- Generated grouped bar charts using Matplotlib to visually compare individual player performance and rank year-over-year (e.g., 2016 vs. 2017, 2017 vs. 2018, etc.).
- Calculated and summarized retention rates for players initially in the top 12 who remained in the top 12, top 24, and top 36 in the subsequent season.
- Presented the full analysis, charts, and conclusions in a comprehensive PDF report.

🛠️ **Tools Used:**
- Python
- Pandas
- Matplotlib
- Jupyter Notebooks
- PDF Generation in PowerPoint

🚧 **Status:**
Complete and available for review in the `Top 12 WR Scoring.pdf` file.

📎 **Conclusions:**
- **Top-Tier Volatility vs. Overall Relevance:** While a significant portion of top 12 WRs repeat their elite performance (ranging from ~47% by total FPTS to ~58% by FPPG), a much higher percentage (74-83%) consistently remain in the top 36, indicating a strong floor for these players in fantasy terms.
- **FPPG as a Stronger Indicator of Consistency:** Analysis based on FPPG (with a minimum of 10 games played) reveals a higher retention rate for top 12 WRs (58.33% repeating top 12) compared to total FPTS (46.88%). This suggests that players who are highly efficient on a per-game basis and maintain reasonable health are more likely to sustain their elite production.
- **Dynasty and Redraft Implications:** Wide receivers, especially those demonstrating strong per-game efficiency, often represent a relatively safe investment in both dynasty and redraft fantasy football formats due to their high probability of maintaining at least strong flex/starter-level relevance.

---

## 👨‍💻 About Me

I’m James Hamer, an experienced retail leader pivoting into data analytics. I recently completed the IBM Data Analyst Professional Certificate and am passionate about combining analytics with real-world domains like fantasy sports.

📬 [Email](mailto:jhamer85@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/james-hamer-932868171/)  
🐙 [More Projects on GitHub](https://github.com/jhamer85)

---

## 🚧 In Progress

More fantasy analytics projects coming soon!
