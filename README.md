
# 🏢 Hostel Management System – Highrise Hostel

This is a full-stack web application I built as part of my **Advanced Web Technology** course project during undergrad. The goal was to digitize the manual hostel operations at our university – particularly leave applications, complaint tracking, and student/staff registration. 

It supports **three user roles**: Admin, Warden, and Student – each with distinct access and features.

---

## 📸 Preview Screens

### 🔐 Login Page  
![Login](https://user-images.githubusercontent.com/51413811/166134137-13af7fca-0559-41a9-8170-fc5fa0a9dc9f.png)

### ❌ Error Page  
![Error](https://user-images.githubusercontent.com/51413811/166134244-a347905b-f0a0-497d-ac38-7a1e5690c07d.png)

### 👨‍🎓 Student Panel
- **Home Page**  
  ![Student Home](https://user-images.githubusercontent.com/51413811/166134153-e1af0161-690d-4e7f-8cd2-63a06dadf164.png)
- **Leave Form**  
  ![Leave Form](https://user-images.githubusercontent.com/51413811/166134161-deac4d67-acc9-4f68-b0d4-fb5fd7596ff1.png)

### 🧑‍💼 Warden Panel
- **Home Page**  
  ![Warden Home](https://user-images.githubusercontent.com/51413811/166134178-8ef2b58c-d148-4a7f-afed-699d0262f539.png)
- **Leave Applications List**  
  ![Leave List](https://user-images.githubusercontent.com/51413811/166134182-af2ad3c1-6f1d-42d9-9df7-1fea4329bfe9.png)
- **Leave Review Page**  
  ![Leave Review](https://user-images.githubusercontent.com/51413811/166134198-d7ca960d-cf2a-47c5-a199-e2e985614360.png)

### 🧑‍💻 Admin Panel
- **Dashboard**  
  ![Admin Home](https://user-images.githubusercontent.com/51413811/166134220-ada8f22c-0091-4e14-beb7-6ac649604bab.png)
- **Student Registration**  
  ![Student Reg](https://user-images.githubusercontent.com/51413811/166134233-2628f539-84b7-4921-bdfb-74e409f974f0.png)

---

## 🧩 Features

- Role-based access system (Admin, Warden, Student)
- Student: Apply for leave and track approval status
- Warden: Review and approve/decline leave requests
- Warden: View student complaints
- Admin: Register new students and wardens
- JWT-based route protection for secure access

---

## 🛠️ Tech Stack

| Layer         | Tools Used |
|---------------|------------|
| **Frontend**  | React.js, Bootstrap, Styled Components |
| **Backend**   | Node.js, Express.js |
| **Database**  | MongoDB, Mongoose |
| **Security**  | JWT for route protection and authentication |

---

## 🧪 How to Run Locally

1. Clone the repo  
   ```bash
   git clone https://github.com/preetpatel1616/hostel-management-system.git
   ```

2. Navigate to the project and install dependencies  
   ```bash
   npm install
   ```

3. Enter your Mongo URI inside `connection.js`  
   ```js
   const DB = "ENTER YOUR MONGO URI";
   ```

4. Run the server  
   ```bash
   npm start
   ```

---

## 🛠️ Contributions & Enhancements

### In Progress
- Complaint resolution workflow for Warden
- Attendance tracking per student

Contributions and suggestions are welcome! Feel free to fork the repo and open a pull request.

---

## 👥 Authors

- [Preet Patel](https://www.linkedin.com/in/patelpreet25)
- [Priyank Mistry](https://www.linkedin.com/in/priyank-mistry-7b7886203)

---

⭐ If you found this project useful or inspiring, don’t forget to star the repo!
