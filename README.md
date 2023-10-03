# SMS Spam Detection with Naive Bayes and SVM

## Overview

This repository contains Python code for SMS spam detection using Naive Bayes and SVM classification. The code is organized into several files:

- **spam.py**: Main script for running the Naive Bayes and SVM models.
- **svm.py**: SVM-related functions and classification.
- **util.py**: Utility functions for data loading and processing.
- **ds6_train.tsv, ds6_val.tsv, ds6_test.tsv**: Datasets for training, validation, and testing.
- **p06_dictionary.json**: JSON file storing the word-to-index dictionary created during data preprocessing.
- **p06_sample_train_matrix.csv**: CSV file containing a sample of the training matrix for inspection.
- **p06_naive_bayes_predictions.csv**: CSV file storing predictions made by the Naive Bayes model.
- **p06_top_indicative_words.json**: JSON file listing the top five indicative words for spam according to Naive Bayes.
- **requirements.txt**: File specifying Python packages needed to run the code.

## Usage

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/nessayoub/sms-spam-classifier.git
    cd sms-spam-classifier
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Code

1. Execute the main script:

    ```bash
    python spam.py
    ```

2. Check the output files and inspect the results.

### Results

- **Naive Bayes Accuracy**: The accuracy of the Naive Bayes model on the testing set is displayed in the console.

- **Top Indicative Words**: The top five indicative words for spam, according to Naive Bayes, are stored in the `p06_top_indicative_words.json` file.

- **Optimal SVM Radius**: The optimal SVM radius is computed but is currently commented out in the code for further refinement.

- **SVM Accuracy**: If the SVM model is enabled, the accuracy of the SVM model on the testing set would be printed.

## Additional Notes

Feel free to explore and modify the code for your own projects. Contributions are welcome!
