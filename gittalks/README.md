## Setup
### Prerequisites
- Python 3.6 or higher
- Streamlit
### Installation
### Clone the repository
```bash
git clone
```
### Change the directory
```bash
cd repochat-gemini-streamlit-master
```

### Create a python env
```bash
python3 -m venv env
```
### Activate the env
```bash
source env/bin/activate
```

### Install dependencies
```bash
pip install -r requirements.txt
```
### Get Gemini API Key
- Go to https://aistudio.google.com/app/apikey
- Create an api key

### Add Gemini API Key
- Create a directory in root named `.streamlit`
- Create a file named `credentials.toml` in `.streamlit`
- Add the following lines in `credentials.toml`
```toml
[api_keys]
API_KEY = "your_api_key_here
```
### Make sure to add secrets.toml in .gitignore

```bash
### Run the app from root directory
```bash
streamlit run app.py
```
### Open the app
Open the browser and go to http://localhost:8501
