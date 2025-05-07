# Audiology Centers Map

This application displays audiology centers in France on an interactive map using data from DataForSEO.

## Prerequisites

- Python 3.8 or higher
- DataForSEO API credentials

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd audiologia
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file with your DataForSEO credentials:
```
DATAFORSEO_LOGIN=your_login_here
DATAFORSEO_PASSWORD=your_password_here
```

## Running the Application

### Local Development

Run the Streamlit app:
```bash
streamlit run app.py
```

### Deployment

The application can be easily deployed to Streamlit Cloud:

1. Push your code to a GitHub repository
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Sign in with your GitHub account
4. Click "New app"
5. Select your repository, branch, and main file (app.py)
6. Add your environment variables (DATAFORSEO_LOGIN and DATAFORSEO_PASSWORD)
7. Click "Deploy"

## Features

- Interactive map of audiology centers in France
- Detailed information for each location
- Statistics about the data
- Real-time data fetching from DataForSEO

## Project Structure

- `app.py`: Main Streamlit application
- `client.py`: DataForSEO API client
- `requirements.txt`: Python dependencies
- `.env`: Environment variables (not included in repository) 