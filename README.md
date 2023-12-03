# LauzHack: Extracting Insights from Amazon Customer Reviews

## Members of Team LeNi
- Lennard Schaub
- Nils Fleischmann

## Overview
In this hackathon, our team tackled Amazon's challenge of extracting valuable insights from customer reviews. Our journey involved a series of analytical steps and the use of cutting-edge technologies to transform raw data into meaningful information.

## Process

### Dataset Exploration
Our initial step was to thoroughly explore the dataset to understand its structure and content. This phase was crucial for guiding our subsequent analytical strategies.

### Analysis and Extraction
We dived into the reviews, focusing on identifying the strengths and problems of products. Our approach was asynchronous, ensuring efficiency and depth in our analysis.

### Choice of Embeddings
After experimenting with different embeddings like MiniLM and MPNet, we opted for GPT embeddings. This decision was based on the superior contextual understanding offered by GPT.

### Dimensionality Reduction
For dimensionality reduction, we employed openTSNE, a state-of-the-art technique. Although UMAP was considered, openTSNE was chosen for its effectiveness in preserving data structure in a lower-dimensional space.

### Kmeans Clustering
We clustered the embedded data about product strengths and problems using Kmeans. Opting for a higher 'k' allowed us to capture a wide array of issues. Post clustering, we manually grouped these issues for better clarity and insight.

### Naming Clusters
An innovative approach was adopted for naming clusters. We sampled descriptions from data points and leveraged GPT's capabilities to label them accurately and meaningfully.

## Visualization Tools

### Plotly Dashboard
Our dashboard, created with Plotly, offers a user-friendly interface for exploring the data. It allows users to select products and compare the frequency of problem clusters with competitors in the same price range.

### Detailed Data Views
For an in-depth analysis, we developed an interactive scatterplot. This plot showcases problem clusters for each product along with their tSNE embeddings. Features like hovering over data points for descriptions and lasso selection for a detailed view enhance the user experience.

### Strengths Analysis
Similar to problem visualization, we also implemented plots for product strengths. Users can interact with the data, selecting specific points to gain more insights.

### Incomplete Feature: Product Improvement Tool
Our vision for a tool that suggests improvements to products based on issue analysis remains incomplete. This tool aims to predict the potential impact on ratings from addressing these issues.

---

This project was a challenging yet enriching experience. By leveraging advanced NLP techniques and interactive data visualization tools, we have developed a comprehensive framework to extract and present key insights from customer reviews, paving the way for data-driven decision-making in product development and marketing strategies.
