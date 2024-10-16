# Fashion Recommender System

👕👖 A Python-based application for recommending matching pants based on shirt color using computer vision and KMeans clustering.

## Description

This project is a fashion recommender system that helps users find the best matching pants for their shirts. By analyzing the dominant color of a shirt image, the system uses KMeans clustering to suggest the top three pants from a provided collection that complements the shirt's color. 

## Features

- Upload or capture a shirt image.
- Specify a folder containing pant images.
- The system recommends the top three matching pants based on color similarity.
- Utilizes OpenCV for image processing and Scikit-learn for clustering.

## How It Works

1. The user uploads a shirt image.
2. The user provides the folder path containing images of pants.
3. The system calculates the dominant color of the shirt.
4. It compares the shirt color with the colors of the pants in the folder.
5. It recommends the best-matching pants based on the color distance.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/sheak9363/fashion-recommender-system.git
