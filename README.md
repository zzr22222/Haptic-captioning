# Haptic-captioning
### Step 1: Keywords extraction

Cleaned_Manual_dataset.csv: manual_dataset separated by ','

Ptext: Original text from participants

fine_tune_res.csv: fine-tuned keywords by GPT-3.5

### Step 2: Keywords post processing

filtered_fine_tune_res.csv: divide keywords into words and phrases

phrase_fine_tune_res.csv: phrases from fine-tune

sentiment_results5.csv: sentiment results of words (positive/negative) .

processed_with_antonyms3: modify the "not" words with their antonyms

processed_sentiment_results4: sentiment results of words (positive/negative) after after converting all nouns to adjectives, and change comparative and superlative forms back to their base form. 

sequence.csv: sequence of signals in the experiment

### Step 3: Clustering

g5_positive/negative_clusters.csv w2v5_positive/negative_clusters.csv ft5_positive/negative_clusters.csv cn_positive/negative_clusters.csv: result of clustering

neg/pos.png: silhouette score of each method

processed_uncase_sentiment_results3.csv: sentiment results of words (positive/negative) after matching the sequence of 32 signals.

### Step 4: Feature correlation

pos/neg.png: Pearson correlation of different methods

coverage_pos/neg_results.csv: words coverage of each signal

