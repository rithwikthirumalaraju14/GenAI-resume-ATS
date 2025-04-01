# ATS Resume Expert

## Project Overview

ATS Resume Expert is a Streamlit-based web application that evaluates resumes against job descriptions using Google Gemini AI. It provides insights into resume relevance, percentage match, and suggestions for improving ATS compliance. The tool leverages AI-driven resume parsing and assessment, making it a valuable resource for job seekers optimizing their resumes for Applicant Tracking Systems (ATS).

## Features

| Sl. No. | Feature Name                  | Description |
|---------|-------------------------------|-------------|
| 1       | **Resume Evaluation**         | Analyzes the resume against the job description and provides feedback on strengths and weaknesses. |
| 2       | **ATS Match Percentage**      | Computes a match percentage between the resume and job description, highlighting missing keywords. |
| 3       | **Resume Optimization**       | Suggests modifications to improve ATS compliance and outputs an optimized resume. |

## Prerequisites

Ensure you have the following installed before running the application:
- Python 3.8 or higher
- Google Gemini API key
- Required Python libraries (listed in `requirements.txt`)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/ats-resume-expert.git
   cd ats-resume-expert
   ```

2. **Set Up a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**:
   Create a `.env` file and add your Google API key:
   ```
   GOOGLE_API_KEY=your_api_key_here
   ```

## Running the Application

1. **Start the Streamlit App**:
   ```bash
   streamlit run app.py
   ```

2. **Access the Web Interface**:
   Open your browser and navigate to `http://localhost:8501/`.

## Usage

1. **Upload a Resume** (PDF format)
2. **Enter the Job Description**
3. **Choose an Option**:
   - **"Tell Me About the Resume"**: Get an AI-powered evaluation of resume strengths and weaknesses.
   - **"Percentage"**: Obtain a match percentage along with missing keywords.
   - **"Modify Resume"**: Get suggestions for ATS compliance and an optimized resume.

## Code Structure

- **app.py**: Main Streamlit application file.
- **requirements.txt**: List of dependencies.
- **.env**: Stores API key (not included in the repository for security reasons).

## Technology Stack

| Sl. No. | Technology            | Description |
|---------|----------------------|-------------|
| 1       | **Streamlit**        | A Python-based web framework for interactive applications. |
| 2       | **Google Gemini AI** | Used for text generation and resume evaluation. |
| 3       | **pdf2image**        | Converts PDF resumes to images for AI processing. |
| 4       | **PIL (Pillow)**     | Handles image processing tasks. |
| 5       | **dotenv**           | Loads environment variables securely. |

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact

For any inquiries or suggestions, feel free to reach out:
📧 Email: rithwik.t2003@gmail.com
