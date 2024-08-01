# Fake News Detection Project
This repository contains the code used in the study "A Comparative Analysis of Fake News Classifier Models," where we trained and compared three different machine learning algorithms to detect real and fake news articles. The models included a naïve Bayes classifier, a support vector classifier, and a random forest classifier.

## Contents

- `notebooks/`: Directory containing the Jupyter Notebook used for the analysis.
  - `Condensed Fake News Project.ipynb`: Jupyter Notebook with the code for training and evaluating the machine learning models.

## CSV Files

Due to size limitations, the CSV files used in this study are stored in a Google Drive folder. You can download the files using the link below:

[Download CSV Files](https://drive.google.com/drive/folders/1N1QJVvWdLHFtKc2rbUvTIpj7i6rotds7?usp=drive_link)

Make sure to download the CSV files and place them in the root directory of this repository (same level as the `notebooks` folder) before running the notebook.

## Instructions

### Prerequisites

To run the Jupyter Notebook, you need to have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

### Setting Up

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/snithin2006/Fake-News-Detection-Project.git
    cd fake-news-detection
    ```

2. **Download the CSV Files:**

    Download the CSV files from the [Google Drive link](https://drive.google.com/drive/folders/1N1QJVvWdLHFtKc2rbUvTIpj7i6rotds7?usp=drive_link) and place them in the root directory of the cloned repository.

3. **Install Dependencies:**

    You can install the required dependencies using `pip`. You can use the following command:

    ```bash
    pip install -r requirements.txt
    ```

    This will ensure all the necessary packages are installed, including `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, and `nltk`.

### Running the Notebook

1. **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

2. **Open the Notebook:**

    In the Jupyter Notebook interface, navigate to the `notebooks` folder and open `fake_news_detection.ipynb`.

3. **Run the Cells:**

    Execute the cells in the notebook sequentially. The notebook reads the CSV files, trains the machine learning models, and evaluates their performance.

## Contact

For any questions or issues, please contact [nithin06.siva@gmail.com](mailto:nithin06.siva@gmail.com).
