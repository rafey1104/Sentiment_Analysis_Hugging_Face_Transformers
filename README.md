<h1>Instagram PlayStore Review Analysis</h1>
    <h2>Project Overview</h2>
    <p>This GitHub repository contains the code and resources used for analyzing Instagram PlayStore reviews. The project's primary goal is to perform sentiment analysis on user reviews to gain insights into user satisfaction and feedback regarding the Instagram mobile app.</p>
    <h2>Data Pre-processing</h2>
    <h3>Step 1: Data Collection</h3>
    <ul>
        <li>The Instagram PlayStore Review Dataset was obtained from Kaggle, a reputable platform for datasets.</li>
        <li>Dataset source: <a href="https://www.kaggle.com/datasets/saloni1712/instagram-play-store-reviews">Kaggle Instagram PlayStore Review Dataset</a></li>
    </ul>
    <h3>Step 2: Data Cleaning</h3>
    <p>Checked for Null Values.</p>
    <p>Utilized <code>neattext</code> for text cleaning:</p>
    <ul>
        <li>Removed stopwords.</li>
        <li>Removed punctuation.</li>
        <li>Handled special characters and noise.</li>
        <li>Managed contractions for improved text processing.</li>
    </ul>
    <h2>Model Selection and Fine-tuning</h2>
    <h3>Step 3: Model Selection</h3>
    <ul>
        <li>Leveraged Hugging Face Transformers for sentiment analysis.</li>
        <li>Utilized pre-trained models using the sentiment-analysis pipeline.</li>
    </ul>

    <h2>Data Visualization</h2>

    <h3>Step 4: Data Visualization</h3>
    <p>Visualized the resultant data, containing 'label' and 'score' columns, using the following techniques:</p>
    <ul>
        <li>Distributions.</li>
        <li>Categorical distributions.</li>
        <li>Values.</li>
        <li>Faceted distributions.</li>
    </ul>

    <h2>Usage</h2>
    <p>To use this project, follow these steps:</p>
    <ol>
        <li>Clone the repository to your local machine.</li>
        <li>Ensure you have the necessary libraries and dependencies installed.</li>
        <li>Execute the provided Jupyter notebooks or Python scripts for data preprocessing, model selection, and data visualization.</li>
        <li>Analyze the visualizations to gain insights into Instagram PlayStore reviews.</li>
    </ol>

    <h2>Resources</h2>
    <ul>
        <li><a href="https://www.kaggle.com/datasets/saloni1712/instagram-play-store-reviews">Kaggle Instagram PlayStore Review Dataset</a></li>
        <li><a href="https://huggingface.co/transformers/">Hugging Face Transformers</a></li>
    </ul>

    <h2>Dependencies</h2>
    <p>To run this project, you'll need the following dependencies:</p>
    <ul>
        <li>Python (3.6+)</li>
        <li>Jupyter Notebook</li>
        <li>Data manipulation and analysis libraries (e.g., Pandas, NumPy)</li>
        <li>Data visualization libraries (e.g., Matplotlib, Seaborn)</li>
        <li>Text preprocessing libraries (e.g., neattext, NLTK, SpaCy)</li>
        <li>Hugging Face Transformers library</li>
    </ul>

    <h2>Contributors</h2>
    <ul>
        <li><a href="https://github.com/rafey1104">Rafey Ahmed</a> - Project Lead</li>
    </ul>

    <h2>License</h2>
    <p>This project is open-source and available under the <a href="LICENSE">MIT License</a>.</p>

    <p>Feel free to contribute, report issues, or provide feedback. Your contributions are highly appreciated!</p>

