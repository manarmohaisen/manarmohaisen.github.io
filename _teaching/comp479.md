---
title: "COMP 479: Machine Learning"
collection: teaching
type: "Graduate course"
permalink: /teaching/comp479
venue: "Loyola University Chicago"
date: 2025-01-01
location: "Chicago, Illinois, United States"
---

Topics include a wide variety of supervised learning methods, both regression and classification, with an emphasis on those that perform well on large feature sets.

Lectures  and In-class Labs
======
<table style="width:100%; border-collapse: collapse; font-size: 90%; margin: 1em 0;">
  <thead>
    <tr style="background-color: #0077cc; color: white;">
      <th style="padding: 10px; text-align: left;">Module</th>
      <th style="padding: 10px; text-align: left;">Content</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #f9f9f9;">
      <td style="padding: 10px;">Machine Learning Types and Project Lifecycle</td>
      <td style="padding: 10px;">
        <ul>
  <li><strong>Introduction to Machine Learning</strong>: Definition, goals, and core concepts of ML.</li>
  <li><strong>Types of Learning</strong>: Supervised, unsupervised, semi-supervised, and reinforcement learning.</li>
  <li><strong>Machine Learning Project Lifecycle</strong>: From business problem framing to deployment, monitoring, and maintenance.</li>
  <li><strong>Data Engineering Pipeline</strong>: Collection, transformation, ingestion, and storage.</li>
  <li><strong>Machine Learning Pipeline</strong>: Data preprocessing, feature engineering, model selection and training, model evaluation, model deployment, and model monitoring and maintenance.</li>
  <li><strong>Data File Formats</strong>: JSON, XML, CSV, Avro, Pickle, Parquet, Numpy, etc.</li>
  <li><strong>Databases</strong>: Relational and NoSQL databases, </li>
  <li><strong>ETL vs. ELT</strong>: Extract-Transform-Load versus Extract-Load-Transform.</li>
  <li><strong>Data-related Roles</strong>: Overview of roles (Data Analyst, Data Engineer, Data Scientist, and ML Engineer).</li>
</ul>
        <strong>In-class Labs</strong>:
        <ul>
        <li>Lab 1: Data integration and analysis</li>
        <li>Lab 2: Extract, Transform, and Load (ETL)</li>
        </ul>
      </td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="padding: 10px;">Crash Course in Programming for Machine Learning (Python)</td>
      <td style="padding: 10px;">
<ul>
  <li><strong>Getting Started with Python</strong>: Setting up Python, running scripts, and basic syntax.</li>
  <li><strong>Supported Programming Paradigms</strong>: Procedural, object-oriented, and functional programming.</li>
  <li><strong>Built-in Types</strong>: Integer (<code>int</code>), Boolean (<code>bool</code>), and Floating point (<code>float</code>).</li>
  <li><strong>Looping and Branching</strong>: <code>for</code> loops, <code>while</code> loops, <code>if</code>/<code>elif</code>/<code>else</code> statements.</li>
  <li><strong>Built-in Collections</strong>: <code>list</code>, <code>tuple</code>, <code>set</code>, <code>dict</code>, <code>bytes</code>, and <code>bytearray</code>.</li>
  <li><strong>Functions</strong>: Defining, calling, arguments, return values, and scope.</li>
  <li><strong>Concrete Classes</strong>: Class definitions, instantiation, attributes, and methods.</li>
  <li><strong>File I/O</strong>:Reading from and writing to files.</li>
  <li><strong>Necessary Packages</strong>: Overview of NumPy, Pandas, SciPy, and Matplotlib.</li>
  <li><strong>Other Selected Topics</strong>: Additional Python features and concepts for advanced use.</li>
</ul>
        <strong>In-class Labs</strong>:
        <ul>
          <li>Lab 3: Python for data scientists</li>
        </ul>
      </td>
    </tr>
    <tr style="background-color: #f9f9f9;">
      <td style="padding: 10px;">Review of Probability, Calculus, and Linear Algebra</td>
      <td style="padding: 10px;">
