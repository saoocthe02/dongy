# Làm Bạn Gái Anh Nha?

Dự án này là một trang web tương tác dùng để tỏ tình. Mong bạn dùng code này như nguồn cảm hứng.
---
## Tôn Trọng Tinh Thần Mã Nguồn Mở
Tôi tạo ra dự án này với mục đích **giải trí & học hỏi**. Nếu bạn fork hoặc chỉnh sửa:  
✔ **Dùng cho mục đích sáng tạo, dự án cá nhân hoặc học tập**  
✔ **Ghi công đầy đủ khi sử dụng công khai**  
✔ **Tôn trọng công sức của tác giả gốc**  
 

## Cách Thức Hoạt Động

Trang web đơn giản gồm nút "Đồng Ý" và "Từ Chối". Khi nhấn nút "Từ Chối", văn bản trên nút sẽ thay đổi theo chuỗi tin nhắn định sẵn, đồng thời nút "Đồng Ý" sẽ to dần lên. Nếu nhấn nút "Đồng Ý", người dùng sẽ được chuyển hướng đến trang mới (`yes_page.html`).

### Điểm Nhấn:
- **Nút Tương Tác**: Nút "Từ Chối" hiển thị chuỗi tin nhắn, nút "Đồng Ý" phóng to dần
- **Thiết Kế Linh Hoạt**: Trang web hiển thị tốt trên mọi kích thước màn hình

---
## Hướng Dẫn Sử Dụng

1. **Tải Xuống Tệp Tin**:
   - Clone repository này hoặc tải xuống các tệp `index.html`, `styles.css`,`yes_style.css`,`yes_page.html` và `script.js`

2. **Mở Dự Án**:
   - Mở tệp `index.html` bằng trình duyệt web

---
## Tổng Quan Code 

### Các Tệp Chính:

- `index.html`: Tệp HTML chính định cấu trúc trang web
- `styles.css`: Tệp CSS tạo kiểu cho trang chính
- `script.js`: Tệp JavaScript xử lý tương tác nút bấm
- `yes_page.html`: Trang hiển thị khi đồng ý
- `yes_style.css`: CSS tạo kiểu cho trang đồng ý

### Chức Năng Chủ Chốt:

- `handleNoClick()`: Thay đổi văn bản nút "Từ Chối" và phóng to nút "Đồng Ý"
- `handleYesClick()`: Chuyển hướng người dùng đến `yes_page.html`

---
## Giấy Phép 📄

Dự án này được cấp phép theo MIT License - xem chi tiết tại [LICENSE](LICENSE)