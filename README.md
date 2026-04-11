# Sentiment_Analysis

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: VEDANT ANGARKAR

*INTERN ID*: CTIS7177

*DOMAIN*: DATA ANALYTICS

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:

This project successfully developed and executed a high-performance sentiment analysis pipeline to decode the digital "pulse" of Indian political discourse, utilizing a massive dataset of over 160,000 unique tweets to achieve an exceptional overall accuracy of 89%. The primary objective was to move beyond simple keyword matching and implement a scalable Natural Language Processing (NLP) framework capable of categorizing complex social media commentary into three distinct emotional states: Positive (1), Neutral (0), and Negative (-1). Through extensive Exploratory Data Analysis (EDA), we uncovered a fascinating behavioral correlation between emotional intensity and message volume, where users expressing strong opinions—whether favorable or critical—tended to write significantly longer, more descriptive tweets (averaging 150–250 characters), while neutral statements remained consistently concise and factual. Despite identifying several "long-form" outliers in the text length distribution, we made the strategic decision to retain these entries to ensure the model captured the full depth of public grievances and praise, relying on subsequent mathematical weighting to handle the varied lengths. To prepare this notoriously "noisy" social media data for machine learning, we implemented a rigorous multi-stage cleaning pipeline that included standardizing text to lowercase, removing non-alphabetic characters, and performing stopword removal using the NLTK library. This refinement process was critical, as it allowed us to strip away grammatical "filler" and isolate the true thematic anchors of the dataset; while terms like "Modi," "BJP," and "Govt" served as the neutral subjects of discussion across all categories, the actual sentiment was driven by specific descriptive keywords such as "good" and "narendra" for positive tweets versus "poor" and "dont" for negative ones. To bridge the gap between human language and machine mathematics, we employed TF-IDF (Term Frequency-Inverse Document Frequency) Vectorization, a method that effectively "penalized" words appearing globally across the dataset while "boosting" the importance of unique, sentiment-rich terms. The processed data was then split into an 80/20 train-test ratio and fed into a Logistic Regression classifier, which was selected for its superior balance of speed and precision when handling high-dimensional, sparse text matrices. The final evaluation, visualized through a detailed Confusion Matrix, confirmed the model's robustness, demonstrating near-perfect recall (0.97) for neutral statements and high precision for positive sentiment. The minor "blur" observed between the positive and negative classes, totaling roughly 8% of cases, represents a standard threshold in modern NLP caused by linguistic complexities such as sarcasm, where a user might employ positive vocabulary to convey a negative underlying thought. Furthermore, this classification performance underscores the model's ability to navigate the nuances of political rhetoric, where the same subject matter can be framed through diametrically opposed emotional lenses. Ultimately, this project proves that a disciplined approach to data cleaning combined with sophisticated statistical modeling can transform hundreds of thousands of rows of messy social media "noise" into highly accurate, actionable insights. By providing a 100% complete and deployment-ready tool for monitoring public reaction to policy and governance, this framework demonstrates that in the era of Big Data, the collective voice of a nation can be quantified, analyzed, and understood with remarkable technical precision, offering invaluable support for data-driven decision-making in the public sphere and setting a strong foundation for future predictive analytics in social sciences.

*OUTPUT*:



![Image](https://github.com/user-attachments/assets/0422b440-a94a-48f1-8915-529d87efa020)
![Image](https://github.com/user-attachments/assets/35379a76-a726-4949-bf6e-51382cd8253b)
![Image](https://github.com/user-attachments/assets/d3f678fc-a5ef-46c4-97e6-39cad8074d09)
![Image](https://github.com/user-attachments/assets/36f5d2ae-d800-4c78-9275-00ffc32bc2fa)
![Image](https://github.com/user-attachments/assets/78c3cf27-ab37-4e33-bbc5-78a7dfce855e)
