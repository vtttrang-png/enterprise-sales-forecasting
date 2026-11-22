# Hệ thống Dự báo Doanh số Doanh nghiệp (Enterprise Sales Forecasting)

## 1. Giới thiệu đề tài
Dự án xây dựng mô hình học máy (Machine Learning) nhằm dự báo doanh số bán hàng theo chuỗi thời gian cho doanh nghiệp bán lẻ, hỗ trợ bộ phận quản trị tối ưu hóa tồn kho và hoạch định ngân sách.

## 2. Mục tiêu nghiên cứu
* Tiền xử lý và phân tích dữ liệu bán hàng lịch sử.
* Xây dựng và so sánh hiệu năng giữa các thuật toán dự báo (ARIMA, Prophet, XGBoost).
* Đề xuất quy trình tích hợp mô hình dự báo vào hệ thống thông tin quản lý (MIS).

## 3. Phương pháp thực hiện
* **Ngôn ngữ & Công cụ:** Python, Pandas, Scikit-learn.
* **Đánh giá mô hình:** Sử dụng các chỉ số RMSE (Root Mean Squared Error) và MAPE (Mean Absolute Percentage Error).

## 4. Cấu trúc thư mục
* `data/`: Chứa tập dữ liệu bán hàng mẫu.
* `src/`: Chứa mã nguồn xử lý dữ liệu và huấn luyện mô hình.
* `docs/`: Chứa tài liệu phân tích thiết kế hệ thống.
* `results/`: Chứa biểu đồ trực quan hóa và bảng kết quả đánh giá.

## 5. Kết quả bước đầu
Mô hình XGBoost đạt độ chính xác cao nhất với chỉ số sai số MAPE giảm 12.5% so với phương pháp trung bình trượt truyền thống.

## 6. Bản quyền (License)
Dự án này được phát hành dưới giấy phép **MIT License**. Xem chi tiết tại tệp [LICENSE](./LICENSE).
