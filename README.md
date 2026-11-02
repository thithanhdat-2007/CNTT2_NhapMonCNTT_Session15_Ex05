# Bài tập Session 15 – Ex05: Giao tiếp bất đồng bộ giữa các múi giờ

Họ và tên: Thi Thành Đạt  
MSSV: N26DTCN041  
Lớp: CNTT2  
Môn học: Nhập môn Công nghệ thông tin  
Email: thithanhdat111@gmail.com

## 1. Cách giao tiếp của nhóm

Nhóm có 3 người ở Hà Nội, 1 người ở Nhật Bản và 1 người ở Mỹ nên không thể mặc định ai cũng đang online cùng lúc. Em chọn Slack để trao đổi công việc. Mỗi yêu cầu cần ghi đầy đủ vấn đề, cách tái hiện, việc đã kiểm tra, người phụ trách và hạn phản hồi. Người nhận đọc và trả lời trong giờ làm việc của mình; chỉ sự cố thật sự khẩn cấp mới cần liên hệ ngay bằng cách nhóm đã thống nhất.

## 2. Tin nhắn mẫu nhờ hỗ trợ sửa lỗi

Đây là **tình huống giả định** để minh họa cách viết tin nhắn, không phải lỗi em đã kiểm tra trên một hệ thống thật:

> @người-phụ-trách-API, nhờ bạn kiểm tra lỗi đăng nhập trên môi trường thử nghiệm. Cách tái hiện: mở trang đăng nhập, nhập tài khoản thử nghiệm hợp lệ rồi bấm “Đăng nhập”. Kết quả thực tế là trang báo “Lỗi máy chủ” và yêu cầu `POST /api/login` trả mã `500`; kết quả mong đợi là vào được màn hình chính. Em đã tải lại trang và thử với một tài khoản thử nghiệm khác, nhưng lỗi vẫn xuất hiện. Nhờ bạn kiểm tra phía API và ghi nguyên nhân, cách xử lý vào thread này trước **17:00 ngày 03/11/2026 theo giờ Nhật Bản (JST)**. Bạn không cần trả lời ngay khi nhận tin; nếu cần thêm dữ liệu để tái hiện, hãy ghi rõ trong thread.

Tin nhắn trên đi thẳng vào câu hỏi, có đủ bối cảnh và hạn phản hồi. Nó tránh kiểu **No-Hello** như chỉ nhắn “Bạn ơi” rồi chờ người khác hỏi lại “Có chuyện gì?”.

## 3. Lịch gửi bằng Schedule Send

Với tin nhắn không khẩn cấp, em soạn trước trong đúng kênh hoặc tin nhắn trực tiếp, bấm mũi tên cạnh nút gửi của Slack, chọn **Schedule for later** và đặt giờ theo **giờ làm việc của người nhận**. Sau đó em kiểm tra lại trong mục **Scheduled**. Trước khi chọn giờ, em kiểm tra múi giờ hiển thị trong Slack của mình để không chọn nhầm giờ của người gửi thành giờ của người nhận.

- **Người ở Hà Nội:** hẹn gửi lúc **09:00 giờ Hà Nội (UTC+7)** của ngày làm việc phù hợp.
- **Người ở Nhật Bản:** hẹn gửi lúc **09:00 giờ Nhật Bản (JST, UTC+9)**; nếu người gửi đang dùng giờ Hà Nội thì chọn **07:00 giờ Hà Nội** cùng ngày.
- **Người ở Mỹ:** hẹn gửi lúc **09:00 theo giờ địa phương của bạn đó**. Đề không cho biết bang hoặc thành phố nên không thể đổi chính xác sang giờ Hà Nội; cần xác nhận múi giờ và giờ làm việc của bạn trước khi đặt lịch, đồng thời chú ý giờ mùa hè nếu nơi đó áp dụng.

Một thông báo chung gửi vào kênh sẽ xuất hiện cùng một thời điểm cho cả nhóm, nên khó bảo đảm cả ba khu vực đều đang thức. Em đăng thông báo chung **không tag cả nhóm**, ghi rõ hạn phản hồi kèm múi giờ; người ở nơi khác đọc khi bắt đầu ca làm. Nếu cần một người xử lý, em hẹn riêng tin nhắn hoặc tag đúng người vào buổi sáng của họ. Không thúc trả lời ngay và không dùng `@all` cho việc thường ngày.

Lịch trên là **phương án thiết kế** cho bài tập. Em chưa gửi hoặc đặt lịch tin nhắn thật trong Slack vì đề không cung cấp nhóm Slack và tài khoản của các thành viên.
