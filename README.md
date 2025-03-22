# 🚀 Laravel CRUD  
A basic Laravel CRUD (Create, Read, Update, Delete) operation learning program.  

---

## 📌 Prerequisites  
Before getting started, ensure you have the following installed:  

- **PHP** (Latest stable version) – [Download PHP](https://www.php.net/downloads)  
- **Composer (Global Installation)** – [Get Composer](https://getcomposer.org/download/)  
- **Laravel Installer** – Install Laravel globally using Composer:  
  ```sh
  composer global require laravel/installer
- **Node.js & npm** – Required for frontend assets and Laravel Mix. Download Node.js

---

## ⚡ Installation
Follow these steps to set up the Laravel CRUD project:

### 1️⃣ Clone the Repository (if using GitHub)
 ```sh
   git clone https://github.com/your-repo/laravel-crud.git
   cd laravel-crud
```

### 2️⃣ Install Dependencies
 ```sh
   composer install
   npm install
```

### 3️⃣ Set Up the Environment File
Copy the example environment file and configure your database settings:
 ```sh
      cp .env.example .env
```

### 4️⃣ Generate Application Key
 ```sh
   php artisan key:generate
```


### 5️⃣ Run Database Migrations
 ```sh
     php artisan migrate
```


### 6️⃣ Start the Development Server
 ```sh
   php artisan serve
 ```
The application will be available at: http://127.0.0.1:8000



### 7️⃣ Compile Assets (if using Laravel Mix)
```sh
  npm run dev
```


## 🎯 Usage
Navigate to http://127.0.0.1:8000 to access the Laravel application.

Perform CRUD operations on the entities available in the project.

## 🛠 Contributing
💡 Feel free to contribute to this project by submitting pull requests or reporting issues.

## 📜 License
This project is open-source and available under the MIT License.

## ✅ Happy Coding! 🚀

This version includes **emoji icons**, **code blocks**, **sections with headers**, and a **well-structured layout** to make your README visually appealing. Let me know if you need any modifications! 🚀



