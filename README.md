<div align="center">
<pre>
 ██████╗██╗  ██╗ █████╗ ████████╗    ██╗    ██╗██╗████████╗██╗  ██╗    ██╗   ██╗██████╗ ██╗     
██╔════╝██║  ██║██╔══██╗╚══██╔══╝    ██║    ██║██║╚══██╔══╝██║  ██║    ██║   ██║██╔══██╗██║     
██║     ███████║███████║   ██║       ██║ █╗ ██║██║   ██║   ███████║    ██║   ██║██████╔╝██║     
██║     ██╔══██║██╔══██║   ██║       ██║███╗██║██║   ██║   ██╔══██║    ██║   ██║██╔══██╗██║     
╚██████╗██║  ██║██║  ██║   ██║       ╚███╔███╔╝██║   ██║   ██║  ██║    ╚██████╔╝██║  ██║███████╗
 ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝        ╚══╝╚══╝ ╚═╝   ╚═╝   ╚═╝  ╚═╝     ╚═════╝ ╚═╝  ╚═╝╚══════╝
                                                                                                
                                                                                                                   
                                                                                                                   
                                                                                                            
                                                                       
---------------------------------------------------
This is a Python program that allows the user to chat with websites.
</pre>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



![alt text](<docs/How it works.png>)




</div>

The Chat with URLs App is a Python-based application that enables interactions with the content of any provided website URL. By leveraging advanced language models and vector storage technologies, it interprets user queries in natural language and retrieves relevant information directly from the website's content, making it an invaluable tool for extracting knowledge without manual browsing.

1. Ensure that Python 3 is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. Clone this repository to your local machine:
bash
git clone https://github.com/rahal1cherif/RAG_CHAT_URL

3. (Optional) Set up a virtual environment:
bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
4. Install the required dependencies by running the following command: "pip install -r requirements.txt"

5. Obtain an API key from OpenAI and add it to the `.env` file in the project directory, use : OPENAI_API_KEY="your_secret_api_key"



## Usage

To use the Chat with Websites App:

1. Ensure that you have installed the required dependencies and added the OpenAI API key to the `.env` file.

2. Run the `app.py` file using the Streamlit CLI. Execute the following command: "streamlit run app.py"

3. The application will launch in your default web browser. Enter a website URL to begin chatting with the content of the website.

4. The app will dynamically load content from the provided URL and prepare it for interaction.

5. Ask questions or make inquiries in natural language. The app retrieves and presents information based on the website's content.

## Contributing

Contributions to the Chat with Websites App are highly encouraged! If you have ideas for new features or improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.


## Contact Information

For any questions or feedback, reach out at [rahal8cherif@gmail.com](mailto:rahal8cherif@gmail.com).
