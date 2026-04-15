# Claims Data Application

## Feature Overview
The Claims Data Application is designed to streamline the processing and management of claims data. It offers the following features:
- **Data Import**: Easily import claims from various sources.
- **Data Validation**: Validates claims data against predefined rules.
- **Reporting**: Generate reports based on processed claims data.
- **User Authentication**: Secure user access with role-based permissions.

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/srijanlalwani/claims-data-application.git
   cd claims-data-application
   ```
   
2. **Install Dependencies**:
   - Make sure you have Python 3.8+ installed.
   - Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**:
   - Create a `.env` file in the root directory and set the necessary variables.

## Usage Guide
- To run the application, use the following command:
  ```bash
  python app.py
  ```
- Access the application at `http://localhost:5000` in your web browser.

## Data Quality Checks Explained
Data quality checks help maintain the integrity of the claims data. The application performs the following checks:
- **Duplicate Detection**: Identifies duplicate claims based on unique identifiers.
- **Field Validation**: Ensures that all required fields are populated correctly.
- **Value Range Checks**: Validates that numerical fields fall within expected ranges.

## File Format Requirements
- Claims data should be provided in CSV format.
- Each file should contain the following columns:
  - `claim_id`
  - `claim_date`
  - `amount`
  - `status`

## Deployment Instructions
To deploy the Claims Data Application:
1. Choose a hosting platform (e.g., Heroku, AWS, etc.).
2. Follow the platform's deployment instructions to set up a new project.
3. Push the application code to the platform.
4. Configure necessary environment variables on the hosting platform.
5. Access the live application via the provided URL.

---

> This README provides a fundamental overview of the application, setup process, and guides users to effectively utilize the Claims Data Application. For more detailed technical documentation, refer to the [Documentation](link_to_full_documentation).