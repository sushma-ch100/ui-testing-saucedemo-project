**UI Testing Project – SauceDemo**
**Project Overview**

Performed end-to-end manual testing of a real-world e-commerce application (SauceDemo) to validate critical user journeys, uncover UI/functional defects, and ensure consistent behavior across devices and browsers.

This project simulates a production-like QA workflow, including test design, execution, defect reporting, and result analysis.
**Testing Objectives**
Validate core business flows (Login → Product → Cart → Checkout)
Identify functional and UI defects impacting user experience
Ensure responsiveness across mobile and tablet devices
Verify cross-browser compatibility
 **Scope of Testing**
Authentication: Valid/invalid login scenarios, error handling
Product Module: Product display, sorting, item details
Cart & Checkout: Add/remove items, checkout validation
UI/UX Validation: Layout consistency, button states, text visibility
Responsive Testing: Mobile & tablet layout behavior
**Tools & Technologies**
Test Design & Reporting: Excel
Browser Testing: Chrome, Safari, Microsoft Edge
Responsive Testing: Chrome DevTools
Defect Tracking Approach: Structured bug reporting (severity, steps, expected vs actual)
 **Test Deliverables**
✔️ Detailed Test Cases (positive & negative scenarios)
✔️ Defect Reports with reproducible steps
✔️ Test Summary Report with execution metrics
**Execution Summary**
Metric	Value
Total Test Cases	20
Passed	17
Failed	3
Defects Identified	3
 Key Defects Identified (Impact-Focused)
Critical: Checkout allowed without items in cart → impacts business logic
High: Login validation gaps → improper error handling
Medium: Product image loading inconsistencies → affects UI reliability

These defects highlight gaps in validation logic and UI stability, common in real-world applications.

 **Responsive Testing Approach**
Tested UI adaptability across multiple screen sizes using Chrome DevTools to simulate real devices.

** Results**
Metric	Value
Test Cases	15
Passed	13
Failed	2
Defects	2

Observations
Minor layout misalignment on smaller screens
Text/content overflow in specific product views
**Cross-Browser Testing**
 Approach

Validated UI consistency and functionality across major browsers.

 **Results**
Metric	Value
Test Cases	10
Passed	10
Failed	0
Defects	1
 **Observations**
Minor rendering inconsistency across browsers (non-blocking)
**QA Thinking & Approach**
Focused on end-user experience + business impact, not just UI checks
Designed realistic test scenarios based on actual user behavior
Prioritized defects using severity and impact analysis
Ensured traceability between test cases and defects
Why This Project Stands Out
Demonstrates complete QA lifecycle execution
Shows ability to think critically and identify real defects
Covers functional, UI, responsive, and cross-browser testing
Structured documentation similar to industry QA standards
 **Next Steps (Planned Enhancements)**
Automate test cases using Selenium / Playwright
Integrate test execution with CI/CD (Jenkins)
Add API testing for backend validation

