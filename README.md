Tester là người dùng thử phần mềm|website để tìm lỗi (bug) trước khi sản phẩm được giao cho khách hàng thật sự sử dụng.

Mục tiêu: Đảm bảo sản phẩm chạy đúng, mượt mà và dễ dùng.

Công việc của tester:

-Requirement: Tìm hiểu xem website|ứng dụng đó được làm ra để giải quyết việc gì.

-Test Case: Liệt kê sẵn danh sách các trường hợp cần kiểm tra (Ví dụ: Thử đăng nhập đúng tài khoản, thử đăng nhập sai mật khẩu...).

-Test Execution: Trực tiếp thao tác trên hệ thống theo kịch bản đã viết.

-Report Bug: Khi thấy hệ thống bị lỗi, chụp ảnh|quay video lại và gửi cho lập trình viên (Developer) sửa.

-Re-test: Sau khi Lập trình viên sửa xong, Tester bấm lại để xác nhận lỗi đã hết.

| Chức Năng | Các Bước Thực Hiện | Kết Quả Mong Đợi | Ưu Tiên | Trạng Thái |
| :---: | :--- | :--- | :---: | :---: |
| Đăng ký tài khoản | Nhập SĐT hợp lệ + Mật khẩu + Mã OTP | Tạo tài khoản thành công, nhận SMS OTP | Critical | `PASS` |
| Đăng nhập sai | Nhập sai Mật khẩu quá 5 lần | Khóa tài khoản tạm thời trong 15 phút | High | `PASS` |
| Tìm kiếm Bác sĩ | Nhập từ khóa *"Tim mạch"* vào thanh tìm kiếm | Trả về danh sách Bác sĩ thuộc chuyên khoa Tim mạch | High | `PASS` |
| Đặt lịch khám | Chọn Bác sĩ -> Chọn Giờ -> Bấm *"Đặt Lịch"* | Tạo lịch thành công, gửi mail/nhắn tin xác nhận | Critical | `PASS` |
| Chẩn đoán AI | Nhập danh sách triệu chứng (Sốt, ho, đau đầu) | AI phân tích và hiển thị gợi ý bệnh lý phù hợp | Critical | `PASS` |
