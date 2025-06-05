# 🍔 UberEatsAPI – End-to-End QA Testing Case Study

This repository presents a **professional API testing case study** based on an Uber Eats-style food delivery platform. It demonstrates full QA lifecycle practices in an **Agile environment** using **Postman, Java (Rest Assured), JIRA, Zephyr**, and **CI/CD** workflows.

---

## 🔧 Tech Stack & Tools

| Category | Tools |
|----------|-------|
| API Testing | Postman, Rest Assured (Java), TestNG |
| Test Management | JIRA, Zephyr |
| Documentation | MS Word, Excel, Confluence |
| Automation | Maven, GitHub Actions, Jenkins |
| Reporting | Allure, ExtentReports |
| Version Control | Git, GitHub |

---

## 📂 Folder Structure

```
UberEatsAPI-QA-CaseStudy/
│
├── docs/                  # Project documentation (SRS, SDD, RTM, etc.)
├── postman/               # Postman collection, environment, auto-docs
├── automation/            # Java + Rest Assured automation suite
├── ci-cd/                 # Jenkins or GitHub Actions CI workflows
├── bug-reports/           # Bug templates and sample issues
├── sprint-artifacts/      # QA sign-offs and sprint summaries
├── README.md              # Project overview and usage instructions
└── LICENSE
```

---

## 📄 Project Artifacts

| Artifact | Description |
|---------|-------------|
| ✅ SRS & SDD | Functional and architectural specs |
| 🗂️ RTM | Maps each requirement to test cases |
| 🧪 Test Plan & Cases | Zephyr-based and Excel-formatted |
| 🔁 Regression Suite | Implemented with Java + Rest Assured |
| 📬 Postman Collection | Manual test coverage for all endpoints |
| 🚦 CI/CD | Jenkins/GitHub Actions triggering nightly runs |
| 📊 Reports | Allure/ExtentReports and Sprint summaries |

---

## 🔬 API Modules Covered

- ✅ User Signup/Login/Logout
- ✅ Restaurant Listing
- ✅ Menu Retrieval by Restaurant
- ✅ Cart Management (Add/Remove/Update)
- ✅ Order Placement and History
- ✅ Payment Initiation and Verification
- ✅ Review Submission and Fetching
- ✅ Error Handling: Token expiry, validation

---

## 🔁 Sprint Workflow

This project simulates 2 full Agile sprints:

| Sprint | Focus |
|--------|-------|
| Sprint 1 | Manual testing, Zephyr setup, smoke/functional test |
| Sprint 2 | Automation, regression, CI/CD integration, sign-off |

👉 Refer to `docs/UberEatsAPI_QA_Workflow_Summary.docx` for complete lifecycle stages.

---

## 📦 Getting Started with Automation

1. Clone the repo
2. Navigate to `/automation`
3. Run: `mvn clean test`
4. Generate report: `mvn allure:serve` (if using Allure)

---

## 📈 CI/CD Integration

- `ci-cd/Jenkinsfile` – Jenkins pipeline for build + test
- `.github/workflows/ci.yml` – GitHub Actions for PR test automation

---

## 🤝 QA Sign-Off

All test phases are documented, validated, and signed off in:
- `sprint-artifacts/QA_SignOff_Sprint2.docx`
- `docs/UberEatsAPI_TestPlan_Updated_Full.docx`

---

## 📧 Contact

This project was developed as a QA case study simulation for real-world API testing scenarios.  
For inquiries or collaboration, contact: **qa.case.study@example.com**