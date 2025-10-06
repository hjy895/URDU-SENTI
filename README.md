# Urdu-Senti: A Manually Curated Benchmark for Aspect-Level Sentiment Analysis

A comprehensive dataset of 9,981 aspect-sentiment pairs from 5,005 Urdu product reviews with 0.787 inter-annotator agreement.

## Dataset Statistics

- **Total Reviews:** 5,005
- **Aspect-Sentiment Pairs:** 9,981
- **Sentiment Distribution:** 41.1% Positive, 39.3% Negative, 19.6% Neutral
- **Inter-Annotator Agreement:** 0.787 (Substantial)
- **Domains:** Mobile Phones, Laptops, Clothing, Food, Books

## Files

### Pars-ABSA Style Format (Recommended)

- `Urdu-Senti_all.txt` - Complete dataset (9,981 samples)
- `Urdu-Senti_train.txt` - Training set (6,987 samples, 70%)
- `Urdu-Senti_test.txt` - Test set (2,994 samples, 30%)
- `Urdu-Senti_xml.xml` - XML format with aspect term positions

### Original Format

- `urdu_absa_dataset.txt` - Text format dataset
- `urdu_absa_dataset.xml` - XML format dataset
- `urdu_absa_statistics.json` - Dataset statistics

## Data Format

Each sample in the text files follows a 3-line format:

1. **Review text** with target replaced by `#TARGET#` placeholder
2. **Target aspect** (the actual aspect term)
3. **Sentiment label** (1=Positive, 0=Neutral, -1=Negative)

### Example:

```
یہ موبائل فون بہت اچھا ہے۔ کیمیرا کوالٹی بہترین ہے لیکن #TARGET# کم ہے۔
بیٹری لائف
-1
```
