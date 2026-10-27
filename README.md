# Generative-AI-Projects
A collection of my Generative AI projects, experiments, and implementations.
# 🤖 Generative AI Projects

A collection of my Generative AI projects and implementations,
covering generative models, image generation, large language
models, and other emerging GenAI technologies.

---

## 🚀 Projects

### 01 — Comprehensive Dataset Analysis & Preprocessing for Generative AI

A Python-based experiment for exploring, cleaning, preprocessing, and analyzing structured datasets to prepare high-quality, AI-ready data for Machine Learning, Deep Learning, and Generative AI applications.

**Concepts:** Exploratory Data Analysis (EDA), Data Preprocessing, Data Cleaning, Feature Scaling, Encoding, Data Visualization

**Tech Stack:** Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Keras, PyTorch, LangChain

**Highlights:**

* Dataset inspection and statistical analysis
* Missing value detection and handling
* Duplicate record identification and removal
* Categorical data encoding
* Feature scaling and normalization
* Data visualization using plots and heatmaps
* Correlation and relationship analysis
* Conversion of processed data into NumPy arrays and tensors
* Preparation of clean datasets for ML, Deep Learning, and GenAI workflows
* Introduction to structured dataset interaction using LangChain

➡️ **[View Experiment](https://github.com/srushtighatge25-commits/Understanding_Datasets)**

---

### 03 — AI Question & Answer System

A Generative AI question-and-answer web application that uses the pretrained FLAN-T5 language model to generate answers to user questions through a clean and interactive Flask-based interface.

**Concepts:** Large Language Models (LLMs), Natural Language Processing, Text Generation, Sequence-to-Sequence Models, Transformer Models

**Tech Stack:** Python, FLAN-T5, Hugging Face Transformers, PyTorch, Flask, HTML, CSS, JavaScript

**Highlights:**

* AI-powered question answering using `google/flan-t5-base`
* Interactive Flask-based web interface
* Adjustable answer length from 30 to 300 tokens
* Pretrained Transformer model integration using Hugging Face
* Local AI inference with automatic CUDA/CPU selection
* Lazy model loading and reuse for faster subsequent responses
* Example questions and real-time answer generation
* Input validation and error handling
* REST API endpoint for question answering
* Responsive user interface with copy and clear functionality
* Automated Flask route and validation tests

➡️ **[View Project](https://github.com/srushtighatge25-commits/Question_Answering_System)**

---

### 04 — Text-to-Image Generation using Stable Diffusion XL

A Generative AI application that converts natural-language prompts into images using the pre-trained Stable Diffusion XL (SDXL) diffusion model, with an interactive Gradio interface in Google Colab and an optional Flask-based web application.

**Concepts:** Text-to-Image Generation, Diffusion Models, Text Conditioning, Iterative Denoising, Prompt Engineering, Negative Prompting, Guidance Scale, Image Generation

**Tech Stack:** Python, PyTorch, Stable Diffusion XL, Hugging Face Diffusers, Transformers, Accelerate, Safetensors, Gradio, Flask, HTML, CSS, JavaScript

**Highlights:**
- Text-to-image generation using the pre-trained `stabilityai/stable-diffusion-xl-base-1.0` model
- Interactive Gradio interface running in Google Colab
- Customizable text prompts and optional negative prompts
- Adjustable inference steps and guidance scale
- Image generation using GPU-accelerated inference with FP16 precision
- Comparison of generation settings using different inference steps and guidance scales
- Optional Flask web application with a custom front end
- Generated image preview and download functionality
- Prompt engineering techniques for improving image results
- Support for running the notebook using a Google Colab GPU runtime

➡️ **[View Project](https://github.com/srushtighatge25-commits/text_to_image_sdxl)**

---

### 05 — MNIST Digit Generation using Variational Autoencoder (VAE)

A Generative AI application that learns to generate handwritten digits from the MNIST dataset using a Variational Autoencoder (VAE). It includes a Flask web application for interactively exploring the 2-dimensional latent space and generating new digits using the trained Decoder.

**Concepts:** Variational Autoencoders (VAE), Encoder–Decoder Architecture, Latent Space Representation, Reparameterization Trick, Reconstruction Loss, KL Divergence, Probabilistic Sampling, Image Generation

**Tech Stack:** Python, TensorFlow, Keras, NumPy, Matplotlib, Flask, Pillow, HTML, CSS, JavaScript

**Highlights:**
- VAE trained on the MNIST handwritten-digit dataset
- 2-dimensional latent space for visualizing and exploring learned representations
- Encoder learns latent mean (`z_mean`) and log variance (`z_log_var`)
- Reparameterization trick enables differentiable latent-space sampling
- Custom training step combining reconstruction loss and KL divergence
- Interactive latent map with click, drag, sliders, and keyboard controls
- Live decoding of selected latent vectors into 28×28 handwritten digits
- Random digit generation by sampling latent vectors from the standard normal distribution \(N(0, I)\)
- Interactive random samples that link back to their corresponding latent-space coordinates
- Trained Decoder exported in Keras format for standalone image generation
- Flask API for digit generation, random sampling, and latent-map access
- Google Colab notebook for training, visualization, and model export

➡️ **[View Project](https://github.com/srushtighatge25-commits/New-Image-Generation---MNIST_using-VAE)**

---



### 06 — Latent Faces: DCGAN Face Generation

A Generative AI web application for generating synthetic human
faces using a Deep Convolutional Generative Adversarial Network.

**Concepts:** DCGAN, GANs, Latent Space, Image Generation

**Tech Stack:** Python, PyTorch, Flask, HTML, CSS, JavaScript

**Highlights:**
- Synthetic 64×64 face generation
- Reproducible seed-based generation
- GPU/CPU inference
- CelebA fine-tuning workflow
- Automated testing
- Training checkpoint support

➡️ **[View Project](https://github.com/srushtighatge25-commits/Face-Generation)**

---

### 07 — Face Generation using StyleGAN

A Generative AI web application that trains and uses a compact StyleGAN-inspired architecture to generate synthetic 64×64 human faces, with interactive controls for random seeds, batch generation, and style truncation.

**Concepts:** StyleGAN, Generative Adversarial Networks (GANs), Latent Space, Mapping Network, Style-Based Generation, AdaIN, Noise Injection, Truncation Trick, Image Generation

**Tech Stack:** Python, PyTorch, Flask, CelebA Dataset, Jupyter Notebook, HTML, CSS, JavaScript

**Highlights:**
- Synthetic 64×64 RGB face generation using a StyleGAN-inspired model
- Mapping of random latent vectors (Z) into intermediate style vectors (W)
- Style-controlled synthesis using Adaptive Instance Normalization (AdaIN)
- Per-pixel noise injection for variation in fine image details
- Adjustable truncation (ψ) for controlling generated-image variation
- Seed-based generation for reproducible face batches
- Batch generation of 1–16 synthetic faces
- Progressive synthesis from a learned 4×4 constant to 64×64 output
- CelebA-based model training and experimentation
- Interactive Flask web interface for model inference
- Automatic CPU/CUDA inference support
- Downloadable generated faces as PNG images
- Separate training notebook and exported model checkpoint workflow

➡️ **[View Project](https://github.com/srushtighatge25-commits/Face_Generation_StyleGAN-)**

---

### 08 — MusicGen: Fine-Tuning for Novel Music Compositions

A Generative AI project that fine-tunes Meta's pretrained MusicGen model using Low-Rank Adaptation (LoRA) to generate novel instrumental music clips from text prompts. The project uses a genre-labelled audio dataset and provides a web-based MusicGen Studio for generating, playing, and downloading music.

**Concepts:** Audio Generation, MusicGen, Transformer Architecture, Text-to-Audio Generation, EnCodec Audio Tokenization, LoRA Fine-Tuning, Transfer Learning, Latent Audio Representations

**Tech Stack:** Python, PyTorch, Hugging Face Transformers, PEFT, Hugging Face Datasets, MusicGen, T5, EnCodec, Flask, HTML, CSS, JavaScript, Google Colab

**Highlights:**
- Fine-tuning of Meta's `facebook/musicgen-small` pretrained model
- LoRA-based parameter-efficient fine-tuning with rank 16
- Genre-labelled music dataset with 10 music genres
- Audio preprocessing and text-caption generation from genre labels
- Text-conditioned instrumental music generation
- Base model vs. fine-tuned model output comparison
- Experiments with both seen genres and an unseen genre
- Google Colab notebook covering the complete fine-tuning pipeline
- MusicGen Studio web interface with prompt input and duration selection
- Audio playback and WAV download support
- Exportable LoRA adapters for reuse with the pretrained model

➡️ **[View Project](https://github.com/srushtighatge25-commits/MusicGen)**

📓 **[Open Fine-Tuning Notebook](https://github.com/srushtighatge25-commits/MusicGen/blob/main/MusicGen_Finetuning_Novel_Compositions_FIXED.ipynb)**


---

### 09 — Personalized AI Assistant: RAG + QLoRA

A personalized AI assistant powered by an open-source large language model that answers questions about user-provided documents. The project compares four approaches: a base LLM, Retrieval-Augmented Generation (RAG), QLoRA fine-tuning, and RAG combined with fine-tuning.

**Concepts:** Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), QLoRA, Parameter-Efficient Fine-Tuning (PEFT), Semantic Search, Vector Databases, Text Embeddings, 4-bit Quantization

**Tech Stack:** Python, PyTorch, Hugging Face Transformers, Qwen2.5, PEFT, bitsandbytes, Sentence-Transformers, FAISS, Gradio, Flask, HTML, CSS, JavaScript, Google Colab

**Highlights:**
- Personalized question answering using user-provided documents
- Comparison of four LLM inference modes: Base Model, RAG, Fine-Tuned, and RAG + Fine-Tuned
- QLoRA fine-tuning of the Qwen2.5-1.5B-Instruct model
- 4-bit NF4 quantization for memory-efficient model loading
- Semantic document retrieval using MiniLM embeddings and FAISS
- Document chunking with configurable chunk size and overlap
- Retrieval of the top-3 relevant passages for context-grounded answers
- Interactive Gradio interface with Ask, Compare All Four, and Documents tabs
- Optional Flask-based local web interface
- Exportable LoRA adapters, FAISS index, document chunks, and configuration
- Experimental evaluation highlighting the strengths and limitations of RAG and fine-tuning

**Key Learning:** RAG provides relevant external knowledge, while fine-tuning adapts model behavior. Combining both requires training examples that teach the model how to interpret retrieved context.

➡️ **[View Project](https://github.com/srushtighatge25-commits/Personalized-AI-Assistant)**

📓 **[Open Training Notebook in Google Colab](https://colab.research.google.com/github/srushtighatge25-commits/personalized-ai-assistant-rag-lora/blob/main/notebooks/01_Train_RAG_QLoRA.ipynb)**

🖼️ **[View Demo Screenshots](https://github.com/srushtighatge25-commits/Personalized-AI-Assistant/tree/main/docs/screenshots)**

---

More projects will be added throughout the semester.
