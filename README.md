# 📘 Learning Log

**Learning Log** là một hệ thống nhật ký trực tuyến cho phép người dùng theo dõi những thông tin mà họ đã học về các chủ đề cụ thể.
Người dùng có thể đăng ký tài khoản, tạo các chủ đề học tập và thêm các mục nhật ký để lưu lại kiến thức đã học theo thời gian.

---

## 🚀 Tính năng

- Đăng ký và đăng nhập người dùng
- Tạo và quản lý các chủ đề học tập cá nhân
- Ghi chú nhật ký theo từng chủ đề
- Giao diện đơn giản, dễ sử dụng với Bootstrap
- Triển khai trên [PythonAnywhere](https://www.pythonanywhere.com)

---

## 🛠️ Công nghệ sử dụng

- 🐍 **Python 3**
- 🌐 **Django** (backend + routing)
- 🎨 **Bootstrap** (giao diện người dùng)
- 💻 **PythonAnywhere** (hosting & deploy)

---

🌐 Triển khai
Ứng dụng được triển khai tại:
🔗 https://minhn23.pythonanywhere.com

---

📸 Video demo: https://drive.google.com/file/d/1Sj7VP0OKGoCotxVs72rIoBPTtidPNs2n/view?usp=sharing

---

## ⚙️ Cài đặt (local)

```bash
# 1. Clone repository
git clone https://github.com/minh7709/learning_log.git
cd learning_log

# 2. Tạo virtual environment và cài đặt dependencies
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

# 3. Chạy migrate và khởi chạy server
python manage.py migrate
python manage.py runserver
---
