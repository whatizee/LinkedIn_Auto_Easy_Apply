# Auto Easy Job Apply in LinkedIn

Welcome to the Auto Easy Job Apply in LinkedIn project! This tool aims to simplify and automate the job application process on LinkedIn. By following the steps below, you can quickly apply to multiple jobs without manually filling out each application.

## Features

- Automated job application process on LinkedIn.
- Supports applying to multiple jobs with a single command.
- Easy-to-use interface.

## Prerequisites

- Python 3.x installed on your system.
- LinkedIn account credentials (email and password).
- Selenium WebDriver for browser automation.

## Setup Instructions

Follow these steps to set up and use the Auto Easy Job Apply tool:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/whatizee/LinkedIn_Auto_Easy_Apply.git
   cd LinkedIn_Auto_Easy_Apply
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Update Credentials**

   Open the `config.py` file and update the `EMAIL` and `PASSWORD` fields with your LinkedIn account credentials.

   ```python
   # config.py
   EMAIL = 'your_email@example.com'
   PASSWORD = 'your_password'
   ```

4. **Run the Script in Jupyter notebok**

   ```bash
   python LinkedIn_Auto_Easy_Apply.ipynb
   ```

   This will start the automated job application process.

## Usage

1. Navigate to the LinkedIn job search page.
2. Find the jobs you want to apply for.
3. Run the `LinkedIn_Auto_Easy_Apply.ipynb` script.
4. Sit back and watch as the tool applies to jobs on your behalf.

## Important Note

- **Security**: Please ensure that you do not share your `config.py` file or your credentials with anyone. Keep your account information secure.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

---

Thank you for using the Auto Easy Job Apply in LinkedIn tool. Happy job hunting!
