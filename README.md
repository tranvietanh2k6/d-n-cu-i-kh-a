# Dự Án Cuối Khóa: Responsive Web Design với CSS Media Queries

Chào mừng đến với dự án cuối khóa của tôi! Đây là một trang web được xây dựng nhằm mục đích thực hành thiết kế web đáp ứng (Responsive Web Design) và tối ưu hóa khả năng truy cập (Accessibility) bằng cách sử dụng CSS Media Queries.

## 🚀 Tính Năng Nổi Bật

Dự án đã đáp ứng đầy đủ 4 yêu cầu Media Queries từ bài tập:

1. **Kích thước màn hình từ 772px (`min-width: 772px`)**:
   - Lưới hình ảnh tự động chuyển sang 2 cột.
   - Hình ảnh được bo tròn (`border-radius: 50%`).
   - Hình ảnh cuối cùng trong lưới sẽ chiếm toàn bộ 2 cột (`grid-column: span 2`).

2. **Kích thước màn hình từ 992px (`min-width: 992px`)**:
   - Giữ nguyên lưới 2 cột.
   - Loại bỏ bo góc để hình ảnh trở thành hình vuông (`border-radius: 0`).
   - Mỗi hình ảnh thứ 3 (3, 6, 9...) sẽ chiếm toàn bộ 2 cột (`nth-child(3n)`).

3. **Hỗ trợ giảm chuyển động (`prefers-reduced-motion: reduce`)**:
   - Tự động tắt hiệu ứng cuộn mượt (`scroll-behavior: smooth`) khi nhấn nút "Jump to the Top" nếu người dùng thiết lập hệ điều hành giảm chuyển động. Giúp giảm khó chịu thị giác cho người dùng nhạy cảm.

4. **Hỗ trợ chế độ nền tối (`prefers-color-scheme: dark`)**:
   - Tự động chuyển đổi giao diện sang nền tối (màu nền `#121212`, chữ màu sáng) và đổi màu viền ảnh sang màu vàng để phù hợp và nổi bật hơn.

## 🛠 Công Nghệ Sử Dụng

- **HTML5**: Cấu trúc trang web ngữ nghĩa (Semantic HTML).
- **CSS3**: Sử dụng CSS Grid cho bố cục lưới và Media Queries cho thiết kế đáp ứng.

## 📁 Cấu Trúc Thư Mục

```text
├── css/
│   └── style.css       # Chứa toàn bộ mã CSS và Media Queries
├── images/             # Thư mục chứa các hình ảnh của dự án
├── index.html          # Trang HTML chính
└── README.md           # Tài liệu mô tả dự án
