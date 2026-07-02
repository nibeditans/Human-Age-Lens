# Age Lens — How Old Are You Really?

A simple Streamlit web application that calculates your exact age in **years, months, and days** from your birth date.

### 👉🏻 [Live Web App](https://nibeditans-how-old-are-you-really.hf.space/)

## 📁 Project Structure

This project demonstrates three implementations showing progression from basic to production-style logic.

- [`person_age.py`](https://github.com/nibeditans/human-age-lens/blob/main/person_age.py): Minimal implementation using year-based approximation (no external dependencies)
- [`age_calc.py`](https://github.com/nibeditans/human-age-lens/blob/main/age_calc.py): Core age calculation logic using Python datetime utilities
- [`app.py`](https://github.com/nibeditans/human-age-lens/blob/main/app.py): Streamlit web application (interactive UI layer)

## 🧠 Features

- Input name and birth date
- Calculates precise age using calendar-aware logic
- Displays age in years, months, and days
- Handles plural formatting correctly
- Simple and interactive UI built with Streamlit

## 🛠️ Tech Stack

- Python
- Streamlit
- python-dateutil
- Hugging Face Spaces (Deployment)

## 📦 Project Structure

```bash
app.py # Main Streamlit application
requirements.txt # Dependencies
```

## What to Learn from this Simple App?

- Working with Python datetime and `relativedelta`
- Building interactive web apps using Streamlit
- Deploying applications using Hugging Face Spaces
- Structuring simple data-driven applications

## How to Run Locally?

```bash
pip install -r requirements.txt
python -m streamlit run app.py
```

## Note

This is a lightweight Streamlit web application built as a focused experiment in building and deploying small and interactive data tools. It demonstrates basic datetime logic and end-to-end deployment using Hugging Face Spaces. The app focuses on a single task: calculating precise human age from a birth date. It is **not intended to be a full-scale data science system**.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
