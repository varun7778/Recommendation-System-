# Recommender Systems

This repository contains implementations of various recommender system models, including collaborative filtering, content-based filtering, and demographic-based recommenders. The goal is to explore, analyze, and build recommenders that provide personalized suggestions based on user preferences, content similarity, and demographic attributes.

## Project Structure

```
RECOMMENDER/
├── datasets/                              # Directory containing dataset files for training and testing
├── .gitignore                             # File to specify untracked files for Git
├── collaborative_filtering_recommender.ipynb  # Implementation of Collaborative Filtering Recommender
├── content_based_recommender.ipynb        # Implementation of Content-Based Recommender
├── content_based_recommender_2.ipynb      # Alternative version of Content-Based Recommender
├── demographic_based_recommender.ipynb    # Implementation of Demographic-Based Recommender
├── requirements.txt                       # List of dependencies required for the project
```

## Features

- **Collaborative Filtering Recommender**:
  - Builds recommendations based on user-item interactions.
  - Utilizes techniques like user-based and item-based collaborative filtering.
  - Employs similarity metrics (e.g., cosine similarity, Pearson correlation).

- **Content-Based Recommender**:
  - Recommends items based on content features.
  - Analyzes item metadata to compute similarity scores.
  - Includes an alternative implementation (`content_based_recommender_2.ipynb`) with advanced techniques.

- **Demographic-Based Recommender**:
  - Generates recommendations by leveraging demographic attributes of users.
  - Clusters users based on shared characteristics to provide personalized suggestions.

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/recommender-systems.git
   cd recommender-systems
   ```

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure datasets are placed in the `datasets/` folder. Modify the notebook paths if necessary.

## How to Use

1. Open the `.ipynb` files.
2. Follow the instructions in each notebook to train and evaluate the respective models.
3. Experiment with hyperparameters, datasets, and techniques to improve performance.

## Requirements

The dependencies for this project are listed in the `requirements.txt` file. Use the command below to install them:

```bash
pip install -r requirements.txt
```

## Datasets

Datasets used for training and testing are located in the `datasets/` folder or the `datasets.txt`. These include:
- User-item interaction data for collaborative filtering.
- Metadata for content-based filtering.
- User demographic data for demographic-based recommendations.
