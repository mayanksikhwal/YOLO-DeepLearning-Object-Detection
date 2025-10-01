# YOLO-DeepLearning-Object-Detection

## Project Description
This project implements a solution for face resolution enhancement using a UNET model, based on the concepts from a Kaggle notebook. The goal is to take a low-resolution face image (64x64 pixels) and produce a high-resolution, enhanced face image. The project involves defining the UNET model architecture, loading and preprocessing input images, applying the trained model, and visualizing the results.

## Tech Stack
*   **Python:** The primary programming language used for the implementation.
*   **TensorFlow:** Used for defining, compiling, and using the UNET model.
*   **OpenCV (cv2):** Used for image loading, resizing, and basic image manipulation.
*   **NumPy:** Used for numerical operations and handling image data as arrays.
*   **Matplotlib:** Used for displaying the original and enhanced images for comparison.
*   **Google Colab:** The environment where the notebook was developed and executed.

## How to Run
1.  **Open the notebook in Google Colab:** Upload or open the notebook file (.ipynb) in your Google Colab environment.
2.  **Install dependencies:** Ensure you have the necessary libraries installed. You can use the `requirements.txt` file generated earlier with `!pip install -r requirements.txt`.
3.  **Run all cells:** Execute all the code cells in the notebook sequentially from top to bottom. This will define the model, load and preprocess the example image, apply the model, and display the results.
4.  **Replace the example image:** To use your own image, replace the path `/content/Profile_Pic.jpg` in the "Image loading and preprocessing" section with the path to your desired low-resolution face image.

## Screenshots

**1. UNET Model Implementation**

<img width="440" height="183" alt="image" src="https://github.com/user-attachments/assets/a8401642-15bb-4e61-90ce-7d2df5b5cd19" />

**2. Post Processing Visualizations**

<img width="618" height="332" alt="image" src="https://github.com/user-attachments/assets/072d2a4f-c55f-466c-adfc-756ddd70044d" />
