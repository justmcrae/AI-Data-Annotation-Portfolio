# Project 003: Named Entity Recognition (NER)

## Overview

This project demonstrates a complete Named Entity Recognition (NER) annotation workflow using manually annotated text samples. The objective was to identify and classify predefined named entities within natural language sentences following a consistent annotation schema and quality assurance process.

The dataset was manually annotated using a span-based annotation format, where each entity is enclosed in square brackets and immediately followed by its corresponding entity label.

Example:

```
[Emily Johnson]PERSON arrived at [Dubai International Airport]LOCATION on [18 April 2026]DATE.
```

The project emphasizes annotation consistency, accurate entity boundaries, and adherence to annotation guidelines throughout the review process.

---

# Objective

The goal of this project was to create a high-quality Named Entity Recognition dataset suitable for training or evaluating Natural Language Processing (NLP) models while demonstrating professional annotation practices used in AI data annotation workflows.

---

# Entity Types

The following entity categories were annotated throughout the dataset:

| Label        | Description                                                                                                                |
| ------------ | -------------------------------------------------------------------------------------------------------------------------- |
| PERSON       | Individual names                                                                                                           |
| ORGANIZATION | Companies, institutions, agencies, universities, hospitals, airlines, government bodies, hotels, and similar organizations |
| LOCATION     | Cities, countries, airports, landmarks, museums, launch sites, and geographical locations                                  |
| PRODUCT      | Commercial products, software, branded services, devices, media titles, and platforms                                      |
| EVENT        | Conferences, summits, exhibitions, named annual events, and recognized celebrations                                        |
| DATE         | Calendar dates                                                                                                             |
| TIME         | Specific times                                                                                                             |
| MONEY        | Monetary values                                                                                                            |
| EMAIL        | Email addresses                                                                                                            |
| PHONE        | Telephone numbers                                                                                                          |

---

# Annotation Methodology

The dataset was annotated manually using span-based annotation.

Each entity follows this format:

```
[Entity]LABEL
```

Example:

```
[OpenAI]ORGANIZATION introduced [ChatGPT Enterprise]PRODUCT during [OpenAI DevDay 2026]EVENT.
```

The annotation process followed consistent entity boundary rules, longest-span selection, and standardized labeling conventions across all samples.

---

# Dataset Statistics

* **Task:** Named Entity Recognition (NER)
* **Annotation Method:** Manual span annotation
* **Total Samples:** 150
* **Entity Types:** 10
* **Quality Assurance:** Multi-round manual review
* **Annotation Status:** Completed

---

# Quality Assurance

Each annotation batch underwent manual quality review to verify:

* Correct entity boundaries
* Appropriate entity labels
* Consistent annotation formatting
* Longest valid entity spans
* Annotation guideline compliance

Reviewer feedback was incorporated after every review cycle to improve annotation consistency across the dataset.

---

# Folder Structure

```
Project-003-Named-Entity-Recognition/
│
├── dataset/
│   └── Named-Entity-Recognition-Dataset.xlsx
│
├── documentation
│   ├── Annotation-Guidelines.pdf
│   ├── QA-Review-Report.pdf
│   ├── Project-Summary.pdf
│   └── Project-Reflection.pdf
│
└── README.md
```

---

# Skills Demonstrated

* Named Entity Recognition (NER)
* Span-based annotation
* Entity boundary identification
* Annotation guideline development
* Quality assurance and review
* Dataset validation
* NLP data preparation
* Annotation consistency

---

# Tools Used

* Microsoft Excel
* ChatGPT (project planning and quality review)

---

# Outcome

This project resulted in a professionally annotated Named Entity Recognition dataset containing 150 manually annotated text samples supported by annotation guidelines, quality assurance documentation, and project reporting. The completed project demonstrates practical experience with NLP data annotation workflows and emphasizes consistency, accuracy, and documentation standards expected in AI data annotation environments.
