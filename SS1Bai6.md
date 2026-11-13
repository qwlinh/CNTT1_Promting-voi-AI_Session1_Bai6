# Bài 6: Phân tích cơ chế "Tràn cốc ngữ cảnh" (Truncation) trong luồng tư vấn CSKH

**Phần 1:** Giải thích hình tượng Chiếc cốc nước:  

- Chiếc cốc nước gioongs như bộ nhớ ngắn hạn cuả AI; 

- Ở lượt 1: thông tin mà Anh B và mã đơn MTX-9988 được đưa vòa đầu điên, sau nhiều lần chat thì chiếc cốc ấy đầy 100%. Khi cố gắng thêm thông tin vào thì nhẽng thông tin ở lượt 1 sẻ bị đẩy ra ngoài. Đến lượt 42 thì AI không còn luuw tông tin về anh B và mã đơn dẫn đến việc hỏi ngược lại tên và mã đơn

**Phần 2**   Đề xuất 2 phương án (thao tác người dùng & thiết kế hệ thống) để luồng tư vấn không bị tràn cốc.

1: Phương án 1

Nên mở đoạn chat mới giống như khi bàn xong một vấn đề nào đó thì chúng ta nên tách luồng mới 

2: Phương án 2

Khi xử dụng AI thì ta nên lưu đoạn thông tin cần thiết vào database để mỗi khi gữi tin nhắn thì hệ thống sẻ kẹp ngầm thông tin đó vào cuối cùng