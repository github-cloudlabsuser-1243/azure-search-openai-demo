# Azure Search OpenAI Demo

This repository contains a demo application that integrates Azure Search with OpenAI's GPT-3 to provide advanced search and natural language processing capabilities.

## Prerequisites

- Azure Subscription
- Azure Search Service
- OpenAI API Key
- Node.js

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/azure-search-openai-demo.git
    cd azure-search-openai-demo/app/backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Configure environment variables:
    Create a `.env` file in the `backend` directory and add the following:
    ```plaintext
    AZURE_SEARCH_API_KEY=your_azure_search_api_key
    AZURE_SEARCH_SERVICE_NAME=your_azure_search_service_name
    OPENAI_API_KEY=your_openai_api_key
    ```

4. Run the application:
    ```bash
    npm start
    ```

## Usage

- Access the application at `http://localhost:3000`
- Use the search bar to input queries and get responses powered by Azure Search and OpenAI.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [yourname@yourdomain.com](mailto:yourname@yourdomain.com).
