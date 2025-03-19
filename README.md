
# BrainDead 🧠 2K25:

![BrainDead Logo](https://github.com/user-attachments/assets/db36aa27-72f8-4fd6-9de6-18f1c4b4c8f6)

# BrainDead 🧠: The Ultimate Data Analysis & Machine Learning Challenge

🚀 Exciting News! Revelation 2K25 is back, proudly presented by the **Department of Computer Science and Technology, IIEST Shibpur**. This year, we are thrilled to announce our collaboration with multiple leading product-based companies eager to recruit top talent from our main technical events. Don't miss this unparalleled opportunity to **showcase your skills, stand out, and secure your future in the tech world**! See you at Revelation 25! 🎉 #Revelation25 #TechFest #IIESTS #CareerOpportunities

---

Get ready for an exciting challenge in **data analysis and machine learning** at **Revelation '25 with BrainDead**! 🚀 

We are excited to present **two compelling problem statements** for this flagship competition. **Both problems are compulsory**—whether you solve one, both, or even just a part, we encourage you to **make a submission** and showcase your expertise! On behalf of **Team Revelation**, we wish you all the best! 💻🔍 #BrainDead #Revelation25 #DataAnalysis #MachineLearning

---

### 📞 Contact Us

📧 **Email**: [revelationiiest@gmail.com](mailto:revelationiiest@gmail.com)  
📲 **Join WhatsApp Group**: [Click here](https://chat.whatsapp.com/EHiJ00VTMjG5zs2xjdlZuQ)


### 📌 Submission Requirements

- For Problem Statement 1 & 2, prepare a **concise report** in **.pptx** or **.pdf** format.
- Append your **Problem Statement 2 report** to the **Problem Statement 1 report**.
- Upload your **iPython notebook (.ipynb)** to **GitHub** and share your **public repository link via UnStop**.

### 🔔 **Important Notes:**
- **Both problem statements are compulsory.**
- You can submit whichever problem you solve, but **your score for an unsolved problem will be 0**.
- **If you submit the report but not the iPython notebook, your score for that problem will be 0** *(Aryabhatta to be blamed! 🙃)*.

Long story short, **create a single concise report covering both problem statements** (if you have solved both) and **upload the corresponding code to GitHub**.

🎯 **Best of luck! Show us your skills and make your mark at Revelation 2K25!** 🚀

---

# Problem Statement 1: Statistics is All You Need: IPL Data Analysis and 2025 Winner Prediction – The Game Behind the Game!


#### 🎯 Marks: 40

#### 📌 Problem Statement:
Cricket is the most popular sport in India. There are various formats of this game and the most loved one is the Indian Premier League (IPL). This professional Twenty20 cricket league in India gets contested during March or April and May of every year by eight teams representing ten different cities on India. The league was founded by the Board of Control for Cricket in India (BCCI) in 2008. The IPL has an exclusive window in ICC Future Tours Programme. It is the most-attended cricket league in the world. Currently, it’s the 18th season of IPL.

You have to perform a comprehensive analysis of IPL data from its inception through to the most recent season in 2024, aimed at uncovering key **insights**, **trends**, and **patterns**. It should consists of **data collection**, **preprocessing**, and **exploratory data analysis (EDA)** to visualize metrics such as **win rates**, **player performance**, and **team statistics**. The analysis includes statistical insights to identify significant factors influencing match outcomes. You may use pandas and NumPy for data manipulation and matplotlib and seaborn for data visualization.

Also, try to develop an **ensemble model**, combining different classifier models (one such example is the ensembling of classifiers like **Random Forest** and **XGBoost**) for predicting the winner of the 2025 IPL season. It should explain the **model’s features**, **training**, **validation**, and **performance evaluation**. Additionally, you can explore experimenting with **neural networks**. The results section must present the model’s predictions for the 2025 season, and discussion regarding the potential strengths and limitations, and should provide insights into the predicted performance of teams and key players. The primary objective is to use historical IPL data to build a predictive model for future match prediction outcomes, demonstrating the application of advanced machine learning techniques to sports data.

#### 🔍 Analysis Goals:

##### 1️⃣ **Data Cleaning and Feature Engineering**
- Ensure that **no missing values or outliers** exist in the dataset.
- Handle potential issues that could **impact insights and predictions**.

##### 2️⃣ **Exploratory Data Analysis (EDA)**
Perform the following analyses based on the **IPL 2008-2024 Dataset**:

###### 🏏 **Team Performance:**
- **Plot Matches Played and Winning Percentages**
- **Plot Run Rate and Economy Rate**
- **Plot Highest and Lowest Scores**
- **Plot Total 4s and 6s**
- **Plot Average Powerplay and Death Overs Score**
- **Run per over of each team**
- **Powerplay Analysis**

###### 👤 **Player Performance:**
- **Plot top run-scorers**
- **Get the top 20 run-scorers**
- **Plot Batting Average vs Batting Strike Rate for the top 20 run-scorers**
- **Find Highest Average and Strike Rate for players with >50 matches**
- **Plot top wicket-takers**
- **Plot top highest individual scores**
- **Man of the Match Count Analysis**
- **Plot Batting Average vs Bowling Economy Rate with Clusters (K-Means Clustering)**
- **Identify Top 10 Batsmen in each run category**:
  - **Top 6’s scorer**
  - **Top 4’s scorer**
  - **Top 2’s scorer**
  - **Top 1’s scorer**

###### 📅 **Seasonal Analysis:**
- **Calculate average runs per match per season**
- **Identify targets of 200+ runs per season**
- **Find the average score of each team per season**
- **Analyze runs of Orange Cap Holders per season**
- **Track wickets of Purple Cap Holders per season**
- **Find top 10 bowlers per season**

##### 3️⃣ **Feature Extraction**:
- Extract key features from **`matches.csv`** dataset.
- Extract crucial insights from **`deliveries.csv`** dataset.

##### 4️⃣ **Winner Prediction Model**:
- **Develop a prediction model** based on the above analyses to predict the **winner of IPL matches**.

---

#### 🛠 Tools for Analysis:
Participants may use the following tools:

- **MS Excel**
- **Tableau/Power BI**
- **Jupyter Notebook/Google Colab with Matplotlib**

#### 📂 Dataset Link:
The dataset consists of two separate CSV files: **matches** and **deliveries**. These files contain the information of each match summary and ball by ball details, respectively. [BrainDead IPL Complete Dataset (2008-2024)](#) *(Insert link here)*

#### 📊 Metadata Description of 'matches' file:

The **`matches.csv`** file consists of the match informations of **1095 face-offs** amongst the teams in all the IPL seasons in the last 17 years! 
-	**'id'**: Unique identifier for each match.
-	**'city'**: City where the match was played.
-	**'date'**: Date of the match.
-	**'player_of_match'**: Name of the player who was awarded "Player of the Match."
-	**'venue'**: Stadium or venue where the match was played.
-	**'neutral_venue'**: Binary indicator (0 or 1) indicating if the match was played on a neutral venue (1) or not (0).
-	**'team1'**: Name of the first team participating in the match.
-	**'team2'**: Name of the second team participating in the match.
-	**'toss_winner'**: Name of the team that won the toss.
-	**'toss_decision'**: Decision taken by the toss-winning team (either 'field' or 'bat').
-	**'winner'**: Name of the team that won the match.
-	**'result'**: The result of the match (e.g., 'runs', 'wickets', 'tie', etc.).
-	**'result_margin'**: The margin by which the winning team won the match (e.g., runs or wickets).
-	**'eliminator'**: Binary indicator (0 or 1) indicating if the match was decided by an eliminator (1) or not (0).
-	**'method'**: The method used to decide the match (e.g., Duckworth-Lewis, etc.).
-	**'umpire1'**: Name of the first on-field umpire.
-	**'umpire2'**: Name of the second on-field umpire.

#### 📊 Metadata Description of 'deliveries' file:

The **`deliveries.csv`** file consists of ball by ball informations of all the 1095 face-offs. The dataset consists of **14,26,312 delivery entries** and **17 attributes**.
-	**'match_id'**: Unique identifier for each match.
-	**'inning'**: The inning number of a match
-	**'batting_team'**: The name of the batting team
-	**'bowling_team'**: The name of the bowling team
-	**'over'**: The over number in the ongoing inning for the batting team
-	**'batter'**: The name of the batsman (at the striker end)
-	**'bowler'**: The name of the bowler
-	**'non_striker'**: The name of the batsman at the non-striker end
-	**'batsman_runs'**: Runs scored by the batsman (at the striker end)
-	**'extra_runs'**: Extra runs (if any) conceded by the bowler
-	**'total_runs'**: The total runs conceded by the bowler (including the runs scored by the batsman and the extra runs conceded)
-	**'extra_type'**: The type of extra runs conceded (wide, no-ball, bye, leg-bye, etc.)
-	**'is_wicket'**: A flag variable to indicate if there is a dismissal in a particular ball ('0' means 'no dismissal'; '1' means 'dismissal')
-	**'player_dismissal'**: The name of the player (batsman) who got dismissed
-	**'dismissal_kind'**: The type of dismissal (caught, bowled, run-out, LBW, stumping, obstructing the field, etc.)
-	**'fielder'**: The name of the fielder (may be bowler also) participated in the dismissal

#### 🔑 Key Details:
- **1 run** is given as an extra run to the batting team in case of wide and no-ball.
- The bowler has to bowl **one extra delivery** in case of wide and no-ball.
- The runs scored by the batsman in case of bye and leg-bye will not get counted in the batsman's individual run, rather, it will get added to the team total.
- The **'super over'** situation in case of a tie should not be considered in any evaluation. Those are just for tie-breaking purposes.
- In December 2018, the team changed its name from the **Delhi Daredevils** to the **Delhi Capitals**.
- **Sunrisers Hyderabad** replaced the **Deccan Chargers** in 2012 and debuted in 2013.

---

#### 📑 Deliverables:
- A **complete report** detailing dataset analysis and methodology
- The report should be **concise**, including **references, tables, figures, and results**
- **Clear methodology** for prediction
- If **Excel** is used, mention the **Excel formulas applied**
- **Source code** for predicting rice production for the next **5 years**


#### 📊 Marking Criteria:
Participants will be evaluated based on:

1. **Writing style**, references, and presentation of findings
2. **Dataset exploration** and insights derived
3. **Methodologies used** for analysis and prediction
4. **Source code**
5. **Results and discussion**

---

# **Problem Statement 2: Research Article Summarization Using Advanced NLP Techniques**  
#### 🎯 Marks: 60 

#### 📌 Problem Statement:
With the exponential rise in scientific publications, researchers struggle to keep up with the vast volume of literature. The challenge lies in creating a **state-of-the-art model that accurately summarizes research articles** while preserving key insights and readability, enabling researchers to assimilate information swiftly. Scientific papers differ significantly from general text due to their **structured frmat (Introduction, Methods, Results, Discussion, etc.), citation dependencies, and inclusion of figure/tables**. Summarizing such documents requires handling **domain-specific challenges**, maintaining semantic coherence, and ensuring **faithful knowledge retention**. This competition challenges participants to develop a **novel framework for summarizing research artciels**, leveraging **state-of-the-art approaches**, including **Large Language Models (LLMs)** with an aim to develop a **hybrid summarization model** that surpasses existing benchmark models while maintaining computational efficiency. 

Participants must develop an extractive-abstractive hybrid model that:
- Summarized single and multi-document research papers
- Handles long-document summarization constraints while maintaining efficiency

Participants will be provided with **multiple research article datasets**, including a proprietary dataset from IIEST Shibpur, **CompScholar**, and two publicly available benchmark datasets (**PubMed and arXiv**). The task is to develop an efficient **text-based abstractive summarization model** that generates **concise, coherent, and relevant summaries** while outperforming existing models. Participants must also compare their models against **state-of-the-art summarization frameworks** (e.g., SummRuNNer, Pointer-Generator, Discourse Aware, BERT, T5, BART, PEGASUS, GPT-4, Longformer, and LED), providing a **detailed performance analysis with citations**.  

#### 📂 Dataset Link:
1. **CompScholar Dataset** (Private dataset—link to be provided during the competition).  
2. **PubMed Dataset** ([Dataset Link](https://huggingface.co/datasets/ncbi/pubmed))—contains millions of biomedical research articles with structured abstracts.  
3. **arXiv Dataset** ([Dataset Link](https://huggingface.co/datasets/arxiv-community/arxiv_dataset))—includes structured documents across multiple scientific disciplines.  

#### **Dataset Description**:
The datasets provided for this competition contain **full-text research articles** from diverse disciplines, including science, medicine, and engineering. Each dataset consists of **article abstracts and full texts**, with labeled summaries provided for supervised learning.  

The datasets contain the following:  
- **Research Articles**: Text files containing full-length papers and abstracts.  
- **Metadata**: Titles, keywords, citations, author information, and journal sources.  
- **Summarization Labels**: Ground truth summaries for evaluation and model training.  

The competition will focus on **extractive-abstractive summarization** techniques. Participants will explore **LLM-based** models to generate meaningful summaries that maintain contextual relevance.  

---

#### 📊 Deliverables:
- A **novel text summarization model** designed to generate concise, coherent, and accurate summaries of research articles.  
- **Trained models** demonstrating superior performance compared to existing benchmark summarization frameworks.  
- **Comparative results with state-of-the-art models**, including SummRuNNer, Pointer-Generator, Discourse Aware, BERT, T5, BART, PEGASUS, Longformer, LED, GPT-4-based summarization approaches, Other models cited in recent research papers  
- **A comprehensive evaluation report**, comparing results with existing benchmarks.  

#### **Performance Metrics**:
Models will be evaluated on:  
1. **ROUGE Scores (ROUGE-1, ROUGE-2, ROUGE-L)**—Measures the overlap of generated summaries with reference summaries.  
2. **BLEU Score**—Evaluates text fluency and translation quality.  
3. **Summarization Length and Readability**—Ensuring meaningful information is retained in concise form.  
4. **Computational Efficiency**—Assessing training time, inference speed, and memory usage.  

**Ranked Model Performance Table**:
| Rank | Model | ROUGE-1 | ROUGE-2 | ROUGE-L | BLEU |  
|------|-------|---------|---------|---------|------|  
| 1 | PEGASUS | 45.1 | 21.8 | 42.3 | 36.2 |  
| 2 | BART | 43.5 | 19.4 | 40.6 | 33.8 |  
| 3 | Longformer | 41.2 | 18.9 | 39.1 | 32.4 |  
| 4 | LED | 40.5 | 17.8 | 38.6 | 31.7 |  
| 5 | GPT-4-Summarization | 39.2 | 16.5 | 37.2 | 30.8 |  

---

### **Environment for Coding**: 
Everyone should use the mentioned environments for coding:  
- **Google Colab or Local System**  
- **Jupyter Notebook**  
- **TensorFlow, Keras, Python, PyTorch**  
- Your notebook name should follow this format: **(team_name_brain_dead_2k24.ipynb)**  

---

### **Submission Guidelines**:
- **Submission via Unstop**.  
- If there is an issue, contact us at [revelationiiest@gmail.com](mailto:revelationiiest@gmail.com).  
- **Join WhatsApp Group**: [Click here](https://chat.whatsapp.com/EHiJ00VTMjG5zs2xjdlZuQ)
- A complete report of the methodology employed in your work and the source code of your best pipelines for each selected dataset. The report should be concise. This report might include references, tables, figures, and results. Everyone should submit their code between 04/04/2024 at 10 AM to 07/04/2024 at 10:00 AM.  

#### **Submission Format**:
1. **Table of Contents**  
2. **Introduction**  
3. **Dataset Preprocessing**  
4. **Model Architecture and Training Methodology**  
5. **Performance Evaluation**  
6. **Results and Discussion**  
   - Summary of model performance on the test set  
   - Optimization Strategies  
7. **Conclusion**  
8. **References**  

#### **Marking Criteria**:  

Upload your code to Github. Create an account if you don’t have one. Make sure your repository is public. Your report should have most of these: Writing Style, references, figures, etc. Dataset exploration Methodology Results of analysis Comparative study Pipeline architecture you used Conclusion  

#### **Heads Up!**:
We'll be checking all submissions for plagiarism to ensure everything's original and above board. It's all about keeping things real and honest! 🚀

🚀 **Best of luck! Show us your analytical and predictive skills!**

---

## **Dataset Credits**:

### **Problem Statement 1:**  
[CrickSheet](https://cricsheet.org/)

### **Problem Statement 2:**  
- U.S. National Library of Medicine  
- Clement, C.B., Bierbaum, M., O'Keeffe, K.P. and Alemi, A.A., 2019. On the use of arxiv as a dataset. arXiv preprint arXiv:1905.00075.