<ul>
  <li><strong>Randomness in Machine Learning</strong>: Role of randomness in algorithms, initialization, and sampling.</li>
  <li><strong>Probability and Random Variables</strong>: Fundamentals of probability theory and types of random variables.</li>
  <li><strong>Entropy</strong>: Measure of uncertainty and its role in information theory and machine learning.</li>
  <li><strong>Basic Operations on Matrices and Vectors</strong>: Addition, multiplication, transposition, and inversion.</li>
  <li><strong>Capital Sigma (Σ) and Pi (Π) Notations</strong>: Summation and product notation for mathematical expressions.</li>
  <li><strong>Local and Global Maxima and Minima</strong>: Concepts in optimization and their importance in ML algorithms.</li>
  <li><strong>Min/Max and Arg Min/Max</strong>: Finding extreme values and their corresponding indices or arguments.</li>
  <li><strong>Similarity Measures</strong>: Techniques such as cosine similarity, Euclidean distance, and correlation.</li>
  <li><strong>Derivative, Gradient, and the Chain Rule</strong>: Core calculus concepts for optimization in ML models.</li>
</ul>
        <strong>In-class Labs</strong>:
        <ul class="labs-list">
          <li>Lab 4: Introduction to statistics</li>
          <li>Lab 5: Web scraping using Pandas</li>
          <li>Lab 6: Web scraping using Beautiful Soup</li>
        </ul>
      </td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="padding: 10px;">Supervised Learning (Regression)
</td>
      <td style="padding: 10px;">
<ul>
  <li><strong>Regression Techniques</strong>: Linear and polynomial regression for predictive modeling.</li>
  <li><strong>Overfitting and Underfitting</strong>: Concepts, detection, and mitigation strategies.</li>
  <li><strong>Regularization Methods</strong>: Ridge, Lasso, and Elastic Net.</li>
  <li><strong>Gradient Descent Variants</strong>: Batch, mini-batch, and stochastic approaches for optimization.</li>
</ul>
       <strong>In-class Labs</strong>:
        <ul class="labs-list">
          <li>Lab 7: Detailed implementation of a single-feature linear regression</li>
          <li>Lab 8: Polynomial regression</li>
          <li>Lab 9: Introduction to Python classes</li>
        </ul>
      </td>
    </tr>
  <tr style="background-color: #f9f9f9;">
      <td style="padding: 10px;">Supervised Learning (Classification)</td>
      <td style="padding: 10px;">
<ul>
  <li><strong>Classification Models</strong>: Perceptron, Adaline, Logistic Regression, Naïve Bayes.</li>
  <li><strong>Support Vector Machines (SVM)</strong>: Hard-margin, soft-margin, and kernel-based approaches.</li>
  <li><strong>Tree-based Methods</strong>: Decision Trees, Random Forests.</li>
  <li><strong>Instance-based Learning</strong>: K-nearest Neighbors (KNN).</li>
  <li><strong>Ensemble Learning</strong>: Bagging, Boosting, AdaBoost, hard vs. soft majority voting.</li>
  <li><strong>Multiclass Classification</strong>: Strategies for extending binary classifiers.</li>
  <li><strong>Evaluation Metrics</strong>: Confusion matrix, precision, recall, F1-score, cost-sensitive metrics, ROC AUC.</li>
</ul>
        <strong>In-class Labs</strong>:
        <ul class="labs-list">
          <li>Lab 10: Perceptron, Adaboost, Logistic Regression</li>
          <li>Lab 11: Boosting algorithms (XGBoost, LightGBM, and CatBoost)</li>
        </ul>
      </td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="padding: 10px;">Feature Engineering and Performance Assessment</td>
      <td style="padding: 10px;">
     <ul>
  <li><strong>Anatomy of a Learning Algorithm</strong> – Key components and workflow.</li>
  <li><strong>Data Splits</strong> – Training, validation, and test sets.</li>
  <li><strong>Model Performance Concepts</strong> – Approximation, generalization, and the bias-variance tradeoff.</li>
  <li><strong>Data Preprocessing</strong> – Handling missing data, scaling, discretization, and encoding categorical features.</li>
  <li><strong>Data Leakage</strong> – Understanding and preventing information leakage between datasets.</li>
  <li><strong>Feature Importance & Selection</strong> – Techniques including:
    <ul>
      <li>Dropping columns with many missing values</li>
      <li>Dropping features with low variance</li>
      <li>Backward and forward feature selection</li>
      <li>Recursive feature elimination</li>
      <li>Filter-based methods (Pearson’s r, Chi-squared, Spearman’s Rho, mutual information, ANOVA F-score)</li>
      <li>Embedded methods (LASSO, positive LASSO regression, XGBoost)</li>
    </ul>
  </li>
