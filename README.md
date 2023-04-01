# README.md

## Adding Metadata to a CSV File: Three Methods for Generating a Knowledge Graph

This repository demonstrates how to add metadata to a CSV file using three different methods. Each method is provided in a separate Jupyter notebook to facilitate a clear understanding of the process. The CSV file has the following structure:

| id  | name  | age | city        |
| --- | ----- | --- | ----------- |
| 1   | Alice | 30  | New York    |
| 2   | Bob   | 25  | Los Angeles |
| 3   | Carol | 22  | Chicago     |

### Method 1: Using RML and a vocab.ttl File

This method uses RDF Mapping Language (RML) and a vocabulary file (vocab.ttl) to generate a Knowledge Graph from the CSV file. The Jupyter notebook `Method1_RML_Vocab.ipynb` provides a step-by-step guide on how to create the RML mapping file and the vocabulary file, as well as how to execute the RML mapping and generate the resulting Knowledge Graph.

### Method 2: Using CSV on the Web (CSVW)

The second method utilizes the CSV on the Web (CSVW) approach to describe the CSV file and generate both JSON and JSON-LD representations. The JSON-LD context is used to generate a Knowledge Graph. The Jupyter notebook `Method2_CSVW.ipynb` demonstrates how to create a CSVW metadata file, convert the CSV to JSON and JSON-LD, and finally generate the Knowledge Graph.

### Method 3: Using Pandas, RDFLib, and Python

The third method involves using the Pandas library to load the CSV file, RDFLib to generate a Knowledge Graph, and Python to perform the necessary data manipulation. The Jupyter notebook `Method3_Pandas_RDFLib.ipynb` explains how to

## Installation amd Setup

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/csv-metadata-to-knowledge-graph.git
```

2. Navigate to the project folder:

```
cd csv-metadata-to-knowledge-graph
```

3. Create and activate a virtual environment (optional, but recommended):

```bash
python3 -m venv venv
source venv/bin/activate  # For Linux/MacOS
venv\Scripts\activate  # For Windows
```

4. Install the required Python packages:

```bash
pip install -r requirements.txt
```

5. Open the desired Jupyter notebook:

```bash
jupyter notebook
```

## Assistive AI Agents

In creating these Jupyter notebooks, we have incorporated the use of two cutting-edge AI language models as assistive agents: OpenAI's ChatGPT and Microsoft's Bing Chat. These AI agents helped generate examples, explain background information, and provide guidance throughout the process of adding metadata to the CSV file and generating a Knowledge Graph.

By integrating ChatGPT and Bing Chat, we aim to demonstrate the potential of AI-driven language models in simplifying complex tasks, automating parts of the process, and enhancing the overall learning experience.

## Contributing

We welcome contributions to this project! Please feel free to open an issue or submit a pull request if you have any suggestions, improvements, or fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

## Disclosure

This README.md file was generated with the assistance of OpenAI's ChatGPT, an advanced AI language model. By leveraging the capabilities of ChatGPT, we were able to create a clear, concise, and informative README that outlines the structure and purpose of this repository. ChatGPT played a significant role in structuring the content, providing relevant information, and ensuring the clarity of the README.md file.

The use of ChatGPT in generating this README.md demonstrates the potential of AI language models in facilitating and streamlining the creation of documentation and other written content.
