# Image Retriever using CLIP and FAISS

This project demonstrates image retrieval using CLIP embeddings and FAISS for both image-based and text-based queries on a Pokémon dataset.

## Setup

1. Clone the repository.
2. Install required packages:
   ```bash
   pip install torch transformers datasets faiss-cpu matplotlib pillow
    ```

## Usage
- Image-based: query an image to find top-k similar images.
- Text-based: embed images, convert a text query to embedding, use FAISS to find closest images.
- Visualize results with matplotlib.

## Functions 
- embed_images: generate image embeddings
- embed_text: generate text embeddings
- search: retrieve top-k similar images using FAISS
