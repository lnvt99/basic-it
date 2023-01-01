# DRIFT: Do it right the first time
# Estimate thời gian task
- Estimate chính xác thời gian thực hiện task là một việc rất khó
- Khi anh em dev bị giới hạn thời điểm deadline và liên tục bị giục hoàn thành việc estimate, mọi người sẽ khó có thể nhìn nhận các yếu tố phức tạp của bài toán để estimate, và sẽ estimate theo kiểu *cố gắng làm hài lòng người quản lý là chính* .
- Các yếu tố nhìn vào khi estimate time cho 1 task:
    + Thuật toán
    + Review code
    + Unit test (UT)
    + Review UT
- Cách để estimate time cho task gồm 4 bước:
    + Bước 1: Phân bổ thời gian dành cho việc estimate (30 phút - 1 tiếng 30 phút)
    + Bước 2: Chia nhỏ task thành các sub-task
    + Bước 3: Phân loại task: 
        - Known task: Biết rõ input - process - output
        - Partially known task:  Mới chỉ nắm được input, output và nắm được sơ bộ cách làm, ước lượng sẽ mất chừng 15-30 phút để tìm hiểu thêm hoặc cần thêm sự trợ giúp 
        - Unknown task: Dành khoảng vài giờ tới cả ngày để hiểu công nghệ mà bạn sẽ định sử dụng để hoàn thành task
    + Bước 4: Estimate lại
# NOTE
- Khi DEV không có đủ thời gian để xem xét độ phức tạp của task, họ sẽ đánh giá thấp độ phức tạp và dẫn đến estimate sai.
- Thà làm lâu mà tính năng hoạt động ổn định, còn hơn làm vội mà sau đấy phải mất rất nhiều thời gian để fixbug.
- Đừng bỏ qua những task lặt vặt: Checkbug, Fixbug, Review code, Build App, Deploy App.

# Quy trình estimate
    - Bước 1: Nhận và nhớ requirement task từ meeting, document, PM hay leader
    - Bước 2: Đọc và phân tích (từng dòng từng chữ, chậm mà chắc) 
    - Bước 3: Note lại những điểm cần chú ý + hướng giải quyết + technical (business logic)
    - Bước 4: Chia sub-task + estimate cho từng subtask
    - Bước 5: Tham khảo về technical, logic về những người đã giải quyết
    - Bước 5: Đọc và phân tích lại lần nữa (rà lại từng dòng một) + QnA 
    - Bước 6: Tổng hợp lại, xem dự án đã có ai làm chưa + coi lại toàn bộ những bước trên + technical + suy nghĩ hướng giải quyết
    - Bước 7: Estimate subtask lần nữa => Estimate task dựa trên các yếu tố phụ như là review + fix bug + UT