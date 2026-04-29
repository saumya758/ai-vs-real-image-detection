This project uses the CLIP (Contrastive Language–Image Pretraining) model to detect whether an image is AI-generated or real.
CLIP, developed by , is a powerful model that understands the relationship between images and text. We leverage this capability to classify images based on textual prompts like "AI-generated image" and "Real image".
🎯 Objective
To build a system that can classify images as AI-generated or real
To explore the power of multimodal models like CLIP
To implement a simple and effective image classification pipeline
🛠️ Tech Stack
Python 🐍
PyTorch 🔥
OpenAI CLIP Model
Google Colab
⚙️ How It Works
Input an image
CLIP encodes the image into feature vectors
Text prompts like:
"This is an AI-generated image"
"This is a real image"
CLIP compares image and text embeddings
The label with the highest similarity score is selected
