# ImageCaptionGen
CNN + LSTM based Image Caption Generator using Flickr8k dataset
## Overview
This project generates natural language captions for any input image using a Convolutional Neural Network (CNN) as the encoder and Long Short-Term Memory (LSTM) network as the decoder. The model is trained on the Flickr8k dataset to understand visual content and generate meaningful descriptions.
## Features
- Upload any image and generate captions in real-time
- CNN-based feature extraction for image understanding
- LSTM-based sequence generation for accurate captions
- Streamlit UI for easy interaction
- Supports popular image formats: JPG, PNG, JPEG
## Dataset
The model is trained on the **Flickr8k dataset**, which contains 8,000 images with 5 captions each.  
This dataset provides a diverse set of real-world images including animals, humans, and objects.
## Architecture
- **CNN Encoder:** Extracts features from the input image (ResNet/VGG recommended)
- **LSTM Decoder:** Generates a sequence of words (caption) based on extracted features
- **Tokenizer:** Converts captions to sequences and maps words to integer tokens
## 8️⃣ Limitations
```markdown
## Limitations
- Model is trained on a **small dataset (Flickr8k)**, so performance on unseen or rare objects may be limited
- Some captions may be incorrect due to dataset bias (e.g., uncommon animals like bears)
