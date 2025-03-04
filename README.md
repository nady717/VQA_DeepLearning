# Visual Question Answering (VQA) using Deep Learning

📌 Project Overview
This repository contains an implementation of a "Visual Question Answering (VQA) model" using deep learning. The goal is to develop a model that can interpret images and answer related questions using techniques from **Computer Vision** and **Natural Language Processing (NLP)**.

📂 Project Structure

VQA_DeepLearning/
│── NadyaMalekpour_VQA_DeepLearning.ipynb   # Main Jupyter Notebook
│── data/                                    # Folder for dataset (if applicable)
│── models/                                  # Pre-trained or custom-trained models
│── results/                                 # Model predictions and evaluation results
│── requirements.txt                         # Dependencies
│── README.md                                # Project documentation
```

🚀 Getting Started
🔹 1. Clone the Repository

git clone https://github.com/YOUR_USERNAME/VQA_DeepLearning.git
cd VQA_DeepLearning


🔹 2. Install Dependencies
Create a virtual environment (optional but recommended):

python -m venv vqa_env
source vqa_env/bin/activate  # On Windows use: vqa_env\Scripts\activate

Install required packages:

pip install -r requirements.txt


🔹 3. Run the Jupyter Notebook

jupyter notebook NadyaMalekpour_VQA_DeepLearning.ipynb


 📊 Dataset
- VQA v2 Subset:
• 265,016 images from COCO and abstract scenes
• At least 3 questions per image (5.4 avg.)
• 10 ground truth answers per question


 🧠 Model Architecture
- VQA model consists of:

• CNN (ResNet50) - Extracts deep visual features from input images
• LSTM - Converts textual questions into vector representations
• Attention Mechanism - Directs focus to key image regions based on the question
• Answer Prediction - Selects the most likely response from predefined answers


 🔍 Results
- Include evaluation metrics 
- sample predictions:
Question: 
Where is he looking?
True Answer: down 
Predicted Answer: yes

Question:
What are the people in the background doing? 
True Answer: watching 
Predicted Answer: yes

Question: 
What is he on top of? 
True Answer: picnic table 
Predicted Answer: yes


 🤝 Contributing
If you'd like to contribute, feel free to fork the repo and submit a pull request.



---
🚀 **Happy Coding!** If you find this useful, give it a ⭐ on GitHub! 😊
