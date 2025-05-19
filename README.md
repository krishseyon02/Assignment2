# Assignment2

## Overview

This assignment will involve creating three Shell scripts for the Board games dataset, which will use Unix tools covered and/or calls to other Shell scripts

The three main scripts:
- `empty_cells`: Find out the number of empty cells per column in the raw data
- `preprocess`: Generate cleaned tsv file by cleans the raw dataset
- `analysis`: Answer the four research questions listed below
---

## Questions 

1. What is the most popular game domain?
2. What is the most popular game mechanic?
3. What is the correlation between year of publication and average rating?
4. What is the correlation between complexity and average rating?

---

## How to Run

### 1. `empty_cells`
**calculate empty values exist in each column of a file**

**Usage:**
```bash
./empty_cells <filename> <delimiter>
```

**Eg:**
```bash
./empty_cells bgg_dataset.txt ";"
```

---

### 2. `preprocess`
**Clean the dataset and save it as new cleaned file**

**Usage:**
```bash
./preprocess <filename> > cleaned_bgg_dataset.tsv
```

**Eg:**
```bash
./preprocess bgg_dataset.txt > cleaned_bgg_dataset.tsv
```

---

### 3. `analysis`
**Analyze the cleaned dataset**

**Usage:**
```bash
./analysis <cleaned_file.tsv>
```

**Example:**
```bash
./analysis sample.tsv
```

---
