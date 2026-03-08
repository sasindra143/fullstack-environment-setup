<h1 align="center">🚀 Full Stack Development Environment Setup</h1>

<p align="center">
<img src="https://readme-typing-svg.herokuapp.com?color=00F7FF&size=28&center=true&vCenter=true&width=700&lines=Full+Stack+Development+Environment;Node.js+%7C+MySQL+%7C+Git+%7C+VS+Code;Modern+Developer+Setup;Internship+Task+Project"/>
</p>

<p align="center">
This project demonstrates the setup of a <b>Full-Stack Development Environment</b> using modern developer tools.
</p>

<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1200/1*Q5EUk28XcG3dK9K0jZP0ZA.gif" width="500">
</p>

---


# 📌 Project Overview

This repository demonstrates how to set up a **basic development environment** required for modern web development.

The environment includes:

✔ Installing **Node.js**
✔ Creating a Node project using **npm**
✔ Writing a **JavaScript program**
✔ Running the program using **Node.js**
✔ Using **Visual Studio Code Terminal**
✔ Installing **MySQL Database**
✔ Writing **SQL queries**
✔ Using **Git for version control**
✔ Uploading code to **GitHub**

---

# 🛠️ Technologies Used

<p align="center">
<img src="https://skillicons.dev/icons?i=nodejs,js,npm,vscode,mysql,git,github"/>
</p>

<p align="center">

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white"/>
<img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>

</p>

---

# 📂 Project Folder Structure

```text
fullstack-environment-setup
│
├── app.js
├── package.json
├── database.sql
├── images
│   └── node-setup.png
│
└── README.md
```

---

# 📄 File Explanation

| File         | Description                                 |
| ------------ | ------------------------------------------- |
| app.js       | JavaScript program to test Node.js          |
| package.json | Node project configuration                  |
| database.sql | SQL script for creating database and tables |
| images       | Folder storing project screenshots          |
| README.md    | Complete project documentation              |

---

# ⚙️ Step 1 — Initialize Node Project

Command used:

```bash
npm init -y
```

This command generates the **package.json** file automatically.

Example output:

```json
{
"name": "fullstack-environment-setup",
"version": "1.0.0",
"description": "",
"main": "index.js",
"scripts": {
"test": "echo \"Error: no test specified\" && exit 1"
},
"keywords": [],
"author": "",
"license": "ISC",
"type": "commonjs"
}
```

---

# 📸 Node Setup Screenshot

<p align="center">
<img src="images/node-setup.png" width="900"/>
</p>

---

# 🧑‍💻 Step 2 — Create JavaScript File

File created:

```text
app.js
```

Code inside the file:

```javascript
console.log("Development Environment Setup Successful");
```

This code prints a message in the terminal.

---

# ▶️ Step 3 — Run the Program

Command:

```bash
node app.js
```

Output:

```
Development Environment Setup Successful
```

This confirms that **Node.js and JavaScript are working correctly.**

---

# 🗄️ Step 4 — Setup MySQL Database

SQL file used:

```text
database.sql
```

SQL code:

```sql
CREATE DATABASE internship_db;

USE internship_db;

CREATE TABLE students (
id INT AUTO_INCREMENT PRIMARY KEY,
name VARCHAR(100),
email VARCHAR(100),
course VARCHAR(100)
);

INSERT INTO students (name,email,course)
VALUES
('Sasindra','sasindra@email.com','Full Stack Development');
```

This script performs:

✔ Database creation
✔ Table creation
✔ Sample data insertion

---

# 💻 Terminal Output Example

```bash
C:\Users\user\fullstack-environment-setup> node app.js

Development Environment Setup Successful
```

---

# 🔧 Git Commands Used

Initialize repository

```bash
git init
```

Add files

```bash
git add .
```

Commit project

```bash
git commit -m "Initial full stack development environment setup"
```

Connect GitHub repository

```bash
git remote add origin https://github.com/sasindra143/fullstack-environment-setup.git
```

Push project

```bash
git push -u origin main
```

---

# 💡 Commands Used

Initialize Node project

```bash
npm init -y
```

Run JavaScript program

```bash
node app.js
```

Start MySQL

```bash
mysql -u root -p
```

Run SQL script

```bash
mysql -u root -p < database.sql
```

---

# 🎯 Learning Outcomes

After completing this task, the following concepts were learned:

✔ Setting up a Node.js Development Environment
✔ Creating a Node project using npm
✔ Running JavaScript outside the browser
✔ Understanding the purpose of package.json
✔ Using VS Code terminal
✔ Creating MySQL databases and tables
✔ Executing SQL scripts
✔ Using Git for version control
✔ Uploading projects to GitHub

---

# 📊 GitHub Project Stats

<p align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sasindra143&show_icons=true&theme=tokyonight"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=sasindra143&theme=tokyonight"/>

</p>

---

# 🌐 Future Scope

This environment will be used for building modern applications using:

⚡ React.js
⚡ Node.js
⚡ Express.js
⚡ MongoDB
⚡ REST APIs
⚡ Full Stack Applications

---

# 👨‍💻 Author

**Sasindra**

🎓 B.Tech Graduate
💻 Full Stack Developer
🚀 Passionate about Web Development & Software Engineering

---

# ⭐ Support

If you like this project, please give it a **star ⭐ on GitHub**

<p align="center">
<img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="300">
</p>
