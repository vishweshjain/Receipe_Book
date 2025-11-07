# 🍳 Recipe Book – Cook, Learn & Login to Explore!

A stylish and interactive **Recipe Book website** built using **HTML, CSS, and JavaScript**.  
It allows users to explore delicious dishes, **sign up or log in to unlock all recipes**, and enjoy a personalized cooking experience — with all data stored securely in the browser’s **Local Storage**.

---
## 🖥️ How It Works

1. **Sign Up / Login**  
   - User registers or logs in using a form.  
   - Credentials are stored in `localStorage` under `isLoggedIn` and `loggedUser`.

2. **Access Control**  
   - Non-logged-in users can read **only one recipe** (demo access).  
   - Attempting to open any other recipe shows an alert like *“Please log in to access this recipe.”*  

3. **Dynamic Navbar Update**  
   - Once logged in, the "Login" button changes to "Logout" and the user’s name appears.  

4. **Logout**  
   - Removes data from LocalStorage.  
   - Redirects to homepage and resets buttons to default state.

---

## ✨ Features

✅ **User Authentication (Frontend)**  
Users can **Sign Up** and **Log In** — credentials are stored in **LocalStorage** for quick and simple session handling.  

✅ **Restricted Access (Login Required)**  
Only **one dish** can be accessed without logging in.  
👉 To explore **all recipes**, users must be logged in.  
This adds a real-world feel similar to premium recipe platforms.  

✅ **Dynamic Navbar**  
After login, the navbar updates automatically — showing the **user’s name** and a **logout** button instead of the default login/signup buttons.  

✅ **Logout Feature**  
One-click logout removes user data from LocalStorage and redirects to the homepage.  

✅ **Attractive Recipe Grid**  
Beautiful recipe cards with images and “Read” buttons linking to individual recipe pages.

✅ **Responsive Design**  
Fully mobile-friendly layout built using **CSS Grid** and **Flexbox**.

✅ **Local Storage Integration**  
Stores user data, login state, and updates UI dynamically without any backend.

---

## **🧠 Key Learnings**

- Creating a frontend-only authentication system
- Managing user sessions with LocalStorage
- Controlling page access and restrictions
- Building a clean UI using HTML, CSS Grid & Flexbox
- Writing modular, readable Vanilla JavaScript

---

## 🧩 Tech Stack

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Structure & content |
| **CSS3** | Styling and responsive layout |
| **JavaScript (ES6)** | Login system, access control, and dynamic DOM manipulation |
| **LocalStorage API** | Save and manage user login data |

---

## 📂 Folder Structure

```
📦 recipe-book
┣ 📂 images
┃ ┣ image1.jpg
┃ ┣ image2.jpg
┃ ┣ image3.jpg
┃ ┣ image4.jpg
┃ ┣ image5.jpg
┃ ┗ image6.jpg
┣ 📜 index.html
┣ 📜 receipes.html
┣ 📜 login.html
┣ 📜 signup.html
┣ 📜 style.css
┗ 📜 script.js
```
---
## 🧑‍🍳 Author
- Vishwesh Jain

---

Would you like me to add a **demo “Access Control GIF” section** (showing how login restricts recipe access)?  
That would make your GitHub page look more interactive and professional.


