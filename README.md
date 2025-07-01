# Automation Testing DemoQA

## Overview
This project showcases automation testing skills for the DemoQA website (https://demoqa.com/) using Selenium IDE and Postman. It includes test cases, scripts, defect reports, and documentation, tailored for an Intern Tester portfolio.

## Project Details
- **Project Name**: Automation Testing DemoQA
- **Prepared by**: Nguyen Thi Tam Nhi
- **Date**: 01/07/2025 - 02/07/2025
- **Environment**: Microsoft Edge (latest version), Windows 11, Desktop

## Prerequisites
- **Selenium IDE**: Microsoft Edge extension (https://www.selenium.dev/selenium-ide/)
- **Postman**: Latest version (https://www.postman.com/downloads/)
- **Microsoft Edge**: Latest version
- **Excel**: To view `Test_Cases.xlsx`

## Repository Structure
- **Test_Plan.docx**: Testing strategy, objectives, and scope.
- **Test_Cases.xlsx**: Test cases for Login, Form, UI, and API modules.
- **Test_Report.docx**: Test execution results and analysis.
- **scripts/**: Selenium IDE scripts (`.side`) for UI automation.
  - `tc_login_002.side`: Failed login test.
  - `tc_form_002.side`: Empty form submission test.
  - `tc_ui_003.side`: Button alignment test at 320px.
- **api/**: Postman collection for API testing.
  - `demoqa_api.json`: API requests (GET https://demoqa.com/BookStore/v1/Books, POST https://demoqa.com/login).
  - `demoqa_environment.json`: Environment variables (baseUrl = https://demoqa.com).
- **screenshots/**: Evidence of test execution and defects.
  - `demo_login.png`: Login error (DEMO-1).
  - `demo_form.png`: Form error (DEMO-2).
  - `demo_ui.png`: Button misalignment (DEMO-3).
- **bug_reports/**: Jira ticket PDFs for defects.
  - `DEMO-1.pdf`: Failed login with incorrect username.
  - `DEMO-2.pdf`: Submit form with empty fields.
  - `DEMO-3.pdf`: Button misalignment at 320px (simulated).

## Key Test Cases
- **TC_Login_002**: Failed login with incorrect username (DEMO-1).
- **TC_Form_002**: Submit form with empty fields (DEMO-2).
- **TC_UI_003**: Check button alignment at 320px width (DEMO-3, simulated).
- **TC_API_001**: Get book list via API (https://demoqa.com/BookStore/v1/Books).
- **TC_API_002**: Post login with invalid credentials (https://demoqa.com/login).
- **TC_API_003**: Check API response time (< 2 seconds).

## How to Use
1. **Review Documents**:
   - Open `Test_Plan.docx` for testing strategy.
   - View `Test_Cases.xlsx` for test scenarios.
   - Check `Test_Report.docx` for results.
2. **Run UI Tests**:
   - Install Selenium IDE.
   - Open `.side` files in `scripts/` (e.g., `tc_ui_003.side`) and run.
3. **Run API Tests**:
   - Install Postman.
   - Import `api/demoqa_api.json` and `api/demoqa_environment.json`.
   - Run requests (e.g., POST https://demoqa.com/login for TC_API_002).
   - Check response time for TC_API_003 in Postman (top-right of response or Test Results).
4. **View Evidence**:
   - Check `screenshots/` for test and defect visuals.
   - Open `bug_reports/` for Jira ticket PDFs.

## Achievements
- Automated 6 test cases with 83% pass rate using Selenium IDE and Postman.
- Demonstrated defect reporting with simulated Jira tickets (DEMO-1, DEMO-2, DEMO-3).
- Produced clear documentation for planning, execution, and reporting.

## Notes
- **Testing Environment**: Microsoft Edge (latest) on Windows 10.
- **Simulated Defect**: DEMO-3 (button misalignment at 320px) is simulated to showcase defect reporting skills.
- **Portfolio Use**: Highlights automation and testing skills for Intern Tester role.

## Links
- DemoQA: https://demoqa.com/
- Selenium IDE: https://www.selenium.dev/selenium-ide/
- Postman: https://www.postman.com/
- GitHub: https://github.com/namiiiah

## Contact
- **Author**: Nguyen Thi Tam Nhi
- **Email**: tamnhint0905@gmail.com
- **Date Created**: 01/07/2025