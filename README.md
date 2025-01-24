
## Groupe:
* Aboubacar Sidik SANOGO
* Aminata Mah NDIAYE

* 
# Streamlit Chatbot Application

This repository contains a chatbot application built with **Streamlit** and **OpenAI's API**. The project is designed to provide a simple and interactive chat interface for users, leveraging OpenAI's natural language processing capabilities.

---

## 🛠️ Project Structure

```plaintext
├── .streamlit/          # Streamlit configuration files (e.g., theme settings)
├── chatbot.py           # Main chatbot script
├── chatbotgpt.py        # Alternate chatbot implementation with OpenAI
├── requirements.txt     # Python dependencies
├── LICENSE              # License for the project
├── README.md            # Documentation (you are here)
└── .gitignore           # Git ignored files

🚀 How to Run the Application
1. Clone the Repository
Clone the repository to your local machine using:

bash
Copier
Modifier
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
2. Set Up a Virtual Environment
It is recommended to use a virtual environment to isolate the dependencies:

bash
Copier
Modifier
python -m venv .venv
source .venv/bin/activate       # On macOS/Linux
.venv\Scripts\activate          # On Windows
3. Install Dependencies
Install the required Python packages using:

bash
Copier
Modifier
pip install -r requirements.txt
4. Configure API Keys
Create a file named secrets.toml in the .streamlit/ folder:
plaintext
Copier
Modifier
.streamlit/secrets.toml
Add your OpenAI API key to this file:
toml
Copier
Modifier
[default]
api_key = "sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
Note: For deployments on Streamlit Cloud, configure your secrets in the app settings under the "Secrets" section.

5. Run the Application
Execute the Streamlit application:

bash
Copier
Modifier
streamlit run chatbot.py
or

bash
Copier
Modifier
streamlit run chatbotgpt.py
6. Access the Application
The application will launch in your default web browser.
If not, open http://localhost:8501 manually.
📄 Requirements
Make sure you have the following installed:

Python 3.8 or later
The dependencies listed in requirements.txt
To regenerate the requirements.txt file after adding new dependencies:

bash
Copier
Modifier
pip freeze > requirements.txt
🛡️ License
This project is licensed under the terms of the MIT License.

🤝 Contributing
Fork the repository.
Create a feature branch (git checkout -b feature-name).
Commit your changes (git commit -m "Add some feature").
Push to the branch (git push origin feature-name).
Open a pull request.
📧 Support
If you encounter any issues, feel free to open an issue or contact me at <your-email>.

🌟 Acknowledgments
Streamlit Documentation
OpenAI API Documentation
vbnet
Copier
Modifier

### Points to Remember:
1. Replace `<your-username>` and `<repository-name>` with the actual values from your GitHub repository.
2. Replace `<your-email>` with your contact email if you want to include it.
3. Test the steps locally to ensure the instructions are accurate.

Let me know if you'd like adjustments or additions! 😊
