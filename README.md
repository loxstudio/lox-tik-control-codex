# LOX TIK CONTROL

**Bản Lite hiện tại: [0.2.33 — tải bộ cài chính thức](https://github.com/loxstudio/lox-tik-control-codex/releases/tag/v0.2.33).**

Bản mới sửa luồng khách kết nối LIVE nhưng chưa nhận hiệu ứng, hiển thị rõ quyền nhận tương tác và tự thử lại khi xác minh tạm gián đoạn. Máy Owner được phép test cùng khách trên một Idol; quy tắc bản quyền giữa các khách hàng vẫn giữ nguyên. Stage tự co cửa sổ theo màn hình khi chọn độ phân giải lớn, tích hợp Gallery và sửa phục hồi Mascot; đồng thời cải thiện đăng ký bản quyền lần đầu. Giữ các tính năng và bản sửa đã có ở 0.2.32.

Mã ứng dụng và runtime khớp bản đã qua 116 nhóm kiểm thử hồi quy. Bộ cài chính thức đã kiểm tra riêng về nội dung, khởi động và cấu hình cập nhật. Phát hành theo yêu cầu chủ dự án để tiếp tục test trên máy khách; nghiệm thu LIVE thực tế vẫn đang chờ. Không coi các kiểm thử tự động là kết quả nghiệm thu LIVE.

## Cập nhật

Trong app, chọn **Kiểm tra bản mới** hoặc [tải bộ cài 0.2.33](https://github.com/loxstudio/lox-tik-control-codex/releases/download/v0.2.33/LOX-TIK-CONTROL-Lite-Setup-0.2.33.exe).

**Dừng LIVE/ghi hình, hoàn tất hàng chờ và lưu các thay đổi trước khi cập nhật.** App giữ cơ chế xác nhận an toàn trước khi cài. Không cần gỡ app hoặc xóa dữ liệu/bản quyền hiện có.

Nếu bản cũ tải xong nhưng không cài được: dừng LIVE, thoát LOX rồi chạy bộ cài ở liên kết trên.

**Gallery hiện nằm trong cửa sổ Stage.** Nguồn Gallery cũ trong OBS sẽ trống sau refresh; hãy thu cửa sổ Stage. Khung nội dung 4K co vừa cửa sổ nhỏ không đồng nghĩa OBS đang thu cửa sổ ở 4K.

Với Lite 0.2.6–0.2.14, nếu không tải được cập nhật:

1. Tải [công cụ sửa cập nhật một lần](https://github.com/loxstudio/lox-tik-control-codex/releases/download/v0.2.15/LOX-Sua-cap-nhat.zip) và giải nén.
2. Dừng LIVE, thoát LOX, chạy `LOX-Sua-cap-nhat.cmd`. Nếu được hỏi, chọn `LOX TIK CONTROL.exe` đã cài.
3. Mở lại LOX và chọn **Kiểm tra bản mới**.

Có thể cài trực tiếp bản mới thay cho bước sửa một lần.

Bộ cài dùng danh tính chính thức, chưa ký chứng chỉ Windows. Không yêu cầu tắt bảo vệ Windows. Quà chưa được gán trong preset vẫn cần người vận hành chọn hiệu ứng mong muốn; bản cập nhật không tự phát bù quà cũ.

Kho này chứa bộ cài và hướng dẫn, không chứa mã nguồn riêng tư. Kênh Lite nhận cập nhật từ máy chủ LOX; nhãn Latest của kho công khai được giữ riêng cho bản cũ dùng kênh GitHub.
