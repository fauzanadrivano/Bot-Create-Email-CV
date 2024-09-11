# Bot Create Email and CV - Automated Email and CV Generator

This web application, built with Streamlit, uses Google PaLM (Pathways Language Model) API to automatically generate professional emails and CVs based on user input. It also includes multilingual translation features using the Google Translate API, supporting 10 UNESCO languages.

## Features

- **Automated Email and CV Generation:** Generates professional emails and CVs based on user prompts.
- **Multilingual Support:** Translates generated content into 10 different languages, including Indonesian, English, Spanish, French, Hindi, Russian, Italian, Portuguese, Arabic, and Mandarin.
- **Downloadable Outputs:** Provides the option to download the generated content as a Word document.
- **User-Friendly Interface:** Built with Streamlit, providing an easy-to-use web interface.

## Installation

To run the application locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/fauzanadrivano/Bot-Create-Email-CV.git
   cd Bot-Create-Email-CV
   
2. **Install Dependencies:**
   Ensure you have Python installed, then install the required packages using pip:
   ```bash
   pip install -r requirements.txt

3. **Set Up Google PaLM API:**
   - Obtain an API key from the Google Cloud Platform for PaLM (Pathways Language Model).
   - Update the palm.configure(api_key="YOUR_API_KEY") line in the code with your API key.
     
4. **Run the Application:**
   ```bash
   streamlit run app.py

## Usage

1. Select the Bot Option:
   - Choose either "Create E-Mail" or "Create CV" from the sidebar.
     
2. Input Your Prompt:
   - For email generation, use keywords like write email, compose email, create email, or email content.
   - For CV generation, use keywords like write cv, compose cv, or create cv.

3. Select Language:
   - Choose a language from the dropdown menu for translation.

4. Submit and Download:
   - Click "Submit" to generate content.
   - Click "Download Result as Word" to save the output as a Word document.
  
## Languages Supported

 - Indonesian, English, Spanish, French, Hindi, Russian, Italian, Portuguese, Arabic, Mandarin

## Acknowledgements
- Streamlit: For providing a simple yet powerful framework for creating web applications in Python.
- Google PaLM: For the generative AI capabilities to create emails and CVs.
- Google Translate: For the multilingual translation features.
