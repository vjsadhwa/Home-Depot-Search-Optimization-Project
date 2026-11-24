# Home Depot: Search Relevance & Optimization

**NC State University | Institute for Advanced Analytics**  
October 2026

## Project Overview

Applied natural language processing (NLP) and unsupervised
learning to evaluate Home Depot's product search relevance,
identify causes of poor search results, and recommend
improvements to the online shopping experience.

## Business Objectives

- Evaluate the effectiveness of product search matching.
- Identify characteristics of successful and unsuccessful searches.
- Discover underlying product themes and customer search intent.
- Develop actionable recommendations to improve search relevance.

## Dataset

- 240,760 search-product pairs
- 124,428 unique products
- 24,601 distinct search queries
- 74,067 human-rated relevance scores

## Methodology

- Text preprocessing and normalization
- Keyword overlap and TF-IDF similarity
- Latent Semantic Analysis (LSA)
- Spearman rank correlation
- Non-negative Matrix Factorization (NMF)
- K-Means clustering
- UMAP dimensionality reduction

## Key Results

| Text Matching Method | Spearman Correlation |
|---|---:|
| Full-text word overlap | 0.375 |
| Title word overlap | 0.368 |
| TF-IDF similarity | 0.319 |
| LSA semantic similarity | 0.262 |

- Traditional keyword matching outperformed semantic
  similarity in agreement with human relevance ratings.
- Identified 12 underlying product themes and 8 customer
  search-intent clusters.
- Identified 1,140 missed matches and 113 confidently
  incorrect matches using semantic similarity.
- Discovered common search failure patterns involving
  misspellings, product accessories, and ambiguous terminology.

## Business Recommendations

- Implement spelling correction and synonym matching.
- Prioritize primary products over accessories in search results.
- Standardize product titles and specifications.
- Utilize semantic matching as a fallback for weak keyword matches.
- Improve autocomplete and customer search guidance.

## Technologies

Python | NLP | scikit-learn | TF-IDF | LSA | NMF |
K-Means | UMAP | Data Visualization

## Limitations

Recommendations are based on historical search relevance data.
Live experimentation would be required to quantify their
impact on customer satisfaction and conversion rates.

## About

Collaborative analytics project completed at NC State
University's Institute for Advanced Analytics.
