## Getting Started

### 1. Clone the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/xcriminal1/AI_Agent.git
```

### 2. Set Up a Virtual Environment
To ensure that all dependencies are managed properly, it's recommended to set up a virtual environment:

For macOS/Linux:
```bash
python3 -m venv venv
source venv/bin/activate
```

For Windows:
```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Required Dependencies
After activating your virtual environment, install the necessary packages by running:
```bash
pip install -r requirements.txt
```

### 4. Obtain Groq Cloud API Key
To run the autonomous agent, you'll need an API key from Groq Cloud. Follow these steps to obtain one:

1. Visit the [Groq Console](https://console.groq.com/) website.
2. Sign up or log in to your account.
3. Navigate to the [API Keys](https://console.groq.com/keys) section in your account settings.
4. Click on "Create API Key".
5. Copy the generated API key.

### 5. Add Groq API Key to .env File
To keep your API key secure, you'll need to add it to a .env file in the root of the project:

1. In the root directory of the project, rename ```.env.local``` to ```.env```
2. Replace the ```GROQ_API_KEY``` with your <API_KEY>
```bash
GROQ_API_KEY=YOUR_API_KEY_HERE
```
## Run the Research Assistant
Once you've set up everything and customized your query, you can run the research assistant by executing the following command:

```bash
python research_assistant.py