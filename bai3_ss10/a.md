# Bài 3: Giảm chi phí vận hành Chatbox
## Phần 1. Phân tích bài toán:
- **Vì sao Makdown giúp AI xử lý nhanh hơn HTML là**: cú pháp của Makdown rất tối giản, sử dụng các kí tự cực kì ngắn gọn để định dạng cấu trúc. Trong khi HTML thì phải dùng các cặp thẻ mở và đóng rườm rà. Việc sử dụng HTML rất nhiều kí tự thì sẽ tốn nhiều token hơn sử dụng Makdown vì đã tối giản kí tự. Và viễ sử dụng HTML thì AI phải phân tích cú pháp trước khi hiểu nội dung thật sự .
## Phần 2. So sánh và đánh giá: 
### Bảng so sánh đánh giá Makdown và HTML.
| Tiêu chí | Markdown | HTML |
| :--- | :--- | :--- |
| **Cú pháp** | Ngắn gọn, tối giản (sử dụng các ký tự ký hiệu). | Dài dòng, nhiều thẻ mở và đóng. |
| **Số lượng Token (Dung lượng)** | **Thấp**, ít tốn kém chi phí gọi API. | **Cao**, tốn nhiều token hơn cho cùng một nội dung. |
| **Tốc độ xử lý của AI** | **Nhanh hơn** do ít token thừa và ít nhiễu cấu trúc. | **Chậm hơn** do mô hình mất thời gian phân tích cú pháp HTML. |
| **Tính "Human-readable"** | **Rất cao**, dễ đọc, dễ viết và dễ chỉnh sửa ngay cả ở dạng mã nguồn thô. | **Thấp hơn**, khó đọc hơn đối với con người khi nhìn vào mã nguồn thuần túy chưa render. |
| **Khả năng hiển thị/Trực quan** | Được hỗ trợ rộng rãi trên các nền tảng tài liệu, chat, GitHub. | Chuyên dụng cho trình duyệt web, hiển thị phong phú nhưng quá nặng cho LLM. |
### Giải pháp tối ưu cho hệ thống "Greentech":
- Sử dụng Makdown làm định dạng chuẩn cho dữ liệu giao tiếp và ngữ cảnh truyền vào AI. 
- Tiết kiệm chi phí với hệ thống phục vụ hàng ngàn nồng dân mỗi ngày cắt giảm được các token rác khi sử dụng HTML. 
- Trải nghiệm mượt mà và tốc độ phản hồi nhanh chóng. 
