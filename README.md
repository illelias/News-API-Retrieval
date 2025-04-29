# News API Retrieval

## Overview
This project utilizes the OpenAI API and The Guardian API to fetch and analyze news articles related to specific topics. The code processes the data using Python and Pandas to extract useful insights from the retrieved news articles.

## Features
- Fetches news articles from The Guardian API
- Utilizes OpenAI API for additional text analysis
- Processes and organizes the data using Pandas
- Displays structured insights for further analysis

## Requirements
Ensure you have the following dependencies installed before running the notebook:

```bash
pip install requests pandas openai
```

## API Keys Setup
Before running the code, set up the necessary API keys:
- **OpenAI API Key**: Store it in `OPENAI_API_KEY`.
- **The Guardian API Key**: Store it in `NEWS_API_KEY`.

These should be set up using an environment variable or a secrets manager if running in a cloud environment like Google Colab.

## Running the Notebook
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd MiniProject1
   ```
3. Open the Jupyter Notebook and run the cells sequentially to fetch and analyze news data.

## Usage
- Modify the `health_query` variable to fetch news articles for different topics.
- Adjust API parameters to retrieve a different number of articles.
- Use Pandas to further analyze and visualize the data as needed.

## Contributing
If you'd like to contribute, feel free to submit a pull request or open an issue for discussions!

## License
This project is licensed under the MIT License.

