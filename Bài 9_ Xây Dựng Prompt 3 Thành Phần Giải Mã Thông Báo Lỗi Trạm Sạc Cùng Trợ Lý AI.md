# PHẦN 1: THIẾT KẾ PROMPT 3 THÀNH PHẦN

1. Vì sao câu hỏi ban đầu khiến AI trả lời sai?

-   Câu hỏi quá ngắn, thiếu tên phần mềm, hệ điều hành và mã lỗi.
    
-   AI thiếu thông tin nên dễ suy đoán sai (Hallucination), dẫn đến hướng dẫn không đúng nguyên nhân.
- # PHẦN 2: GIẢI MÃ LỖI VÀ KHẮC PHỤC

3. Dịch và giải thích lỗi

Lỗi có nghĩa là phần mềm không được cấp quyền truy cập và ghi file `session.log` trong thư mục `Program Files`.

Nguyên nhân: Tài khoản chạy phần mềm chưa có quyền ghi dữ liệu.

4. Ba bước khắc phục

1.  Nhấn chuột phải vào VoltCharge Controller, chọn Run as administrator.
    
2.  Vào Properties → Security của thư mục `data`, cấp quyền Modify cho đúng tài khoản chạy phần mềm.
    
3.  Mở lại phần mềm, kiểm tra nhật ký và trạng thái trạm sạc.
    

5. Xử lý API Key

-   Xóa hoặc thay mã bí mật bằng `[REDACTED]` trước khi gửi AI.
    
-   Không chia sẻ API Key, mật khẩu hoặc mã OTP.
    
-   Nếu đã lộ mã thật, cần thu hồi và tạo mã mới.
