# Login Test Cases

## TC_001 - Valid Login

*Precondition*
- User account exists.

*Steps*
1. Open the Login page.
2. Enter a valid email.
3. Enter the correct password.
4. Click Login.

*Expected Result*
- User is successfully logged in.
- Dashboard is displayed.

---

## TC_002 - Invalid Password

*Steps*
1. Enter a valid email.
2. Enter an incorrect password.
3. Click Login.

*Expected Result*
- Error message: "Invalid email or password."

---

## TC_003 - Empty Fields

*Steps*
1. Leave both fields empty.
2. Click Login.

*Expected Result*
- Validation messages are displayed for required fields.
