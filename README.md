Simple Auth
Giới thiệu

Dự án này demo cơ chế xác thực cơ bản (Basic Authentication và Cookie Authentication).

Cách chạy

Cài dependency: npm install

Chạy:
node basic_auth.js
node cookie_auth.js

Hướng dẫn test

Với basic_auth.js: gọi API bằng Postman với header Authorization: Basic <base64(username:password)>

Với cookie_auth.js: đăng nhập → nhận cookie → kiểm tra trong Postman và MongoDB.

Kết quả test
### 1. Auth Require
![Auth Require](img/auth_require.png)

### 2. Login
![Login](img/login.png)

### 3. Header Authorization
![Header](img/header.png)

### 4. Cookie
![Cookie](img/cookie.png)

### 5. Cookie in mongoDB
![Cookie Mongodb](img/cookie_mongodb.png)