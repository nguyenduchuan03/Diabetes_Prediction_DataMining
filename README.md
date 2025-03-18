Dự đoán bệnh tiểu đường bằng thuật toán FreeSpan

📌 Giới thiệu

Dự án này sử dụng thuật toán FreeSpan & Apriori để khai phá dữ liệu bệnh nhân tiểu đường, giúp phát hiện các mẫu tuần tự quan trọng nhằm hỗ trợ dự báo nguy cơ mắc bệnh.

🚀 Công nghệ sử dụng

Ngôn ngữ: Python

Thư viện: pandas, NumPy, scikit-learn, Matplotlib, Seaborn

Thuật toán: FreeSpan, Apriori, Decision Tree

📊 Quy trình thực hiện

Tiền xử lý dữ liệu: Làm sạch, chuẩn hóa dữ liệu bệnh nhân.

Áp dụng thuật toán Data Mining:

FreeSpan để tìm các mẫu tuần tự phổ biến.

Apriori để xác định các luật kết hợp giữa các yếu tố nguy cơ.

Đánh giá và trực quan hóa kết quả:

Vẽ biểu đồ tần suất các mẫu tuần tự phổ biến.

Tính toán ma trận lift để đánh giá mức độ liên quan giữa các yếu tố nguy cơ.

📁 Cấu trúc thư mục

Diabetes_Prediction_DataMining/
│── data/                    # Dữ liệu (CSV, JSON,...)
│── notebooks/               # File Jupyter Notebook (.ipynb)
│── reports/                 # Báo cáo dự án
│── README.md                # Giới thiệu dự án

📌 Kết quả

Phát hiện được các mẫu tuần tự giúp dự báo nguy cơ mắc bệnh.

Trực quan hóa kết quả bằng biểu đồ & ma trận lift.

So sánh FreeSpan với các thuật toán FP-Growth, LSTM, Random Forest.

📌 Hướng phát triển

Mở rộng dữ liệu để kiểm tra độ chính xác của mô hình.

Kết hợp với Machine Learning (LSTM, Random Forest) để nâng cao độ chính xác.

Ứng dụng vào hệ thống hỗ trợ ra quyết định trong y tế.

📎 Tài nguyên & Liên kết

📄 Báo cáo chi tiết: Link file Word

📊 Dữ liệu mẫu: Dataset.csv

📂 Mã nguồn trên GitHub: Repo GitHub
