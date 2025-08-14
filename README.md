# 🚗 Hệ Thống Nhận Diện Biển Số Xe Máy

Đồ án tốt nghiệp này là một dự án về một hệ thống nhận diện biển số xe máy sử dụng Python, OpenCV, YOLO và Deep Learning.  
Chương trình có giao diện trực quan cho phép đăng nhập và nhận diện biển số từ hình ảnh hoặc camera.

---

## 📌 Tính năng
- Giao diện đăng nhập cho người dùng.
- Tải ảnh hoặc sử dụng camera để nhận diện biển số.
- Xử lý ảnh gốc, ảnh xám, tách biển số và nhận dạng ký tự.
- Hiển thị kết quả nhận dạng và các ký tự đã phát hiện.

---

## 📷 Giao diện minh họa

### Màn hình đăng nhập
<img width="1920" height="1022" alt="image" src="https://github.com/user-attachments/assets/5919d05d-2b3e-4770-b4f4-053877fbab1b" />


### Màn hình nhận diện biển số
<img width="1053" height="1007" alt="image" src="https://github.com/user-attachments/assets/07a783c2-2eb3-4c3d-8a64-8893fa3208ed" />


---

## 📂 Cấu trúc thư mục

```
.
├── assets/                  # Lưu hình ảnh giao diện, icon, ...
├── data/                    # Dữ liệu huấn luyện
├── icons/                   # Icon giao diện
├── output/                  # Kết quả nhận diện
├── weights/                 # Trọng số mô hình
├── app.py                   # Chạy ứng dụng chính
├── giaodiendn.py            # Giao diện đăng nhập
├── number_classifier.py     # Mô hình nhận dạng ký tự
├── inception.py             # Mô hình xử lý đặc trưng
├── utils.py                 # Hàm hỗ trợ xử lý ảnh
├── requirements.txt         # Thư viện cần cài đặt
└── README.md
```

---

## 🚀 Cài đặt và chạy
1. **Clone dự án**
```bash
git clone https://github.com/pvkhanh/NDBSX-DATN.git
cd NDBSX-DATN
```

2. **Tạo môi trường ảo và cài đặt thư viện**
```bash
python -m venv .venv
source .venv/bin/activate   # Nếu dùng Linux/Mac
.venv\Scripts\activate      # Nếu dùng Windows
pip install -r requirements.txt
```

3. **Chạy ứng dụng**
```bash
python app.py
```

---

## 🛠 Công nghệ sử dụng
- Python 3.x
- OpenCV
- YOLO
- CNN
- Gradio
- PyQt5
- PyTorch / TensorFlow (tùy vào mô hình bạn dùng)
- Tkinter / PyQt5 (cho giao diện)
- Git LFS (lưu trữ file trọng số lớn)

---
## 🔒 Quyền truy cập mã nguồn
Mã nguồn **không công khai**.  
Nếu bạn muốn truy cập code đầy đủ, vui lòng liên hệ qua:

📧 Email: `pvkhanh.tech@gmail.com`  
✍ **Tác giả:** [pvkhanh](https://github.com/pvkhanh)  

> Sau khi nhận được yêu cầu, chúng tôi sẽ xem xét và cấp quyền vào **repo private**.

📅 **Năm:** 2025
