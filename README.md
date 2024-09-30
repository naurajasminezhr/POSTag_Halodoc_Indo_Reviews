# POSTag_Halodoc_Indo_Reviews
This repository contains an analysis of user reviews for the HaloDoc application, a telemedicine platform in Indonesia. The project focuses on Natural Language Processing (NLP) techniques, specifically Part-of-Speech (POS) tagging, to gain insights into user feedback and sentiment.

# HaloDoc App Review POS Tagging Analysis

This project analyzes user reviews of the HaloDoc application using Part-of-Speech (POS) tagging to gain insights into the language used by users when describing their experiences.

## Project Structure
```
HaloDoc-Review-Analysis/
├── data/
│   ├── raw/
│   │   └── df_halodoc.csv
│   └── processed/
│       ├── word_pos_tags.csv
│       ├── top_pos_entities.csv
│       ├── pos_tags_summary_2.csv
│       └── pos_tags_all_summary.csv
├── notebooks/
│   └── PBAWeek5_POSTag_HaloDoc_Indo_Review_5026211005.ipynb
├── results/
│   └── (visualization outputs, if any)
├── README.md
└── requirements.txt
```

## Overview

This project uses Natural Language Processing techniques, specifically Part-of-Speech (POS) tagging, to analyze user reviews of the HaloDoc application. The analysis aims to understand the linguistic patterns and common themes in user feedback.

## Methodology

1. Data Collection: Reviews were collected from the HaloDoc app on the Google Play Store.
2. Data Preprocessing: Text cleaning and normalization were performed.
3. POS Tagging: The Polyglot library was used for POS tagging in Indonesian language.
4. Analysis: Frequency analysis of POS tags and entities was conducted.

## Results

The analysis yielded several interesting insights:

1. Most Common POS Tags:
   - PUNCT (Punctuation): 15,292 occurrences
   - NOUN (Nouns): 13,257 occurrences
   - PROPN (Proper Nouns): 12,920 occurrences
   - VERB (Verbs): 8,914 occurrences
   - ADV (Adverbs): 7,605 occurrences

2. Top Entities:
   - "dokter" (doctor): 2,078 occurrences
   - "obat" (medicine): 1,857 occurrences
   - "aplikasi" (application): 874 occurrences
   - "konsultasi" (consultation): 812 occurrences
   - "rumah" (home): 470 occurrences

3. Key Observations:
   - High frequency of nouns and proper nouns suggests users often refer to specific features or aspects of the app.
   - Significant presence of verbs indicates users describing actions or experiences.
   - Adverbs are commonly used, possibly to qualify experiences (e.g., "sangat membantu" - very helpful).
   - Punctuation is heavily used, which may indicate expressive or detailed reviews.

## Conclusions

The POS tagging analysis reveals that users frequently discuss specific features of the HaloDoc app, particularly focusing on doctors, medicines, and the consultation process. The language used is often descriptive and action-oriented, with users expressing their experiences in detail.

## Future Work

- Sentiment analysis to correlate POS patterns with positive/negative reviews
- Topic modeling to identify main themes in user feedback
- Comparative analysis with competitor app reviews

## Requirements

See `requirements.txt` for the list of Python packages required to run the analysis.

## How to Use

1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Run the Jupyter notebook in the `notebooks/` directory

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT). It puts only very limited restriction on reuse and has, therefore, high license compatibility.

Key points of the MIT License:
- It allows users to do anything with the code, including using it commercially.
- The only requirement is that the license and copyright notice must be included with the code.
- It provides no warranty or liability protection for the original author.

For the full license text, please refer to the LICENSE file in this repository.

