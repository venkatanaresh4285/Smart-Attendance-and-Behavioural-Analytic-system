# Smart-Attendance-and-Behavioural-Analytic-system

## Project Overview

The **Smart-Attendance-and-Behavioural-Analytic-system** is an AI-powered solution designed to automate attendance tracking using voice recognition. Leveraging deep learning, audio processing, and Gradio UI for an interactive interface, this system enhances the accuracy and efficiency of attendance monitoring.

## Features

- **Automated Attendance Tracking**: Uses voice recognition to mark attendance.
- **Real-Time Audio Processing**: Captures and processes voice data for authentication.
- **Speaker Verification**: Identifies registered users based on their voice features.
- **Audio Feature Extraction**: Utilizes MFCC and spectrogram analysis for speaker recognition.
- **User-Friendly UI**: Interactive Gradio-based interface for easy attendance marking.
- **Data Storage & Visualization**: Stores attendance records and provides analytics dashboards.
- **Secure and Scalable**: Ensures data security with encrypted storage and scalable architecture.
- **Integration**: Compatible with existing Learning Management Systems (LMS) for seamless adoption.

## Technologies Used

- **Frontend**: Gradio (for UI), HTML, CSS, JavaScript
- **Backend**: Python (Flask/Django)
- **Database**: PostgreSQL/MySQL
- **Machine Learning**:
  - **Audio Processing**: Librosa, MFCC feature extraction
  - **Deep Learning**: TensorFlow/Keras for model training
- **Cloud Storage**: AWS S3/GCP Storage
- **Deployment**: Docker, Kubernetes, AWS/GCP

## Installation

### Prerequisites

- Python 3.8+
- Node.js and npm (for frontend, if applicable)
- PostgreSQL/MySQL
- Virtual environment (optional but recommended)

### Steps to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo/voice-attendance-system.git
   cd voice-attendance-system
   ```
2. **Install Backend Dependencies**
   ```bash
   cd backend
   pip install -r requirements.txt
   ```
3. **Set up Database**
   ```bash
   python manage.py migrate  # For Django
   flask db upgrade  # For Flask
   ```
4. **Run the Backend Server**
   ```bash
   python manage.py runserver  # Django
   flask run  # Flask
   ```
5. **Run the Gradio UI**
   ```bash
   python app.py
   ```

## Usage

1. **Login/Register**: Users authenticate using credentials.
2. **Voice Capture**: The system captures real-time audio for attendance verification.
3. **Feature Extraction**:
   - Uses Librosa to extract MFCC features and generate spectrograms.
4. **Attendance Marking**: Recognized voices are matched against the database.
5. **Reports & Dashboard**: Users can view attendance records and speaker recognition analytics via a web interface.

## Future Enhancements

- **Mobile App Integration**
- **Real-Time Noise Filtering**
- **Multilingual Voice Recognition**
- **Automated Report Generation**
- **Integration with Biometric Systems**



