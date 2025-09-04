# Blood Bank Management System

A simple Node.js + Express web app for blood donation management.  
**Made by: Kovin Mahan**

---

## Features

- **User Registration:** Register as a blood donor.
- **Login via Cookie:** No password, just phone-based session.
- **Donate Blood:** Update your donation amount.
- **Check Donors:** Search donors by blood group and city.
- **Leaderboard:** Top donors listed.
- **Responsive UI:** Built with Materialize CSS.
- **MongoDB Database:** Stores all donor info.

---

## Getting Started

### 1. Clone the Repo

```sh
git clone https://github.com/KovinMahan/Blood-Bank-Management-System.git
cd Blood-Bank-Management-System
```

### 2. Install Dependencies

```sh
npm install
```

### 3. Setup Environment Variables

Create a `.env` file in the root folder:

```
DBURI=your_mongodb_connection_string
KEY=your_cookie_secret_key
PORT=3000
```

### 4. Run the App

```sh
node index.js
```
or
```sh
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Folder Structure

```
├── index.js
├── models/
│   └── user.js
├── public/
│   ├── css/
│   ├── img/
│   ├── js/
│   ├── json/
│   ├── index.html
│   └── register.html
├── util/
│   └── populator.js
├── views/
│   ├── bank.ejs
│   ├── donate.ejs
│   └── footer.ejs
├── .env
├── .gitignore
├── package.json
```

---

## How To Use

- **Register:** Go to `/register` and fill the form.
- **Donate:** After registering, donate blood via `/donate`.
- **Check Donors:** Click "Check Donors" to see all donors.
- **Logout:** Click "Logout" to end your session.

---

## Contributing

Pull requests are welcome!  
For major changes, please open an issue first.

---
---

## Author

**Kovin Mahan**

---

## Credits

- [Materialize CSS](https://materializecss.com/)
- MongoDB
- Express.js

---
