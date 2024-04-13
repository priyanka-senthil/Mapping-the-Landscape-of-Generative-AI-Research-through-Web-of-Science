# Mapping-the-Landscape-of-Generative-AI-Research-through-Web-of-Science


In the rapidly evolving field of generative artificial intelligence (AI), identifying key research themes and understanding their interconnections is crucial for academics, practitioners, and policy makers. This project aims to utilize the comprehensive Web of Science (WoS) database to search for publications related to generative AI. Through an
analytical approach focused on keyword co-occurrence networks derived from author keywords, we will map the intellectual structure and identify the core themes and trends
in generative AI research. This project implements co-occurrence analysis between author keywords and article titles extracted from a dataset. The analysis aims to identify prevalent themes and topics across articles by examining the frequency of co-occurrence between titles and keywords.

## Project Structure

- **data/**: Contains the input dataset(s) in various formats.
- **results/**: Stores the output files, such as co-occurrence matrices and visualizations.

## Usage

1. **Data Preparation**: Place your dataset file(s) in the `data/` directory.
2. **Data Preprocessing**: If necessary, preprocess the data to ensure consistency and cleanliness.
3. **Co-occurrence Analysis**: Run the Python Notebook to perform co-occurrence analysis.
4. **Visualization**: Visualize the results using the provided scripts or tools of your choice.
5. **Interpretation**: Interpret the co-occurrence patterns to gain insights into the underlying themes and topics in the dataset.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- NetworkX
