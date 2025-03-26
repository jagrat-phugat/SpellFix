# SpellFix

## Overview
AutoCorrector is an NLP-based spelling correction system that utilizes Natural Language Processing techniques to identify and correct misspelled words in text input. This project explores different approaches to spelling correction, including frequency-based methods and probabilistic models.

## Features
- Tokenization and text preprocessing.
- Spelling correction using NLP techniques.
- Frequency analysis of words for improved accuracy.
- Support for different correction algorithms (e.g., NLTK, TextBlob, SymSpell).

## Technologies Used
- Python
- Jupyter Notebook
- NLTK / TextBlob / SymSpell
- Regular Expressions (Regex)
- Pandas & NumPy

## Cloning
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AutoCorrector.git
   cd AutoCorrector
   ```

## Usage
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Run the `AutoCorrector.ipynb` notebook.
3. Input misspelled text and get corrected suggestions.

## Methodology
The notebook follows these key steps:
1. **Data Preprocessing**
   - Removing punctuation and special characters.
   - Converting text to lowercase.
   - Tokenization and frequency analysis.
2. **Error Correction Techniques**
   - Word frequency-based correction.
   - NLP-based correction using TextBlob/SymSpell.
   - Probabilistic approaches for better accuracy.
3. **Evaluation**
   - Testing on sample text data.
   - Improving accuracy through feedback mechanisms.

## Future Improvements
- Enhance correction accuracy using deep learning models.
- Add support for grammar correction.
- Deploy as a web or mobile application.

## Results
- Model is correcting the words and giving correct spellings.
- On some realted words, it shows two or three related spellings.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.
