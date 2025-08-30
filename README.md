# TikCheck

## 📌 Project Overview

This project explores patterns in Google Local Reviews using Natural Language Processing (NLP) techniques. Our analysis focuses on uncovering insights that can inform platform strategies across five key stakeholder groups:

Users (General Audience): Ease of content creation, engagement, community building, accessibility, and data privacy.

Creators: Monetization opportunities, recognition, and growth support.

Businesses & Advertisers: Product promotion, e-commerce integration, brand safety, and advertising analytics.

Platform & Technology: AI-driven personalization, new content formats, scalability, and performance.

Regulators & Society: Compliance, transparency, and social responsibility.

By leveraging the dataset of millions of user-generated reviews (Google Local Reviews dataset), we aim to identify factors that enhance user engagement, content creation, business promotion, and trust on digital platforms.

## ⚙️ Setup Instructions
1. Clone the Repository
git clone <your-repo-link>
cd <your-repo-name>

2. Create a virtual environment

3. Install Dependencies:
`pip install -r requirements.txt`

All dataset can be found here in the repo, and are clearly specified in the notebooks.

## 👥 Team Member Contributions

[Coco] – Data preprocessing, model development, README documentation.

[Xavier] – Model training, evaluation, and results analysis.

[Ungchan] – Model training, evaluation, and results analysis.

[Kai Jun] – Model training, evaluation, and results analysis.

[Jairus] – Model training, evaluation, and results analysis.

## 📊 Key Themes Explored

Content creation & engagement → Making platforms fun, interactive, and inclusive.

Business promotion → Enabling brands to effectively reach audiences.

E-commerce integration → Analyzing opportunities for in-app purchasing.

Privacy & accessibility → Ensuring trust, safety, and inclusivity.

AI & regulation → Balancing innovation with compliance and responsibility.

## ↩️ General Flow of Pipeline

Data Collection (Both Reviews Dataset & User-Metadata Dataset) -> Data Cleaning -> EDA -> Feature Engineering -> Modelling -> Final Evaluation

For the user_metadata dataset, we would be use the user's past reviews that we have collected, aggregate them to form user-level features, and merge them with the main `Reviews Dataset`.

## ⚠️ Disclaimer

All the relevant documentations are clearly done in the 11 notebooks. 

Please note that since we have crawled data using APIs, used GPT to synthesize data, it would not be possible to be able to replicate the data collection process (step1_data_collection.ipynb).

The dataset that we have collected (initial datasets) can be found under `final_data/initial_dataset.csv` and `final_data/user_metadata.csv`.

As such, please start running the notebook from step2_data_cleaning.ipynb.
