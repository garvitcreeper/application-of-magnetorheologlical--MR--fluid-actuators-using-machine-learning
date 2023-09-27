<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    .content {
      max-width: 800px;
      margin: auto;
    }
  </style>
</head>
<body>
  <div class="content">
    <h1>Magnetorheological Fluid Actuators using Machine Learning</h1>
    <h2>Introduction</h2>
    <p>
      This GitHub repository contains the work done as part of a Bachelor's Thesis Project (BTP) focused on the application of Magnetorheological (MR) fluid actuators using machine learning techniques. The project involves the extraction and analysis of hysteresis loops obtained from numerical models and experiments, with subsequent data processing and utilization of Support Vector Regression (SVR) to predict force values.
    </p>
    <h2>Project Details</h2>
    <ul>
      <li>The hysteresis loops were obtained from experiments conducted at different frequencies and currents:
        <ul>
          <li>(a) f=0.5 Hz, I=1 A</li>
          <li>(b) f=1.5 Hz, I=0.3 A</li>
          <li>(c) f=3.5 Hz, I=0.6 A</li>
        </ul>
      </li>
      <li>Data Extraction:
        <ul>
          <li>Graphs were processed to extract data points using contour detection techniques.</li>
          <li>Interpolation was applied to increase the number of data points.</li>
        </ul>
      </li>
      <li>Data Preparation:
        <ul>
          <li>The extracted data was arranged and combined into a single dataset, consisting of 3 images of graphs.</li>
        </ul>
      </li>
      <li>Machine Learning Approach:
        <ul>
          <li>Support Vector Regression (SVR) was employed to predict force values based on features like velocity, frequency, and current.</li>
        </ul>
      </li>
    </ul>
    <h2>How to Use this Repository</h2>
    <ul>
      <li><strong>Data Extraction and Processing:</strong> The code for data extraction and processing is not provided in this repository but was utilized to create the combined dataset.</li>
      <li><strong>SVR Model Training:</strong> The SVR model training and evaluation code is provided in the repository (svr_model.ipynb). The code demonstrates how to:
        <ul>
          <li>Load and preprocess the dataset.</li>
          <li>Perform hyperparameter tuning using GridSearchCV.</li>
          <li>Train the SVR model and evaluate its performance.</li>
        </ul>
      </li>
    </ul>
    <h2>Repository Structure</h2>
    <ul>
      <li><code>Combined_Data - Sheet1_1.csv</code>: Combined dataset containing extracted and interpolated data.</li>
      <li><code>svr_model.ipynb</code>: Jupyter Notebook containing code for SVR model training and evaluation.</li>
      <li><code>README.md</code>: This file providing an overview of the project.</li>
    </ul>
    <h2>Ongoing Project</h2>
    <p>
      This project is ongoing, and further updates and improvements will be made in the future. Stay tuned for more developments and enhancements to the machine learning model for MR fluid actuators.
    </p>
  </div>
</body>
</html>
