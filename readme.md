# IsharaIntelligence: Real-Time Sign Language Detection

[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

IsharaIntelligence is a revolutionary sign language detection system that empowers communication for the deaf and hard-of-hearing community. Using the power of machine learning, it seamlessly bridges the gap between spoken and sign language, offering both real-time gesture recognition and image-based analysis.

## Key Features

- **Real-Time Gesture Recognition:** Utilizing OpenCV, Mediapipe, and TensorFlow, IsharaIntelligence captures and interprets sign language gestures in real-time, providing instant translations and feedback.
- **Image-Based Gesture Analysis:** Upload images of sign language gestures through the intuitive web interface. The Xception architecture-based model accurately identifies and translates the gestures.
- **User-Friendly Interface:** The static website component allows users to easily sign up, log in, and upload images for analysis.
- **Open Source:** Built on open-source technologies, IsharaIntelligence fosters collaboration and continuous improvement within the sign language recognition community.

## Demo

[Include a link to a video demo or animated GIF showcasing the system in action]

## Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/xvisierra/IsharaIntelligence.git
Install Dependencies:

bash
Copy code
pip install numpy==1.21.6 Pillow Keras==2.9.0 tensorflow==2.9.1 Flask pandas==1.4.2 opencv-python mediapipe
Run the Application:

bash
Copy code
python3 app.py
Usage
Real-Time Recognition:
Run the real-time gesture recognition module.
Perform sign language gestures in front of your camera.
View the translated text or interpretations in real-time.
Image-Based Analysis:
Visit the IsharaIntelligence website.
Sign up or log in.
Upload an image of a sign language gesture.
Receive the identified gesture and its translation.
Project Structure
SOURCE CODE/: Contains all the source code for the project.

Hand Gesture Recognition using deep learning/: Includes the deep learning models and datasets.
model/: Directory for model checkpoints and datasets.
static/: Contains static files for the web interface such as CSS, images, and JavaScript.
templates/: HTML templates for the web interface.
upload/: Directory for uploaded images for analysis.
real time hand gesture recognition/: Contains the code for the real-time gesture recognition module.
landmark_utils/: Utility functions for landmark detection.
model/: Model files for keypoint classification.
OUTPUT VIDEO/: Directory for storing output videos of gesture recognition.

REVIEW DOCUMENTS/: Documentation related to the project.

COMPLETE DOCUMENTS/: Finalized documents.
Contributing
We welcome contributions! Please see our CONTRIBUTING.md file for guidelines.

License
IsharaIntelligence is licensed under the MIT License.

Contact
If you have any questions or feedback, feel free to reach out to us:

Email: [your email address]
Twitter: [@your_twitter_handle]
