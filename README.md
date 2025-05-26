🌿 **Plant Disease Detection Using Deep Learning (CNN + Docker)**
📍 *Deep Learning | Computer Vision | Agriculture Tech | Dockerized ML Deployment*

In this project, I developed an end-to-end deep learning system to automatically detect and classify **plant leaf diseases** using **Convolutional Neural Networks (CNN)**. The model identifies diseases from leaf images with high accuracy, aiming to support precision agriculture and early intervention in crop management.

To ensure easy deployment and platform independence, the entire application was **containerized using Docker**, allowing seamless execution across environments without dependency issues.

---

### 🔍 **Project Highlights**

* ✅ Built a CNN model to classify various plant leaf diseases and healthy leaves.
* 📈 Achieved over 95% accuracy on a labeled dataset using Keras and TensorFlow.
* 📦 Containerized the entire workflow using Docker for reproducible and scalable deployment.
* 🛠️ Used Python, OpenCV, NumPy, Matplotlib, and Jupyter for development and experimentation.

---

### ⚙️ **How It Works**

1. **Dataset**: Images of plant leaves (healthy and diseased) from the PlantVillage dataset.
2. **Preprocessing**: Resized, normalized, and augmented input images to improve generalization.
3. **Model**: Custom CNN architecture trained with categorical cross-entropy loss.
4. **Evaluation**: Assessed using test accuracy, confusion matrix, and loss plots.
5. **Deployment**: Dockerized app that runs the trained model inside an isolated container.

---

### 🐳 **Docker Usage**

* Created a `Dockerfile` to package dependencies, model code, and runtime environment.
* Built and ran containers using simple CLI commands:

  ```bash
  docker build -t plant-disease-detector .
  docker run -p 5000:5000 plant-disease-detector
  ```
* Ensured portability and consistent behavior across different systems.

---

### 🚀 **Applications**

* Smart farming and early plant disease diagnostics
* Reduced dependency on manual inspection
* Scalable and portable solution for real-time field deployment

---

💬 *Excited to continue exploring AI for agriculture and computer vision for real-world impact. Let’s connect if you’re working on similar problems or want to collaborate!*


