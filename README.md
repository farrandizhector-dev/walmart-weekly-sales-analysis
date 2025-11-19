Walmart Weekly Sales Analysis — Beginner Data Science Project

This is one of my first data analysis projects as a Data Science student.
My goal was to practice a full Exploratory Data Analysis (EDA) using Python and understand how weekly sales behave across different Walmart stores.
I focused on keeping the workflow simple, clear, and well-structured, since I’m still learning but want to build solid habits from the beginning.

🧰 Tools & Libraries Used

Python 3.12

Pandas — data cleaning and manipulation

Matplotlib — visualizations

VS Code + Jupyter Notebook

📁 Dataset Description

The dataset includes weekly sales information for several Walmart stores.
Main fields:

Store — Store ID

Date — Week of the year

Weekly_Sales — Revenue for that week

Holiday_Flag — Whether the week includes a major holiday

Temperature

Fuel_Price

CPI

Unemployment

The dataset used in this project is included as:

Walmart.csv

🔍 What I Did (Step by Step)
✔️ 1. Loaded and inspected the dataset

I checked the structure (df.info()), basic statistics (df.describe()), and looked at the first rows to understand the format.

✔️ 2. Cleaned and prepared the data

Converted the Date column to datetime

Created new columns such as Year, Month, and Week

Checked for duplicated or missing values

Prepared the dataset for grouping and visualization

✔️ 3. Analyzed the main trends

I answered several beginner-friendly business questions:

• How did sales change over the years?

I grouped weekly sales by year to understand overall performance.

• Which stores sold the most?

I compared total and average sales across all stores.

• Do holiday weeks generate more sales?

Using the Holiday_Flag to compare both cases.

• What are the top 10 highest-selling weeks?

Useful to understand seasonality and peak demand.

• Does temperature affect sales?

I plotted a scatter plot to see if hotter or colder weather influenced revenue.

📈 Visualizations Included

Line chart of total sales by year

Line chart of sales per store

Bar chart comparing holiday vs non-holiday sales

Scatter plot of temperature vs weekly sales

Table of top 10 selling weeks

🧠 What I Learned

This was a great project to practice the basics:

Reading and exploring real datasets

Cleaning and transforming data in Pandas

Creating grouped summaries

Generating visualizations to answer questions

Drawing conclusions based on data instead of assumptions

Understanding how to structure a complete EDA workflow

As a beginner, this project helped me understand how real-world data behaves and how to approach analysis step by step.

📝 Key Insights
🔹 1. Best sales year: 2011

This year clearly stands out in total weekly revenue.

🔹 2. Not all stores perform equally

Some stores sell significantly more than others.

🔹 3. Holiday weeks don’t necessarily sell more

In this dataset, they don’t show a strong increase.

🔹 4. Top sales weeks happen near the end of the year

Mostly around November–December.

🔹 5. Temperature has weak correlation with sales

Sales don’t move drastically with temperature changes.

🚀 Next Steps (Future Improvements)

As I keep learning, I want to:

Add forecasting models (Prophet, ARIMA…)

Build an interactive dashboard (Power BI / Tableau)

Use statistical tests to measure holiday impact

Expand the analysis with external datasets

🤝 About Me

I’m an 18-year-old Data Science student, and this is one of my first real projects.
I’m learning step by step and trying to build a strong foundation.
Any feedback or suggestions to improve this project are always welcome!
