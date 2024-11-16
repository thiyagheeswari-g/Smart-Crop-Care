<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <div class="container">
        <h1>🌾 Smart Crop Care</h1>
        <p>Smart Crop Care is an AI-powered solution for identifying and classifying plant health, ensuring sustainable agriculture practices by accurately detecting diseased crops using advanced image processing and machine learning techniques.</p>
        
  <h2>🌟 Project Motivation</h2>
        <p>Modern agriculture faces challenges like early disease detection and crop health monitoring. This project aims to bridge this gap using AI-powered solutions to ensure farmers can take timely actions to safeguard their crops and maximize yield.</p>
        
  <h2>✨ Features</h2>
        <ul>
            <li>🖼️ <strong>Image-Based Classification</strong>: Detects crop health (Healthy/Diseased) using images.</li>
            <li>📊 <strong>Performance Metrics</strong>: Generates classification reports and confusion matrices for evaluation.</li>
            <li>🤖 <strong>Automated Predictions</strong>: Real-time prediction of new crop images uploaded to the system.</li>
            <li>🔍 <strong>Feature Extraction</strong>: Uses HOG (Histogram of Oriented Gradients) for robust feature extraction.</li>
        </ul>
        
  <h2>💻 Technologies Used</h2>
        <ul>
            <li><strong>Python</strong>: The core programming language used.</li>
            <li><strong>OpenCV</strong>: For image preprocessing and manipulation.</li>
            <li><strong>Scikit-learn</strong>: Machine learning algorithms for training and evaluation.</li>
            <li><strong>HOG Features</strong>: Extracts robust features for accurate image classification.</li>
            <li><strong>Google Colab</strong>: A cloud-based platform for development and testing.</li>
        </ul>
        
  <h2>📸 Images</h2>
        <p>Healthy and diseased crop classification:</p>
        <img src="https://images-provider.frontiersin.org/api/ipx/w=480&f=webp/https://www.frontiersin.org/files/Articles/1356260/fpls-15-1356260-HTML/image_m/fpls-15-1356260-g001.jpg">
        
  <h2>🚀 Usage</h2>
        <ol>
            <li>Clone or download the repository.</li>
            <li>Upload the dataset to the appropriate folders: <code>dataset/healthy</code> and <code>dataset/diseased</code>.</li>
            <li>Run the code on Google Colab or a local environment with dependencies installed.</li>
            <li>Use the trained SVM model for classifying new crop images.</li>
        </ol>
        
  <h2>🧠 Model Workflow</h2>
        <p>The project workflow involves:</p>
        <ul>
            <li>Preprocessing crop images using OpenCV (resize, grayscale conversion).</li>
            <li>Extracting Histogram of Oriented Gradients (HOG) features for robust feature representation.</li>
            <li>Training an Support Vector Machine (SVM) classifier to distinguish between healthy and diseased crops.</li>
            <li>Providing predictions for unseen crop images with high accuracy.</li>
        </ul>
        
  <h2>📂 Project Structure</h2>
        <ul>
            <li><code>/dataset/</code> - Folder containing crop images.</li>
            <li><code>smart_crop_care.ipynb</code> - Main notebook for training and testing.</li>
            <li><code>README.md</code> - Documentation for the project.</li>
        </ul>
        
  <h2>📊 Evaluation Metrics</h2>
        <p>The model evaluates performance using:</p>
        <ul>
            <li>Classification Report</li>
            <li>Confusion Matrix</li>
            <li>Accuracy Score</li>
        </ul>
        
  <h2>🚀 Future Enhancements</h2>
        <ul>
            <li>📱 <strong>Mobile Application</strong>: Develop a user-friendly mobile app for farmers to upload images for instant analysis.</li>
            <li>🌐 <strong>Cloud Integration</strong>: Store and process data on cloud platforms for scalability.</li>
            <li>🌱 <strong>Expand Dataset</strong>: Incorporate more crop types and diseases for generalized prediction models.</li>
            <li>⚡ <strong>Real-Time Analysis</strong>: Deploy the model on edge devices like Raspberry Pi for field-level usage.</li>
        </ul>
        
  <h2>🤝 Contribution</h2>
        <p>Contributions are welcome! Feel free to fork this repository, submit pull requests, or raise issues for discussion.</p>
        
  <h2>👥 Author</h2>
        <p>Developed by <strong>Thiyagheeswari G.</strong></p>
        
  <div class="feature-icons">
            <span class="icon">🌾</span>
            <span class="icon">📸</span>
            <span class="icon">🤖</span>
            <span class="icon">🔍</span>
        </div>
    </div>
</body>
</html>
