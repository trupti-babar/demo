📊 WhatsApp Chat Analyzer – Python & Streamlit Project

📖 Project Overview

WhatsApp is one of the most widely used messaging platforms worldwide, generating massive amounts of conversational data every day. 
While we constantly use it, we rarely analyze our own communication patterns. This project aims to turn raw WhatsApp chat exports into meaningful insights using Python, Pandas, and Streamlit.
By reading and processing the exported .txt file from WhatsApp, the program cleans, structures, and analyzes the chat data to answer questions like:

Who is the most active participant?
At what times do people chat the most?
Which words and emojis are most commonly used?
How has messaging activity changed over time?

This project blends data preprocessing, exploratory data analysis (EDA), and data visualization into one interactive application.

🎯 Objectives of the Project

Understand human communication patterns through data analysis.
Practice Python libraries for real-world datasets.
Learn how to clean and preprocess text data for analysis.
Create interactive dashboards using Streamlit for non-technical users.
Explore the intersection of data science and social communication.

🧠 Theoretical Background

1. Data Collection
WhatsApp provides a feature to export chats as .txt files (with or without media). This project uses the raw text format without media for simpler processing.

2. Data Preprocessing
Raw chat exports are unstructured and contain noise, such as timestamps, sender names, and media placeholders. We must:
Parse each message to separate date, time, sender, and message.Handle multiline messages.
Remove media files entries (<Media omitted>).
Convert date formats for time-based analysis.

3. Data Analysis

Once structured into a Pandas DataFrame, the data can be analyzed to find:
Descriptive statistics (total messages, word count, media count).
Temporal patterns (daily, monthly activity).
User participation in group chats.
Most used emojis and words.

4. Data Visualization

The results are displayed using Matplotlib graphs:
Bar charts for top participants.
Line charts for activity over time.
Pie charts for message distribution.
Word clouds for common words.

5. Interactive User Interface

Streamlit turns the Python script into a web-based app where users can:
Upload their chat file.
Select the user they want to analyze.
View dynamic graphs and statistics without coding knowledge.

⚙️ Tech Stack and Libraries

Python – Core language for implementation.
Pandas – For data cleaning and manipulation.
NumPy – For numerical operations.
Matplotlib – For plotting statistical graphs.
Streamlit – For building the interactive dashboard.
Emoji – For emoji extraction and analysis.

🔍 Example Use Cases

Personal Analysis – See your own chat behavior patterns.
Group Chat Insights – Identify the most active members in a group.
Behavioral Research – Study how messaging changes over time.
Sentiment Analysis (Future) – Determine mood trends in messages.

📈 Benefits of This Project

Practical application of data science on real-world text data.
Improves skills in data preprocessing and visualization.
Creates a portfolio-worthy project for GitHub and LinkedIn.
Teaches how to handle time-series and categorical data.

🚀 How to Use

Export your WhatsApp chat (without media).
Upload the .txt file in the app.
Select your analysis options.
Explore detailed statistics and graphs.
