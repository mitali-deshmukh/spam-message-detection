# spam-message-detection
SMS Spam Classifier 
This project is a simple yet effective SMS Spam Classifier built using Python and Natural Language Processing (NLP) techniques. The goal is to distinguish between spam and ham (non-spam) messages using a labeled dataset.

📁 Project Structure /
Dataset: The project uses the classic SMSSpamCollection dataset.
Notebook: All code and analysis are performed in a single Jupyter Notebook file: AI&R_Miniproject.ipynb.

📊 Dependencies /
Make sure to install the following libraries:
pip install pandas numpy matplotlib seaborn nltk scikit-learn
Also, if using Google Colab, you’ll need to mount your Google Drive to access the dataset:
from google.colab import drive
drive.mount('/content/drive')

🚀 How to Run /
Open the notebook in Jupyter or Google Colab.
Mount your drive (if needed) and ensure the SMSSpamCollection file is accessible.
Run the cells sequentially.
Review the analysis and model performance.

📈 Results/
The model achieves high accuracy using basic NLP techniques and a simple Naive Bayes classifier. You’ll find visualizations of message lengths, word frequencies, and confusion matrices in the notebook.
