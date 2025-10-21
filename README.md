Mô tả ngắn gọn bài thực hành và trích dẫn nguồn AI
Phần 1: Cấu hình Phần cứng/Phần mềm với Hỗ trợ AI 
  Nhiệm vụ 1.1: Tìm hiểu cấu hình phần cứng
    - Mở trình duyệt, truy cập Google Bard.
    - Nhập prompt: “Giải thích thông số CPU, RAM, ổ cứng của máy tính Windows 10 và cách kiểm tra chúng.”
    - Dựa trên câu trả lời AI, sử dụng công cụ hệ thống (Task Manager trên Windows hoặc System Information) để kiểm tra thông số phần cứng của máy tính.
    - Ghi lại thông số (CPU model, RAM dung lượng, loại ổ cứng: HDD/SSD) vào file Word/Google Docs.
  Nhiệm vụ 1.2: Cấu hình phần mềm cơ bản
    - Truy cập Google Bard, nhập prompt: “Hướng dẫn chi tiết cài đặt Notepad++ trên Windows 10 và cấu hình để viết code Python.”
    - Làm theo hướng dẫn AI: 
    1.	Cài đặt Notepad++
      Bước 1: Tải file cài đặt
      -	Truy cập trang web chính thức của Notepad++: https://notepad-plus-plus.org/downloads/.
      -	Chọn phiên bản Installer (thường là 64-bit x64 cho Windows 10 hiện đại) và nhấn Download.
      -	Lưu file cài đặt (file .exe) vào một thư mục trên máy tính.
      Bước 2: Thực hiện cài đặt
      -	Nhấp đúp chuột vào file .exe vừa tải về.
      -	Chọn ngôn ngữ: Chọn ngôn ngữ bạn muốn sử dụng cho trình cài đặt (ví dụ: English) và nhấn OK.
      -	Hộp thoại Welcome: Nhấn Next.
      -	Thỏa thuận cấp phép: Đọc thỏa thuận và chọn I Agree.
      -	Chọn thư mục cài đặt: Để mặc định là ổn, nhấn Next.
      -	Chọn thành phần: Giữ nguyên các tùy chọn mặc định, nhấn Next.
      -	Tùy chọn: Nên đánh dấu vào ô "Create Shortcut on Desktop" để tạo biểu tượng truy cập nhanh. Nhấn Install.
   2.	 Cấu hình Notepad++ để chạy code Python: Để chạy code Python trực tiếp từ Notepad++, bạn cần cài thêm một Plugin có tên là NppExec.
      Bước 1: Cài đặt Plugin NppExec
      -	Mở Notepad++.
      -	Trên thanh Menu, chọn Plugins $\to$ Plugins Admin....
      -	Trong cửa sổ Plugins Admin, chuyển sang tab Available (Nếu chưa ở đó).
      -	Tìm kiếm (hoặc cuộn xuống) để tìm Plugin NppExec.
      -	Đánh dấu vào ô NppExec.
      -	Nhấn nút Install ở góc trên bên phải.
      -	Notepad++ sẽ yêu cầu khởi động lại để hoàn tất cài đặt Plugin. Nhấn Yes.
      Bước 2: Thiết lập lệnh chạy Python
      -	Trên thanh Menu, chọn Plugin -> NppExec -> Execute... (hoặc nhấn phím tắt F6).
      -	Trong hộp thoại Execute, nhập chính xác hai dòng lệnh sau: NPP_SAVE và python"$(FULL_CURRENT_PATH)"
      -	Nhấn nút Save....
      -	Trong cửa sổ Save As, đặt tên cho Script này (ví dụ: Run_Python) và nhấn OK.
      -	Bây giờ, bạn có thể nhấn OK (hoặc Cancel) để đóng hộp thoại Execute.
      Bước 3: Gán phím tắt cho lệnh Run_Python 
      -	Trên thanh Menu, chọn Settings $\to$ Shortcut Mapper....
      -	Chọn tab Plugin commands.
      -	Cuộn xuống tìm tên Script bạn đã lưu (Run_Python).
      -	Chọn lệnh đó, rồi nhấn nút Modify.
      -	Trong hộp thoại Shortcut, chọn một tổ hợp phím tắt dễ nhớ (ví dụ: Ctrl + F5) và nhấn OK. (Đảm bảo tổ hợp phím này không bị trùng với lệnh khác).
      -	Đóng cửa sổ Shortcut Mapper.
