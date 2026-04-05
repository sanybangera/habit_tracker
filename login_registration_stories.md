# User Stories for Login & Registration
---
## User Story 1: Account Registration

**Title:** Account Registration  
_As a user, I want to register with my name, username, age, and country so that I can create an account and access the habit tracking features._

**Acceptance Criteria:**
1. User can enter name, username, age, and country
2. All fields are required
3. Registration is successful if valid data is entered

**Priority:** High  
**Story Points:** 5  

**Notes:**
- User data is not stored after logout due to security constraints

---

## User Story 2: Account Login

**Title:** Account Login  
_As a user, I want to log in using my username and password so that I can access my account and track my habits._

**Acceptance Criteria:**
1. User enters username and password
2. Only default credentials allow login
3. Successful login redirects to dashboard

**Priority:** High  
**Story Points:** 5  

**Notes:**
- User cannot log in with registered credentials

---

## User Story 3: Error Feedback on Login

**Title:** Login Error Handling  
_As a user, I want to receive a message if I enter the wrong username or password so that I know my login attempt was unsuccessful._

**Acceptance Criteria:**
1. Error message shown for incorrect credentials
2. Empty fields show validation message
3. User stays on login page after failure

**Priority:** Medium  
**Story Points:** 3  

**Notes:**
- Clear error messages improve user experience
