# Fine-Tuning LLM for SQL Query Generation

This repository is dedicated to fine-tuning the Phi-3 large language model (LLM) for the specific task of SQL query generation. The process involves using the 'unsloth' technique for enhanced performance.

## Overview

SQL query generation is a crucial task for many data-driven applications. By fine-tuning the Phi-3 LLM, we aim to improve its ability to generate accurate and efficient SQL queries based on natural language input.

## Contents

- `fine-tuning.ipynb`: Jupyter notebook detailing the fine-tuning process using the 'unsloth' method.
- `Article`: A comprehensive article explaining the methodology and results ([Link](https://medium.com/gopenai/bridging-the-gap-fine-tuning-phi-3-for-sql-query-generation-with-natural-language-queries-8fbe6a58b1ec)).
- `Dataset`: The dataset used for fine-tuning is available at b-mc2/sql-create-context.
- `Model`: The base model for fine-tuning can be found at unsloth/Phi-3-mini-4k-instruct.

## Getting Started

To replicate the fine-tuning process or to use the fine-tuned model:

1. Clone this repository:
   ```bash
   git clone https://github.com/imanoop7/fine-tuning-llm-for-SQL-query-generation/fine-tuning-llm-for-SQL-query-generation.git
2. ``` cd fine-tuning-llm-for-SQL-query-generation ```
3. Follow the instructions in ``` phi3_fine-tuning_on_sql_task.ipynb ``` to fine-tune the model on your dataset.
## Prerequisites
* Python 3.8+
* Jupyter Notebook
* Access to the Hugging Face platform
## Contributing
Your contributions are welcome! If you have suggestions or improvements, please fork the repo and submit a pull request, or create an issue.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
The Hugging Face team for providing the dataset and model hosting.
The developers of the ‘unsloth’ fine-tuning technique.
## Support
If you find this project useful, please consider giving it a star on GitHub. Your support helps us maintain and improve the project.
