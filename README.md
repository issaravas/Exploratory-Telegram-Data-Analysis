# Exploratory-Telegram-Data-Analysis
Computational Social Science Project

### About the project
This data analysis looks at information taken from personal Telegram activity to find interesting patterns in communication and gain insights related to social behavior. By studying messages, conversations, and interactions in private and group chats, the goal is to understand how people communicate, what they prefer, and explore any social trends that might appear.

### Goals of the Research:
* Personal Behavioral Patterns: analyze the frequency, topics, and trends of interactions over time to identify how communication evolves in different contexts.
* Social Psychology Insights: Complement the analysis with relevant insights from social psychology, providing references to established studies that offer explanations for observed results on the charts. These references help interpret patterns, such as communication preferences, social group dynamics, and gendered interactions, within a broader psychological framework.
* Data-Driven Decision Making: use data visualization and advanced processing techniques, such as natural language processing (NLP) and TF-IDF analysis, to quantify interaction trends and evaluate personal priorities.

### Description of Technologies Used
This project relies on a variety of Python libraries and frameworks to analyze, clean, and visualize data extracted from Telegram. Here’s an overview of the key tools and their purpose:

#### Data Handling and Preprocessing:
- `pandas` and `numpy` were essential for organizing, cleaning, and manipulating the dataset, enabling efficient filtering, grouping, and statistical calculations.
- `json` and `re` were used to parse data and clean text fields to prepare them for analysis.

#### Visualization:
- `matplotlib.pyplot` and `pywaffle` were used to generate static plots like bar charts, waffle charts, and pie charts, helping summarize and present the data effectively.
- `plotly` provided interactive charts and subplots for dynamic visualizations, enhancing user engagement with the results.

#### Data Parsing:
- `collections.Counter` was applied to analyze word frequencies and reaction counts.
- `sklearn.feature_extraction.text.TfidfVectorizer` enabled advanced text analysis by calculating TF-IDF scores, identifying the most relevant terms across messages.

#### Date and Time Processing:
- `datetim`e was used for working with timestamps, allowing for trend analysis over time.

#### Performance Optimization:
- `tqdm` provided progress bars for long-running processes, improving the workflow's transparency.