*Trích dẫn nguồn AI: https://gemini.google.com/ *
Phần 2: Giải quyết Sự cố Kỹ thuật Đơn giản với AI
  Nhiệm vụ 2.1: Xử lý sự cố kết nối Wi-Fi:  Sử dụng AI để tìm cách khắc phục sự cố Wi-Fi mất kết nối trên Windows 10. Mở Google Bard nhập prompt: “Cách khắc phục lỗi Wi-Fi không kết nối trên Windows 10.” và thực thiện theo các bước AI đề xuất sau:
    - Kiểm tra cơ bản
      Bật Wi-Fi
      Kiểm tra router
      Xem Phạm vi tín hiệu
      Kiểm tra trên thiết bị khác
    - Cập nhật hoặc cài lại driver Wi-Fi
      Nhấn Windows + X, chọn Device Manager.
      Mở rộng mục Network adapters, tìm adapter Wi-Fi (thường có từ "Wireless" hoặc tên hãng như Intel, Realtek).
     Nhấp chuột phải, chọn Update driver > Search automatically for drivers.
      Nếu không hoạt động, chọn Uninstall device, sau đó khởi động lại máy để Windows tự cài lại driver.
      Nếu vẫn không được, tải driver mới nhất từ trang web của hãng sản xuất laptop hoặc adapter Wi-Fi (Intel, Broadcom, Realtek...).
    - Ghi lại các bước đã thực hiện và kết quả (kết nối thành công hay không) vào Google Docs.
    - Chụp ảnh màn hình trạng thái Wi-Fi sau khi khắc phục.
  Nhiệm vụ 2.2: Xử lý lỗi phần mềm cơ bản: Sử dụng AI để khắc phục lỗi “Notepad++ không mở được file Python lớn”. 
  Mô tả các bước thực hiện:
  - Nhập prompt vào Google Bard: “Cách khắc phục lỗi Notepad++ không mở được file Python lớn trên Windows.”
  - Thực hiện giải pháp AI đề xuất (ví dụ: tăng bộ nhớ cache, chuyển sang trình soạn thảo khác như VS Code).
  - Thử mở một file Python lớn (>1MB, tải mẫu từ GitHub nếu cần).
  - Ghi lại kết quả (thành công/thất bại) và giải pháp vào file văn bản.
Phần 3: Ứng dụng AI trong Học tập
  Nhiệm vụ 3.1: Tạo nội dung học tập với Canva AI: Sử dụng Canva AI để tạo infographic về một chủ đề công nghệ số (ví dụ: “Ứng dụng AI trong CNTT”).
 Hướng dẫn thực hiện:
   - Truy cập Canva, chọn “Create a design” → “Infographic”.
   - Sử dụng tính năng AI (Magic Design): Nhập prompt “Tạo infographic về ứng dụng AI trong công nghệ thông tin”.
   - Chỉnh sửa infographic: Thêm văn bản, hình ảnh từ nguồn miễn phí (Unsplash tích hợp trong Canva).
   - Xuất file PNG và ghi chú: “Infographic được tạo bằng Canva AI” trong mô tả.
   - Đẩy file PNG lên GitHub với giấy phép Creative Commons (CC BY).
  Nhiệm vụ 3.2: Đánh giá đạo đức khi sử dụng AI: Phân tích cách sử dụng AI trong nhiệm vụ 3.1 theo nguyên tắc đạo đức.
Hướng dẫn thực hiện:
 - Nghiên cứu [2] DigComp 2.2 về đạo đức số (hoặc tài liệu [7] Google, 2025).
 - Viết đoạn văn ngắn (100-150 từ) trả lời câu hỏi: “Làm thế nào để sử dụng Canva AI một cách minh bạch và đạo đức?”
 - Gợi ý: Ghi nguồn AI, không sử dụng nội dung để lan truyền thông tin sai lệch, kiểm tra bản quyền hình ảnh.
 - Lưu đoạn văn vào file Word và đẩy lên GitHub cùng với infographic.
===
