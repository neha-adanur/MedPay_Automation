# MedPay_Automation
A hybrid framework automated using Vbscript in UFT tool.
The script uses a driverscript that will trigger each test case based on whether the test case is checked as "Yes" or "No" in excel.
The driverscript picks the test data from an excel file "TestCases.xls" and run based on the test data provided in excel.
The excel has sheet called as "TestCaseDetails" which represent testcase details like steps, pre-conditions and expected results.
Each tescase is written as function in suite.
The function library folder consists of Functions.vbs that has all the functions defined.
Based on validation checks in every function whether passed or failed, default UFT report generator event is called and result is written.
User can modify the test data in excel accordingly to test variety of inputs.
