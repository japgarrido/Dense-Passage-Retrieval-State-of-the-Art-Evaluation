# DPR State-of-the-Art Analysis

This repository contains the **DPR_State_of_the_Art_Analysis.ipynb** notebook, which explores Dense Passage Retrieval (DPR), a cutting-edge retrieval model designed for open-domain question answering. The project evaluates DPR's performance on benchmark datasets and compares its efficiency.

---

## Project Summary

DPR utilizes dense embeddings to map questions and passages into a shared vector space, enabling efficient and accurate retrieval. This project focuses on:

1. **Testing several DPR's state-of-the-art architectures**

2. **Performance Evaluation**:
   - Benchmark testing on datasets like TREC-Covid and MSMARCO.
   - Analysis of retrieval accuracy and latency.

4. **Visualization and Analysis**:
   - Visualization of retrieval metrics.

---

## How to Load the Notebook in Google Colab

To run the **DPR_State_of_the_Art_Analysis.ipynb** notebook in Google Colab, follow these steps:

### 1. Open Google Colab
- Navigate to [Google Colab](https://colab.research.google.com).

### 2. Upload the Notebook
- Download the `DPR_State_of_the_Art_Analysis.ipynb` file from this repository.
- In Google Colab, click on **File > Upload Notebook**.
- Select the downloaded notebook file.

### 3. Link to Your Google Drive (Optional)
- To save outputs or load datasets from your Google Drive, run the following code in the first cell:
  ```python
  from google.colab import drive
  drive.mount('/content/drive')
  ```

### 4. Install Required Libraries
Ensure you install all dependencies listed in the notebook.

### 5. Run the Notebook
Execute cells sequentially to load models, datasets, and perform the analysis.

---

## License
This project is licensed under the GPLv3 License. See the LICENSE file for more details.