</ul>
       <strong>In-class Labs</strong>:
        <ul class="labs-list">
          <li>Lab 12: Hyperparameter tuning</li>
          <li>Lab 13: Time series prediction (stock market forecasting)</li>
          <li>Lab 14: Feature selection</li>
        </ul>
      </td>
    </tr>
      <tr style="background-color: #f9f9f9;">
      <td style="padding: 10px;">Unsupervised Learning</td>
      <td style="padding: 10px;">
        <ul>
  <li><strong>Unsupervised Learning Use Cases</strong>: Applications in pattern discovery, anomaly detection, and data exploration.</li>
  <li><strong>Clustering Methods</strong> – 
    <ul>
      <li>Prototype-based: K-means</li>
      <li>Hierarchical: Agglomerative and divisive clustering</li>
      <li>Density-based: DBSCAN, HDBSCAN</li>
    </ul>
  </li>
  <li><strong>Dimensionality Reduction</strong>:
    <ul>
      <li>Principal Component Analysis (PCA)</li>
      <li>Kernel PCA (KPCA)</li>
      <li>Overview of the Linear Discriminant Analysis (LDA)</li>
    </ul>
  </li>
  <li><strong>Market Basket Analysis & Association Rules</strong>: Discovering relationships between items in transactional datasets.</li>
</ul>
       <strong>In-class Labs</strong>:
        <ul class="labs-list">
          <li>Lab 15: Clustering and principal component analysis</li>
        </ul>
      </td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="padding: 10px;">Introduction to Shallow and Deep Neural Networks</td>
      <td style="padding: 10px;">
<ul>
  <li><strong>Shallow Neural Networks</strong>: Basic architecture with input, hidden, and output layers.</li>
  <li><strong>Deep Neural Networks (DNNs)</strong>: Multi-layer architectures.</li>
  <li><strong>Key Concepts</strong>: Neurons, weights, biases, activation functions.</li>
  <li><strong>Forward Propagation</strong>: Flow of data through the network for predictions.</li>
  <li><strong>Backpropagation</strong>: Gradient-based optimization for training neural networks.</li>
  <li><strong>Common Activation Functions</strong>: Sigmoid, tanh, ReLU, and softmax.</li>
  <li><strong>Use Cases</strong>: Regression, image recognition, natural language processing, with focus on classification.</li>
</ul>
      <strong>In-class Labs</strong>:
        <ul class="labs-list">
          <li>Lab 16: Tensors using PyTorch</li>
          <li>Lab 17: Shallow neural networks</li>
          <li>Lab 18: Feedforward neural networks</li>
        </ul>
      </td>
    </tr>
     <tr style="background-color: #f9f9f9;">
      <td style="padding: 10px;">Introduction to Convolutional Neural Networks</td>
      <td style="padding: 10px;">
        <ul>
  <li><strong>Overview of CNNs</strong>: Processing grid-like data, including images.</li>
  <li><strong>Convolutional Layers</strong>: Filters/kernels feature extraction.</li>
  <li><strong>Pooling Layers</strong>: Max pooling and average pooling downsampling.</li>
  <li><strong>Fully Connected Layers</strong>: Combining extracted features for classification or regression tasks.</li>
  <li><strong>Activation Functions</strong></li>
  <li><strong>Use cases</strong>: Image recognition, object detection, medical imaging, and malware analysis.</li>
</ul>
        <strong>In-class Labs</strong>:
        <ul class="labs-list">
          <li>Lab 19: Basic convolutional neural network</li>
        </ul>
      </td>
    </tr>
    <tr style="background-color: #ffffff;">
      <td style="padding: 10px;">Introduction to Transfer Learning</td>
      <td style="padding: 10px;">
<ul>
  <li><strong>Overview of Transfer Learning</strong>: Leveraging pre-trained models to solve related tasks.</li>
  <li><strong>Benefits of Transfer Learning</strong>: Reduced training time, improved performance with limited data, and lower computational cost.</li>
  <li><strong>Common Approaches</strong>: 
    <ul>
      <li>Feature extraction using pre-trained models</li>
      <li>Fine-tuning model's partial subset of the weights for the target task</li>
    </ul>
  </li>
  <li><strong>Popular Pre-trained Models</strong>: Examples include VGG, ResNet, EfficientNet, BERT, and GPT.</li>
  <li><strong>Applications</strong>: Computer vision, natural language processing, and medical diagnostics.</li>
</ul>
       <strong>In-class Labs</strong>:
        <ul class="labs-list">
          <li>Lab 20: Pretrained models and transfer learning</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
  </tbody>
</table>
