# 🐧 Palmer Penguins Data Analysis

## 📌 Project Overview
This project analyzes the **Palmer Penguins** dataset using **R and ggplot2**. The goal is to explore relationships between different penguin species and their physical characteristics while applying data visualization best practices.  

## 📊 Dataset  
The **Palmer Penguins dataset** contains measurements of three penguin species—Adélie, Chinstrap, and Gentoo—collected from islands in Antarctica. It includes attributes such as **bill length, flipper length, body mass, and sex**.  

Dataset source: [Palmer Penguins Dataset](https://allisonhorst.github.io/palmerpenguins/)  

## 🛠️ Tools & Libraries  
- **R** (tidyverse, ggplot2, dplyr, readr)  
- **RMarkdown** for reporting  
- **GitHub** for version control  

## 📁 Repository Structure  
📁 capstone-data-analysis/

│── 📜 README.md        
│── 📜 penguin_export.Rmd  
│── 📜 penguin_analysis.html   
│── 📊 data/              
│    ├── penguins.csv  
│── 📷 visuals/         
│    ├── Rplot_palmer_penguins.png  
│    ├── Rpoint_palmer_penguins.png  


## 📊 Key Insights  
✅ A scatter plot visualized the relationship between **flipper length and body mass**, showing distinct size differences between species.  
✅ Using **color and shape together** improved species differentiation in visualizations.  
✅ **Faceting by sex** allowed for a more granular trend analysis.  
✅ **Handling missing values** in the sex column improved data accuracy and insights.  

## 🚀 How to Reproduce  

1️⃣ Clone this repository:  
```bash
git clone https://github.com/ssagastume11/capstone-data-analysis.git
2️⃣ Open RStudio and run:
rmarkdown::render("penguins_analysis.Rmd")
3️⃣ View the generated HTML report for insights.

## Dataset
The dataset comes from the PalmerPenguins package in R, which provides ecological data for three penguin species in Antarctica.



📚 Resources & References
* Palmer Penguins Dataset
* ggplot2 Documentation
* RMarkdown Guide
  
## Next Steps
* Expand analysis with machine learning models.
* Compare with other wildlife datasets.
* Improve storytelling in my portfolio.
