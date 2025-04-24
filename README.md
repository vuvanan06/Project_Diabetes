## Phân tích Dữ liệu dự đoán người bị Bệnh Tiểu Đường
### Mô tả dự án
Phân tích tập dữ liệu bệnh tiểu đường để xác định mối quan hệ giữa các yếu tố lâm sàng và nguy cơ mắc bệnh, đồng thời xây dựng mô hình dự đoán.
### A. MÔ TẢ TẬP DỮ LIỆU 
Tập dữ liệu Data_Diabetes.csv bao gồm  kết quả xét nghiệm bệnh tiểu đường của 723 
bệnh nhân toàn bộ là nữ giới. Mỗi bản ghi tương ứng với một bệnh nhân, bao gồm 9 thuộc 
tính: 
1. Pregnancies: Số lần mang thai 
2. Glucose: Chỉ số Gluco  
3. BloodPressur: Huyết áp (đơn vị: mm Hg) 
4. SkinThickness: Mức độ dày da (đơn vị: mm) 
5. Insulin: Chỉ số Insulin (đơn vị: mu U/ml) 
6. BMI: Chỉ số BMI của cơ thể (được tính bằng = Cân nặng / chiều cao2) 
7. DiabetesPedigreeFunction: Chức năng phả hệ của bệnh tiểu đường 
8. Age: Tuổi 
9. Outcome: Thuộc tính cho biết bệnh nhân có mắc bệnh tiểu đường hay không?  
Không bị tiểu đường (0) – Bị tiểu đường (1)

### B. Công việc thực hiện:
Làm sạch dữ liệu, xử lý giá trị thiếu và chuẩn hóa các thuộc tính.

Trực quan hóa dữ liệu để phân tích mối quan hệ giữa các biến.

Xây dựng mô hình phân loại bằng thuật toán K-Nearest Neighbors (KNN).

Sử dụng thư viện Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.

### C. Kết quả đạt được:
Mô hình KNN đạt độ chính xác 81.23%, giúp dự đoán khả năng mắc bệnh tiểu đường hiệu quả

