# ai-career-coach
An AI-powered Career Coach built with IBM watsonx.ai, Gradio, and LLMs to polish resumes, generate personalized cover letters, and provide career advice.

The application provides three AI-powered tools:

- 📝 Resume Polisher
- 💌 Cover Letter Generator
- 🎯 Career Advisor

---

## Features

### Resume Polisher

Improve your resume for a specific job position.

- ATS-friendly improvements
- Better wording and grammar
- Stronger achievement statements
- Professional formatting suggestions

---

### Cover Letter Generator

Generate personalized cover letters based on:

- Company name
- Job title
- Job description
- Resume content

---

### Career Advisor

Receive personalized career recommendations including:

- Resume strengths
- Missing skills
- Resume improvement suggestions
- Career development advice
- Job match recommendations

---

## Built With

- Python
- IBM watsonx.ai
- IBM Watsonx AI SDK
- Gradio
- Large Language Models (LLMs)

---

## Project Structure

```text
.
├── resume_polisher.py
├── cover_letter_generator.py
├── career_advisor.py
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ai-career-coach.git

cd ai-career-coach
```

Create a virtual environment:

```bash
python -m venv my_env
```

Activate it:

### Linux / macOS

```bash
source my_env/bin/activate
```

### Windows

```bash
my_env\Scripts\activate
```



---

## Configuration

Update your IBM watsonx.ai credentials:

```python
credentials = Credentials(
    apikey="YOUR_API_KEY",
    url="https://us-south.ml.cloud.ibm.com"
)

project_id = "YOUR_PROJECT_ID"
```

Choose a supported foundation model, for example:

```python
model_id = "ibm/granite-4-h-small"
```

---

## Run the Applications

### Resume Polisher

```bash
python resume_polisher.py
```

### Cover Letter Generator

```bash
python cover_letter_generator.py
```

### Career Advisor

```bash
python career_advisor.py
```

Gradio will launch a local web application.

---

## Example Workflow

1. Select your target position.
2. Paste your resume.
3. Paste the job description.
4. Receive AI-powered recommendations.
5. Generate a customized cover letter.

---

## Technologies

- IBM watsonx.ai
- IBM Granite Foundation Models
- Gradio
- Python
- Prompt Engineering
- Large Language Models

---