# React Native Expense Tracker Interview Task

## Objective

Create a simple expense tracking application with user authentication and CRUD functionality for transactions. The app must persist data locally and maintain user sessions until logout.

---

## **Requirements**

### **Technical Setup**

1. Use **React Native** (Expo or CLI)
2. Choose any **local storage** solution (e.g. SQLite, MMKV, etc..).
3. Use **React Navigation** for screens.

---

## **Core Features**

### 1. **User Authentication**

#### Registration Screen

- Fields: Name, Email, Password.
- Validate inputs (e.g., valid email format, password length).
- Store user data in local storage.

#### Login Screen

- Fields: Email, Password.
- Validate credentials against stored registration data.
- Navigate to Home on success; show errors on failure.

#### Session Persistence

- Keep users logged in until they manually logout.
- Redirect authenticated users to the Home screen on app restart.

#### Logout

- Add a logout button on the Home screen.
- Clear session data and redirect to Login.

---

### 2. **Expense Management**

#### Add Transaction

- Screen with fields: Title, Amount (number), Type (income/expense), Date.
- Save to local storage.

#### List Transactions

- Screen to display all transactions in a list.
- Show title, amount, date and type.
- Add a way to navigate here from the Home screen (e.g., tab, button).

#### Edit/Delete Transactions

- Allow users to edit or delete existing transactions.
- Update local storage after any changes.

---

### 3. **Data Persistence**

- All data (user accounts, transactions) must survive app restarts.
- Transactions must be tied to the logged-in user (users see only their own data).

---

## **Technical Expectations**

1. **State Management**: Redux.
2. **Navigation**: Stack and Tab navigators (e.g., Login → Home, Home → Transactions).
3. **Code Quality**:
   - Clean, reusable components.
   - Proper error handling (e.g., login failures, invalid inputs).
   - Meaningful variable names and comments.
   - Make util function in separate folder

---

## **Design & UI**

- **Freestyle design**, but ensure a clean and intuitive interface.
- Use icons, labels, and input validations where appropriate.

---

## **Submission**

1. **GitHub Repository** with:
   - Complete source code.
   - `README.md` explaining setup, libraries used, and key decisions.

---

**Timeframe**: Submit within 2-4 days.

Good luck! 🚀
