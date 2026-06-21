# Spam Email Detection System

## System Description
Đây là hệ thống học máy tự động phân loại và phát hiện email rác (Spam). Hệ thống trích xuất đặc trưng từ văn bản email để dự đoán xem email đó là thư bình thường (Ham) hay thư rác (Spam). Quá trình phát triển đi từ việc tiền xử lý dữ liệu thô, xây dựng mô hình cơ sở (Base model), cho tới việc tinh chỉnh và tìm kiếm siêu tham số (Hyperparameter tuning) để đạt độ chính xác tối đa.

## Key Features
- **Tiền xử lý & Khám phá dữ liệu:** Làm sạch văn bản, loại bỏ nhiễu và chuyển hóa ngôn ngữ tự nhiên thành dữ liệu định lượng.
- **Tối ưu hóa siêu tham số (Hyperparameter Search Tools):** Sử dụng các thuật toán tối ưu (như GridSearch, RandomizedSearch) để tinh chỉnh hiệu suất mô hình tự động.
- **Ứng dụng nhận diện trực tiếp (App):** Tích hợp giao diện kiểm thử trực tiếp, cho phép người dùng dán nội dung email vào và nhận kết quả phân loại tức thì.

## Tech Stack
- **Ngôn ngữ lập trình:** Python
- **Môi trường phát triển:** Jupyter Notebook
- **Deep Learning:** :LSTM
- **Data Processing:** Pandas, NumPy
- **Giao diện ứng dụng:** Streamlit (Triển khai trong app.ipynb)