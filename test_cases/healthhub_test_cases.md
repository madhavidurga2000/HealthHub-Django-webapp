# HealthHub - Hospital Management System: Test Cases

| Test ID   | Module        | Test Description                      | Input                              | Expected Result                         | Status |
|-----------|----------------|----------------------------------------|-------------------------------------|------------------------------------------|--------|
| TC-HH-01  | Admin          | Admin Login with valid credentials     | Username: `admin`, Password: `admin123` | Redirect to admin dashboard         | ✅     |
| TC-HH-02  | Admin          | Invalid login                         | Username: `wrong`, Password: `1234` | Show login error message                 | ✅     |
| TC-HH-03  | Doctor Module  | Add a new doctor                      | Valid doctor form                   | Doctor successfully added                | ✅     |
| TC-HH-04  | Patient Module | Book appointment with invalid date   | Past date                           | Show "Invalid Date" error                |  ✅     |
| TC-HH-05  | Patient Module | Book appointment valid                | Name, date, doctor selected         | Appointment saved                        | ✅     |
| TC-HH-06  | Reports        | View patient list                     | N/A                                 | Display all registered patients          | ✅     |
| TC-HH-07  | Logout         | Logout from system                    | Click "Logout"                      | Redirect to login page                   | ✅     |
