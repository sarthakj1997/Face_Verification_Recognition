# Face_Verification_Recognition


## Project Description
This project implements a face recognition system using a neural network model in Keras. The system is designed to identify and verify individuals based on facial features.

### Key Features
- Utilizes a pre-trained Keras model for face detection and recognition.
- Employs techniques like triplet loss for effective training.
- Offers both verification (1:1 matching) and recognition (1:K matching) capabilities.

## Technologies Used
- Python
- TensorFlow & Keras
- NumPy
- Pandas
- PIL (Python Imaging Library)

## Installation
To set up this project, you need to have Python and the necessary libraries installed. Follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/sarthakj1997/Face_Verification_Recognition.git
   ```
2. Install the required libraries:
   ```
   pip install tensorflow keras numpy pandas pillow
   ```

## Usage
To use the face recognition system, follow these steps:

1. Load the pre-trained model.
2. Run the face detection script on your image data.
3. Use the provided functions to perform verification or recognition tasks.

## Additional Notes
- The system is optimized for individual recognition and might require additional tuning for different datasets.
- Experiment with different lighting conditions and facial expressions to improve accuracy.

## References
1. [FaceNet: A Unified Embedding for Face Recognition and Clustering](https://arxiv.org/pdf/1503.03832.pdf)
2. [DeepFace: Closing the gap to human-level performance in face verification](https://research.fb.com/wp-content/uploads/2016/11/deepface-closing-the-gap-to-human-level-performance-in-face-verification.pdf)
3. [FaceNet GitHub Repository](https://github.com/davidsandberg/facenet)
4. [Keras-FaceNet implementation](https://machinelearningmastery.com/how-to-develop-a-face-recognition-system-using-facenet-in-keras-and-an-svm-classifier/)
