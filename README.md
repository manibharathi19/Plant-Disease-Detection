
# 🌱 **Plant Disease Detection**

## 🚀 **About the Project**
**Plant Disease Detection** is a machine learning-based project that uses **image classification** to identify and diagnose diseases in plants. The model analyzes images of plant leaves and classifies them into different disease categories, helping farmers and gardeners detect issues early and take action to protect their crops. This system aims to improve agricultural productivity by providing easy-to-use and accurate disease identification tools.

## 🔧 **Technologies Used**
- **Programming Language**: Python
- **Libraries**: 
  - **TensorFlow/Keras** (for deep learning model development)
  - **OpenCV** (for image processing)
  - **Matplotlib** (for data visualization)
  - **NumPy** (for numerical operations)
  - **Flask** (for web framework to serve the model)
  - **Pandas** (for data manipulation)
- **Machine Learning**: Convolutional Neural Networks (CNN)
- **Frontend**: HTML, CSS, JavaScript (for the web interface)
- **Deployment**: Heroku (or your chosen platform for hosting)

## 🌱 **Features**
- **Disease Detection**: Identifies various plant diseases based on uploaded images of plant leaves.
- **User-Friendly Interface**: Simple web interface for users to upload images and receive disease predictions.
- **Accurate Predictions**: Powered by a trained deep learning model for high accuracy.
- **Multiple Disease Categories**: Detects a variety of plant diseases across different plant species.
- **Model Retraining**: Allows for periodic model updates and improvements using new datasets.

## 🧑‍💻 **How to Run the Project Locally**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/manibharathi19/Plant-Disease-Detection.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Plant-Disease-Detection
   ```

3. **Set up a virtual environment** (Optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use: env\Scripts\activate
   ```

4. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Prepare the dataset**:
   - Ensure the dataset is in the correct directory, typically a folder with plant images and labels. If you don't have the dataset, you can use any suitable plant disease dataset, or follow the dataset instructions in the repository.

6. **Train the model** (if not pre-trained):
   - Run the following command to start training the model:
   ```bash
   python train_model.py
   ```

7. **Run the Flask application**:
   ```bash
   python app.py
   ```

8. **Access the web app**:
   - Open your browser and go to `http://localhost:5000` to access the Plant Disease Detection web app.

## 📚 **Usage**
- **Upload an Image**: Users can upload an image of a plant leaf affected by a disease.
- **Get Prediction**: The model will analyze the image and return the predicted disease with an accuracy score.
- **View Results**: The user can view the predicted disease name and description, along with suggestions for treatment or prevention.

## 💡 **Future Improvements**
- **Mobile Application**: Build a mobile app for easier access and real-time image upload.
- **More Disease Categories**: Expand the model to include more plant species and diseases.
- **Real-time Detection**: Implement real-time video or camera-based disease detection for on-field use.
- **Integration with Agricultural Databases**: Connect the model to external agricultural data sources for more precise predictions.
- **Automatic Disease Treatment Recommendations**: Implement automatic suggestions for treatments based on the detected disease.

## 👥 **Contributing**
We welcome contributions to **Plant Disease Detection**:
- Fork the repository and create a new branch for your feature or bug fix.
- Submit a pull request with clear descriptions of the changes.
- Report any bugs or issues you encounter.

## 📜 **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌐 **Contact**
- **Mani Bharathi** - [GitHub Profile](https://github.com/manibharathi19)
- **Portfolio**: [Mani Bharathi Portfolio](https://manibharathi19.github.io/Portfolio)

---

