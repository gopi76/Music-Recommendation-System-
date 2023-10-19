# Music Recommendation System

A collaborative filtering-based music recommendation system using K-means clustering. This system provides song recommendations based on user preferences and a dataset of music features.The dataset contains 174,389 rows and 19 columns, providing a comprehensive set of music features for analysis.
For a detailed overview of the project, refer to the Project Report PDF attached to this repository.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Collaborative Filtering](#collaborative-filtering)
- [Example](#example)
- [Dataset](#dataset)
- [Project Report](#project-report)
- [Contributing](#contributing)


## Introduction

This Python script implements a music recommendation system using collaborative filtering and K-means clustering. It analyzes user preferences to recommend songs similar to a given input.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/music-recommendation.git
    cd music-recommendation
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the music recommendation system:

1. Make sure you have the required dataset. The script assumes a CSV file named `dataset.csv`.

2. Import the necessary libraries and load the dataset:

    ```python
    import warnings
    import numpy as np
    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sns
    from tqdm import tqdm

    sns.set()
    dataset = pd.read_csv("dataset.csv")
    ```

3. Normalize the dataset and perform collaborative filtering with K-means clustering:

    ```python
    # Code for normalization and collaborative filtering
    ```

4. Create an instance of the `music_Recommendation_System` class:

    ```python
    recommendations = music_Recommendation_System(dataset)
    ```

5. Call the `recommend` method to get song recommendations:

    ```python
    recommended_songs = recommendations.recommend("Lovers Rock", 10)
    ```

## Collaborative Filtering

The system employs collaborative filtering, a technique that predicts a user's preferences based on the preferences of other users. This enhances the accuracy of song recommendations.

## Example

Here's an example of using the recommendation system:

```python
# Example of using the recommendation system
recommendations.recommend("Lovers Rock", 10)
```


## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.
