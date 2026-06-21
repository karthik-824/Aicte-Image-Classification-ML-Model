# Aicte-Image-Classification-ML-Model
#  Implementation of ML Model for Image Classification

##  Project Overview
This project focuses on building an image classification application using pre-trained deep learning models. It was developed as part of the **AICTE Internship on AI: Transformative Learning**, a joint CSR initiative by **Microsoft & SAP (TechSaksham)**.

The application addresses the need for accurate and efficient image recognition by leveraging **MobileNetV2** (for general-purpose classification) and a custom-trained **CIFAR-10** model (for specific object recognition). The solution is deployed as a user-friendly web application using **Streamlit**.

[** Try the Live App on Streamlit **](https://karthik-kuru-edunet-internship-ml-image-classifier.streamlit.app/)

##  Objectives
* **Develop an Image Classification System:** Automatically recognize and sort different types of images.
* **Improve Accuracy:** Ensure identification with minimal errors using robust models.
* **Enhance Efficiency:** Reduce manual effort in analyzing large datasets.
* **Real-World Application:** Applicable in healthcare, security, e-commerce, and autonomous driving.

##  System Architecture & Methodology
The project follows a structured pipeline:
1.  **Data Collection & Preprocessing:** Resizing, normalization, and augmentation of images.
2.  **Model Selection:** Utilizing CNN architectures (MobileNetV2 and CIFAR-10).
3.  **Training:** Training the custom model on the CIFAR-10 dataset.
4.  **Deployment:** Hosting the model via Streamlit Cloud for real-time inference.

##  Technologies Used
* **Language:** Python
* **Frontend:** Streamlit
* **Deep Learning Frameworks:** TensorFlow, Scikit-learn
* **Model Architectures:** Convolutional Neural Networks (CNN), MobileNetV2
* **Hardware:** GPU-enabled setup

##  Key Results
The application allows users to upload images and receive instant predictions with confidence scores.
* **MobileNetV2:** Achieves high accuracy for diverse, general-purpose images.
* **CIFAR-10 Model:** Effectively classifies objects into 10 predefined classes (e.g., Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck).

**Example Performance:**
* *Dog Classification:* 99.94% Confidence (CIFAR-10)
* *Cat Classification:* 85.75% Confidence (CIFAR-10)

##  How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/karthik-824/Aicte-Image-Classification-ML-Model.git](https://github.com/karthik-824/Aicte-Image-Classification-ML-Model.git)
    ```

2.  **Install dependencies:**
    ```bash
    pip install tensorflow streamlit scikit-learn numpy pillow
    ```

3.  **Run the App:**
    ```bash
    streamlit run app.py
    ```

##  Future Scope
* **Fine-tuning:** Allow users to fine-tune models on their own datasets.
* **Explainability:** Add heatmaps to highlight image areas influencing predictions.
* **Edge Optimization:** Optimize models for mobile and edge devices.

##  Acknowledgements
* **TechSaksham:** A joint CSR initiative of Microsoft & SAP.
* **Abdul Aziz MD:** Master Trainer, Edunet Foundation, for guidance and mentorship.

##  Author
**[Karthik Kuru](https://www.linkedin.com/in/karthikkuru/)**
