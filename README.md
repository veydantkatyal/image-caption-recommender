# AI Image Caption Recommender

This project implements an AI-based image caption recommendation system using OpenAI’s CLIP model and machine learning techniques. The system takes an input image and returns the most contextually relevant captions from a predefined list, making it useful for content generation, social media automation, or assistive technologies.

---

## Features

- Leverages OpenAI's CLIP model to understand image-text associations
- Recommends the most semantically appropriate captions for a given image
- Lightweight and easily customizable

---


## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/veydantkatyal/image-caption-recommender.git
cd image-caption-recommender
```

### 2. Install Required Packages
```bash
pip install -r requirements.txt
```

---


## How It Works
- Image Input

Load an image using PIL or other compatible libraries.

- Caption Dataset

Load a set of predefined captions from a .txt file.

- Text & Image Embedding

Use the CLIP model to convert both the image and each caption into embeddings.

- Similarity Matching

Compute cosine similarity between the image embedding and text embeddings to recommend the best match.

---

## Usage

1. Open the notebook:
```bash
jupyter notebook image_caption_recommender.ipynb
```

2. Follow the steps:

- Upload your own image and caption file (optional) or use test image given in the repo for testing model.

- Run all cells in the notebook.

- View top recommended captions for your image.

## License

This project is licensed under [MIT License](https://github.com/veydantkatyal/image-caption-recommender/blob/main/LICENSE)
