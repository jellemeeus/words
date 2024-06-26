# Words vocabulary + pronunciation + definition

This project aims to provide easy-to-read and printable vocabulary list of the
most common words of the English/Dutch/French/... language with their meaning.

The word lists contain the following points of data
* Spelling (text)
* Meaning (text)
* Example (text)
* Lexical spelling (text) (optional)
* pronunciation (audio) (optional)

This project contains scripts to extract data and formatting.

## Languages so far:
* English: see README.md in [`./english/`](./english)

## Data
Extracted data can be
found in formats `.pkl`, `.csv`, `.json`

Formatted lists in `/output` are formatted alphabetically, by CEFR rating, random and viewable in
`.pdf` and `.html` format.

See release or see hosted seperately https://www.mediafire.com/folder/ik6n07bumen6n/words


## Sample outputs English

1. grouped by CEFR alphabetical order
![by_cefr_img_sample](images/oxford_5000_exclusive_by_cefr_sample.jpg)

2. grouped by CEFR two columns word/type/definition
![by_cefr_two_column_by_cefr_shuffle_img_sample](images/oxford_5000_exclusive_two_column_by_cefr_shuffle_sample.jpg)

3. Spanish by CEFR
![spanish_5000_two_column_shuffle_by_rank_with_example_sample.jpg](images/spanish_5000_two_column_shuffle_by_rank_with_example_sample.jpg)

## Folder structure
```
├── audio
│   └── *.mp3
├── data
│   ├── data.pkl
│   ├── data.csv
│   ├── data.json
├── output
│   ├── output.html
│   └── output.pdf
├── format.ipynb
└── scrape.ipynb
```