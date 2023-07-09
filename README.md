# Text Similarity Comparison with spaCy

This repository contains code that demonstrates how to compare the similarity between complaints and recipes using spaCy's similarity model.

## Code Explanation

The Python code in this repository compares the similarity between two sets of texts: complaints and recipes. It uses spaCy, a popular natural language processing library, to process the texts and calculate the similarity scores.

### Code Files

- `text_similarity.py`: This file contains the main code for comparing the similarity between complaints and recipes. It loads the spaCy model, defines the complaint and recipe texts, and calculates the similarity scores using nested loops.

- `Dockerfile`: This file is used to build a Docker image that includes all the necessary dependencies and configurations to run the text similarity code. It specifies the base image, installs spaCy and the required language model, and sets the entry point for running the code.

## Usage

To run the text similarity comparison, follow these steps:

1. Install Docker on your machine if it's not already installed.

2. Clone this repository to your local machine.

3. Open a terminal or command prompt and navigate to the repository directory.

4. Build the Docker image using the provided Dockerfile:
   ```
   docker build -t text-similarity .
   ```

5. Run the Docker container:
   ```
   docker run text-similarity
   ```

6. The similarity scores between complaints and recipes will be displayed in the console output.

## Customization

You can customize the texts used for comparison by modifying the `complaints` and `recipes` lists in the `text_similarity.py` file. Add or remove texts as needed to suit your requirements.

## Further Exploration

For more information on spaCy and its features, refer to the official spaCy documentation: [https://spacy.io/](https://spacy.io/)

