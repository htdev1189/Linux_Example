# Hướng dẫn VIM cơ bản

### Mở file
> vi file.txt
> ### Muốn chỉnh sửa thì ấn phím I để insert
> ### Muốn vào chế độ cmd thì ấn phím ESC sau đó  : + lệnh_thực_thi

### Lệnh thực thi
> :q! --> Thoát ra ngoài không lưu

> :wq --> Lưu file và thoát

> :/key -> Tìm kiếm trong file (Ấn n để trỏ tới kết quả tiếp theo)

> :set paste -> nếu muốn paste nội dung từ ngoài vào file

> :set number (Sau đó :Number) để nhảy tới dòng được xác định

> :$ -> Nhảy tới dòng cuối cùng

### Một số tổ hợp phím thao tác cơ bản trong chế dộ bình thường
> dd -> xóa dòng hiện tại con trỏ đang đứng

> u -> thực hiện undo lại tác vụ trước đó

### Copy văn bản trong cùng 1 file
- ấn ESC để trở về chế độ bình thường
- Ấn phím v, sau đó dùng mũi tên để chọn vùng text cần copy
- Ấn phím y để xác nhận
- Ấn phím o để tạo dòng mới, sau đó ESC để thoát khỏi insert model
- Ấn phím p để paste vào
