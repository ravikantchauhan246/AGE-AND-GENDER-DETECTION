# Age and Gender Detection 

## Overview
This project implements a real-time age and gender detection system using deep learning and computer vision techniques. The system can analyze faces through both static images and live webcam feed to predict a person's age group and gender.

## Features
- Real-time face detection
- Age classification into 8 categories: (0-2), (4-6), (8-12), (15-20), (25-32), (38-43), (48-53), (60-100)
- Gender classification (Male/Female)
- Multiple face detection and analysis in a single frame
- Visual output with bounding boxes and predictions

## Technologies Used
- Python 3.x
- OpenCV (cv2)
- Deep Neural Networks (DNN)
- Caffe pre-trained models
- NumPy
- Matplotlib
- Scikit-learn

## Project Structure

├── age_deploy.prototxt
├── age_net.caffemodel
├── gender_deploy.prototxt
├── gender_net.caffemodel
├── opencv_face_detector.pbtxt
├── opencv_face_detector_uint8.pb
├── GenderAndAge.ipynb
└── README.md

## Installation
1. Clone this repository
2. Install required packages:
```bash
pip install opencv-python numpy scikit-learn matplotlib jupyter
```

## Usage
### Method 1: Using Jupyter Notebook
1. Launch Jupyter Notebook:
```bash
jupyter notebook
```
2. Open "GenderAndAge.ipynb"
3. Run the cells sequentially

### Method 2: Live Webcam Detection
1. Run the webcam detection script
2. Press 'q' to quit the program

## Model Information
The project uses three pre-trained models:
- Face Detection: OpenCV's DNN-based face detector
- Age Detection: Caffe model trained for age classification
- Gender Detection: Caffe model trained for gender classification

## Performance
- Face detection confidence threshold: 0.7 (70%)
- Real-time processing capability
- Suitable for multiple face detection and analysis

## Limitations
- Age predictions are approximate and grouped into ranges
- Performance may vary based on lighting conditions
- Requires good quality webcam for better results

## Future Improvements
- Add support for more age categories
- Implement emotion detection
- Improve accuracy in varying lighting conditions
- Add support for video file processing
- Optimize performance for slower systems

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments
- OpenCV community
- Caffe model creators
- Deep learning research community

## Author
[Your Name]

## Contact
- Email: chauhan@ravikant.dev
- GitHub: https://github.com/ravikantchauhan246


