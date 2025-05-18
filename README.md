
---
## 📝 Project Description
This project automates test scenarios for the **OpenMRS Demo System**, an open-source medical record platform.  
The test scenarios are implemented using **Cucumber**, along with **Selenium WebDriver**, and follow the **Page Object Model (POM)** structure.  
**This project is primarily developed and structured using Cucumber for Behavior-Driven Development (BDD) style test automation.**  
Test executions are configured through the `testng.xml` file.


## 🧑‍💻 User Stories and Test Scenarios

| ID       | User Story Description                            | Expected Outcome                                               | Actual Outcome                                             |
|----------|--------------------------------------------------|----------------------------------------------------------------|------------------------------------------------------------|
| **US_401** | Login test with invalid user data             | Error messages for location and invalid credentials            | Warnings like "You must choose a location!" and "Invalid username/password." displayed |
| **US_402** | Login test with valid user data               | Successful login after selecting location                      | Login successful with correct credentials                  |
| **US_403** | Logout                                        | Redirect to login page after logout                            | Session ended and user logged out                           |
| **US_404** | Patient registration                          | Patient registered with demographic/contact/relationship info | Patient appeared in system after registration              |
| **US_405** | Access account settings                        | “My Account” page opens with settings options                  | Account settings accessed and interacted with              |
| **US_406** | Patient search in list                         | Valid searches return data; invalid searches show “No match”  | Both positive and negative searches passed                  |
| **US_407** | Patient deletion                              | Patient record deleted with valid reason                       | Patient data removed successfully                           |
| **US_408** | List all patients                             | Number of rows matches summary count                           | Patient list and summary consistent                         |
| **US_409** | Merge patient records                         | Records merged after selection and confirmation                | Patient records merged correctly                            |
| **US_410** | Timezone error on appointment                 | Error if timezone is not GMT+0                                 | Scheduling blocked until timezone corrected                 |

---

## 📊 Test Coverage Table

| Test Scenario                        | Status   | Priority |
|------------------------------------|----------|----------|
| US_401 - Login errors               | ✅ Passed | High     |
| US_402 - Successful login           | ✅ Passed | High     |
| US_403 - Logout                    | ✅ Passed | High     |
| US_404 - Patient registration      | ✅ Passed | Medium   |
| US_405 - My account settings       | ✅ Passed | Low      |
| US_406 - Patient search            | ✅ Passed | High     |
| US_407 - Patient deletion          | ✅ Passed | High     |
| US_408 - List all patients         | ✅ Passed | Medium   |
| US_409 - Merge patient records     | ✅ Passed | Medium   |
| US_410 - Timezone error during appointment | ✅ Passed | Low      |

---

## 🚀 Tools and Technologies

| Tool / Technology      | Description                                    |
|-----------------------|------------------------------------------------|
| Java                  | Programming language                           |
| Selenium WebDriver    | Web automation framework                        |
| Cucumber              | Testing framework                              |
| Cucumber XML          | Manages test configurations and groups        |
| Maven                 | Dependency management and build tool           |
| Page Object Model (POM) | Reusable and maintainable test design         |
| Git / GitHub          | Version control                                |

---

## 📚 Required Libraries

- Selenium  
- Cucumber  
- Apache Commons IO  
- SLF4J NOP  

---

## 👨‍💻 Project Team

| Name                 | Role                   | User Story(s)         | Short Bio & Responsibilities                                      |
|----------------------|------------------------|-----------------------|------------------------------------------------------------------|
| Serkan Sewoester     | QA Automation Tester    | US_403                | Experienced in Selenium and TestNG, responsible for logout tests and session management scenarios. |
| Burak Bora Durmaz    | QA Automation Tester    | US_408                | Skilled in cross-browser testing, manages patient listing and UI consistency. |
| Murat Öksüz          | QA Automation Tester    | US_404                | Focuses on patient registration workflows and data validation.   |
| Melike Emine Özyavuz | QA Automation Tester    | US_401                | Expert in negative testing scenarios; leads login error validations. |
| İbrahim Can          | QA Automation Tester    | US_405                | Handles account settings tests, password changes, and UI navigation. |
| Ayşenur Gökdemir     | QA Automation Tester    | US_402, US_410        | Responsible for login success cases and timezone-related appointment errors. |
| Tuğba Yılmaz         | QA Automation Tester    | US_406                | Specializes in patient search functionalities and edge cases.    |
| Ennur Göl            | QA Automation Tester    | US_407                | Manages patient deletion scenarios ensuring secure data removal. |
| Hakan Mert           | QA Automation Tester    | US_409                | Oversees merge patient records test cases and conflict resolution. |

---

## 🔗 GitHub Repository

- [OpenMRS Cucumber Automation Repository](#) *(Add actual link)*
- 

---

## 📝 License

This project incorporates code from the OpenMRS project.

For more information about OpenMRS, visit: [https://openmrs.org](https://openmrs.org)
