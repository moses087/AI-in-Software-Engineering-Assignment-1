# AI-in-Software-Engineering-Assignment-1
Quiz Questions:

What is TensorFlow, and what are its key features?

TensorFlow is an open-source machine learning framework developed by Google. It is widely used for deep learning, AI, and numerical computing across various platforms, including desktops, mobile devices, and the cloud.

Key Features:
✔ Open-Source & Scalable – Runs on CPUs, GPUs, and TPUs.
✔ Flexible & Easy to Use – Supports Python, C++, and JavaScript.
✔ High-Performance Computation – Uses computational graphs for efficient processing.
✔ Pre-trained Models & Transfer Learning – Access to ready-to-use models.
✔ Multi-Platform Deployment – TensorFlow Lite (mobile), TensorFlow.js (web), TensorFlow Serving (production).
✔ Integrated with Google Cloud & Other Tools – Works well with TensorBoard, Keras, and PyTorch.


What is the main difference between TensorFlow and PyTorch in terms of computation graphs?

The key difference between TensorFlow and PyTorch in terms of computation graphs lies in how they handle graph construction. TensorFlow uses a static computation graph, meaning you must define the entire graph before running it. This approach, often called "define-and-run," allows for better optimization and efficient execution, especially in deployment scenarios. However, it can be more challenging to debug since changes require rebuilding the graph.

On the other hand, PyTorch uses a dynamic computation graph, following a "define-by-run" approach. This means the graph is created on the fly as operations are executed, making it more flexible and intuitive, especially for debugging and research purposes. Since the graph is rebuilt at every iteration, PyTorch is often preferred for applications that require varying input sizes, such as recurrent neural networks (RNNs).

What is Keras, and on which frameworks can it run?

Keras is a high-level deep learning API designed for building and training neural networks easily. It provides a simple, modular, and user-friendly interface, making deep learning more accessible.

Frameworks Keras Can Run On:
TensorFlow (default backend)
Microsoft CNTK (deprecated)
Theano (no longer maintained)
PlaidML (for OpenCL support)
Since TensorFlow 2.0, Keras is integrated as tf.keras, making TensorFlow its primary backend. 


What are the key features of Scikit-learn?

Easy-to-use API for machine learning tasks.
Supports supervised & unsupervised learning (classification, regression, clustering).
Built-in data preprocessing (scaling, encoding, imputation).
Model selection & evaluation (cross-validation, grid search).
Seamless integration with NumPy and SciPy.
Dimensionality reduction (PCA, t-SNE).
Feature selection to improve model performance.
Ensemble methods (Random Forest, AdaBoost).
Scalable for small to medium datasets.
Open-source & well-documented for easy learning.

What is the purpose of Jupyter Notebooks, and what are its key features?

Jupyter Notebooks are an interactive computing environment used for data analysis, machine learning, and scientific computing. They allow users to write and execute code, visualize data, and document their work in a single document.

Key Features:
✔ Supports Multiple Languages – Primarily Python but also R, Julia, and more.
✔ Interactive Code Execution – Run code in cells and see outputs instantly.
✔ Rich Visualizations – Supports Matplotlib, Seaborn, and other plotting libraries.
✔ Markdown Support – Add formatted text, equations, and explanations.
✔ Easy Sharing – Export to HTML, PDF, or share via GitHub.
✔ Extensible – Supports widgets, extensions, and cloud integration.

In the TensorFlow example provided, what is the purpose of the Dropout layer in the neural network?

The Dropout layer in TensorFlow is used to prevent overfitting in a neural network by randomly setting a fraction of input neurons to zero during training. This forces the model to learn more robust features rather than relying too much on specific neurons.

Purpose of Dropout:
✔ Reduces Overfitting – Prevents the network from becoming too dependent on certain neurons.
✔ Improves Generalization – Helps the model perform better on unseen data.
✔ Regularization Technique – Acts like an ensemble method by training different parts of the network in each iteration.

What is the role of the optimizer in the PyTorch example, and which optimizer is used?

The optimizer in PyTorch is responsible for updating the model's parameters (weights and biases) to minimize the loss function during training. It adjusts these parameters using gradients computed through backpropagation, helping the model learn and improve over time

In the Keras example, what is the purpose of the Conv2D layer?

The Conv2D layer in Keras is used in convolutional neural networks (CNNs) for feature extraction from image data. It applies convolutional filters to detect patterns such as edges, textures, and shapes in an image.

What type of model is used in the Scikit-learn example, and what dataset is it applied to?

What is the output of the Jupyter Notebook example, and which library is used to generate the visualization?

The output of the Jupyter Notebook example depends on the code executed. If the example involves data visualization, the output would be a graph or chart.

A common visualization in Jupyter Notebooks is created using Matplotlib, a popular plotting library in Python.




