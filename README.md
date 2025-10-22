# 🛴 Urban Scooter — Full-Stack QA Testing Capstone (Web • Mobile • Backend)
Urban Scooter is a three-part QA capstone project demonstrating end-to-end quality assurance across web, mobile, and backend components of a scooter-rental platform.  
It showcases the ability to plan, execute, and document functional, validation, and integration testing using industry-standard tools and workflows.

## 🧩 Project Scope
### 1️⃣ Web Application Testing
Tested the “About Customer” form in the “Place Order” flow — the section titled *“Who the scooter is for”*, containing customer name and phone number fields.  
- Designed positive and negative test cases to verify field validation, input restrictions, and UI error states.  
- Conducted cross-browser testing on Chrome (v85+) and Opera (v71+) at 1280×720 resolution.  
- Logged results in Google Sheets and filed linked Jira bug reports for each defect.  
- Validated compliance with the web app’s front-end and backend input constraints.

### 📱 Mobile Application Testing
Executed tests on the Urban Scooter Android app using an Android 31 emulator in Android Studio.  
- Created a courier account via backend API (`POST /couriers`) to log into the app.  
- Verified login flow, order synchronization, and visual layout against Figma designs.  
- Designed test cases for highlighted mobile features, including order management and UI responsiveness.  
- Ensured data consistency between the web client (order creation) and mobile courier app (order visibility).  
- Recorded all test outcomes and Jira references in the “Task 2: Test Cases” tab.

### ⚙️ Backend (API) Testing
Focused on courier management endpoints within the backend service.  
- Tested Add Courier (POST) and Delete Courier (DELETE) operations following backend requirements.  
- Used Postman to execute and validate API calls, verifying correct status codes, payloads, and data persistence.  
- Designed positive and negative scenarios (duplicate couriers, invalid fields, missing parameters).  
- Linked API test results and bug reports to the “Task 3: API Test Cases” tab.  
- Cross-referenced findings with apiDoc documentation at `/docs/en`.

## 📦 Deliverables
- Google Sheets test documentation (positive + negative cases, results, Jira links)  
- Postman collection and environment for backend API testing  
- Screenshot and evidence folders for web and mobile test execution  
- Jira defect reports with reproduction steps and environment details

## 🧰 Tools & Technologies
- **Web:** Chrome | Opera | DevTools | Figma  
- **Mobile:** Android Studio | Emulator (API 31) | APK testing  
- **Backend:** Postman | REST API | JSON payloads  
- **Test Management:** Google Sheets  
- **Bug Tracking:** Jira  
- **Documentation:** Web Req v1.2 | Mobile Req | Backend Req v1.4

## 💡 Skills Demonstrated
- Full-stack QA coverage (UI, Mobile, API)  
- Test design and execution for functional and validation testing  
- Cross-platform and cross-browser testing  
- API verification and error handling in Postman  
- Requirement-based testing with Figma UI alignment  
- Defect management and traceability in Jira  
- Integration testing across client ↔ server interfaces

## 🏁 Result
This project reflects end-to-end testing expertise across all major QA domains — manual web testing, mobile validation, and backend API verification.  
It highlights strong analytical thinking, test design, and attention to detail, demonstrating readiness to deliver comprehensive QA coverage in a professional environment.
