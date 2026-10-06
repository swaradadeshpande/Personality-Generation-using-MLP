# Text-Based Personality Generation using MLP

A Machine Learning project that uses a Multi-Layer Perceptron (MLP) to analyze Big Five personality traits and generate short descriptive personality characteristics based on questionnaire responses.

---

## 📌 Project Overview

Personality plays an important role in understanding human behavior and characteristics.

This project uses the **Big Five Personality Model** to analyze personality questionnaire responses and identify five major personality traits:

- Openness
- Conscientiousness
- Extraversion
- Agreeableness
- Neuroticism

The project uses the **Big Five Personality / IPIP-FFM dataset** containing questionnaire responses.

The questionnaire data is processed and used as input to an **MLP neural network**.

The final system aims to generate a short text-based personality description based on the predicted personality characteristics.

---

## 🎯 Objectives

The main objectives of this project are:

1. Load and understand the Big Five personality dataset.
2. Preprocess the questionnaire data.
3. Automatically identify personality questionnaire columns.
4. Calculate the Big Five personality scores.
5. Perform Exploratory Data Analysis (EDA).
6. Handle missing and invalid values.
7. Normalize the input features.
8. Train a Multi-Layer Perceptron (MLP) model.
9. Predict the Big Five personality characteristics.
10. Convert the predicted personality characteristics into a short textual personality description.

---

## 🧠 Big Five Personality Traits

The project uses the following five personality traits:

| Trait | Description |
|---|---|
| **Openness** | Creativity, curiosity and willingness to experience new things |
| **Conscientiousness** | Organization, responsibility and discipline |
| **Extraversion** | Sociability, energy and outgoing behavior |
| **Agreeableness** | Cooperation, kindness and friendliness |
| **Neuroticism** | Emotional sensitivity and tendency toward negative emotions |

---

## 📊 Dataset

The project uses a Big Five Personality / IPIP-FFM questionnaire dataset.

The dataset contains personality questionnaire responses associated with the five major personality dimensions.

The questionnaire columns used in this project are automatically detected from the dataset.

Examples of questionnaire column names include:

```text
EXT1, EXT2, ..., EXT10
EST1, EST2, ..., EST10
AGR1, AGR2, ..., AGR10
CSN1, CSN2, ..., CSN10
OPN1, OPN2, ..., OPN10
