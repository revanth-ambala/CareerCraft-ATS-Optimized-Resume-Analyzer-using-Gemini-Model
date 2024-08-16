# CareerCraft: ATS-Optimized Resume Analyzer using Gemini Model

CareerCraft is a cutting-edge ATS (Applicant Tracking System) Optimized Resume Analyzer designed to enhance the job application process using advanced technology. This project leverages the Gemini Pro model from Google to analyze resumes against job descriptions, suggest missing keywords, and provide tailored profile summaries for optimal presentation to potential employers.

## Features

- **Resume Optimization:** Analyze job descriptions and resumes to determine the percentage match, suggest missing keywords, and provide recommendations for improved alignment with job roles.
- **Skill Enhancement:** Identify skill gaps compared to industry standards and receive personalized suggestions for skill development.
- **Career Progression Guidance:** Get insights into potential career paths, relevant skills, and recommendations for career advancement.

## Technical Architecture

### Project Structure

- `images/` - Contains images used in the user interface.
- `.env` - Stores the Google API key securely.
- `app.py` - Main application file containing both the model and Streamlit UI code.
- `requirements.txt` - Lists required libraries for installation.

### Libraries

- `streamlit` - Framework for building interactive web applications with Python.
- `streamlit_extras` - Additional utilities for Streamlit applications.
- `google-generativeai` - Client library for accessing the GenerativeAI API.
- `python-dotenv` - Manages environment variables from a `.env` file.
- `PyPDF2` - For extracting text from PDF documents.
- `Pillow` - Imaging library for handling various image file formats.


## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/revanth-ambala/CareerCraft: ATS-Optimized Resume Analyzer using Gemini Model.git
   cd careercraft
   
2. **Create the Virtual Environment:**
   To create a virtual environment for the project, follow these steps:
   ```bash
   python -m venv venv

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt

4. **Configure Google API Key:**

   Generate a Google API key by following these instructions.
   Create a .env file in the root directory and add your API key:
   ```makefile
   GOOGLE_API_KEY = "your_api_key_here"

## Usage

1. **Launch the Application:**
    ```bash
    streamlit run app.py 
2. **Access the Application:**
    Open your web browser and go to http://localhost:8501 to view the application.
3. **Testing:**
 - **Input 1:** Paste a job description and upload a resume to see the generated output.
 - **Input 2:** Test with different job descriptions and resumes.
 - **Input 3:** Continue testing with additional examples.

