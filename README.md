# MedREQAL

The code and data for the paper "**[MedREQAL: Examining Medical Knowledge Recall of Large Language Models via Question Answering](https://arxiv.org/abs/2406.05845)**", accepted to Findings of **ACL 2024**.

The dataset can be found in the CSV file _MedREQAL.csv_

Explanation of columns in the dataset:


- **background**: _Background_ section of the systematic review.
- **objective**: _Objective_ section of the systematic review.
- **conclusion**: _Authors' conclusion_ section of the systematic review, used as the gold answer for generative QA task.

- **question**: Generated question (from the systematic review _Objective_ section)
- **verdict**: Generated verdict (from the systematic review _Authors' conclusion_ section), one of the three: SUPPORTED, REFUTED, NOT ENOUGH INFORMATION.
- **label**: Mapped verdict label: SUPPORTED (0), REFUTED (2), NOT ENOUGH INFORMATION (1).
- **strength**: Generated label for the strength of systematic review's findings (from the systematic review _Authors' conclusion_ section), one of the three: LOW, MEDIUM, HIGH.

- **category**: Automatically assigned medical category of the question / systematic review.
