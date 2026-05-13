/* พื้นหลังและฟอนต์ */
body {
  font-family: "Prompt", sans-serif;
  background-color: #f8f9fa;
  color: #333;
  margin: 0;
  padding: 0;
}

/* กล่องฟอร์ม */
form {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  max-width: 400px;
  margin: 20px auto;
}

/* input */
input[type="text"],
input[type="password"],
input[type="file"] {
  width: 100%;
  padding: 10px;
  margin: 8px 0;
  border: 1px solid #ccc;
  border-radius: 6px;
  transition: border-color 0.3s;
}

input:focus {
  border-color: #6f42c1; /* purple */
  outline: none;
}

/* ปุ่ม */
button {
  background-color: #6f42c1;
  color: #fff;
  border: none;
  padding: 10px 15px;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s;
}

button:hover {
  background-color: #563d7c;
}

/* หัวข้อ */
h3 {
  text-align: center;
  color: #6f42c1;
  margin-bottom: 20px;
}

/* เมนูหลัก */
.list-group {
  max-width: 400px;
  margin: 30px auto;
}

.list-group-item {
  background: #fff;
  border: 1px solid #ddd;
  margin-bottom: 8px;
  border-radius: 6px;
  text-align: center;
  font-weight: 500;
  color: #6f42c1;
  transition: background 0.3s, color 0.3s;
}

.list-group-item:hover {
  background: #6f42c1;
  color: #fff;
}
