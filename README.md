# Mini-project 1: Trang HTML Chuẩn Đầu Tiên

Dự án này trình bày cấu trúc tài liệu HTML tiêu chuẩn, giải thích ý nghĩa các thẻ cốt lõi và tổ chức quản lý mã nguồn bài bản trên GitHub.

## 📁 Cấu Trúc Thư Mục Dự Án
- `index.html`: Chứa cấu trúc layout và nội dung bài học.
- `css/style.css`: File thiết kế giao diện, phân định các khu vực trực quan.
- `js/script.js`: Xử lý các tương tác cơ bản.
- `assets/`: Thư mục lưu trữ hình ảnh thiết kế giao diện.

## 📸 Ảnh Chụp Thiết Kế UI / Giao Diện Page
Dưới đây là ảnh chụp thiết kế layout giao diện của trang web:

![Thiết Kế Giao Diện UI](assets/ui-design.png)

## 🗺️ Mô Tả Phân Vùng HTML Theo Ảnh Thiết Kế
Dựa trên ảnh chụp thiết kế UI ở trên, cấu trúc mã nguồn trong file `index.html` được phân chia thành các vùng (Semantic HTML) rõ ràng như sau:

1. **Vùng Đầu Trang (`<header>` và `<nav>`)**: Tương ứng với thanh biểu ngữ màu tối phía trên cùng, chứa tên trang web "HTML Learning Lab", thông tin học viên và các nút chức năng điều hướng.
2. **Vùng Tiêu Điểm/Giới Thiệu (`<section class="hero">`)**: Vùng màu xanh đen làm nổi bật tên bài học "Mini-project 1: Trang HTML chuẩn đầu tiên" và yêu cầu đề bài.
3. **Bố Cục Nội Dung Chính (Main Layout Split)**: Được chia làm 2 cột chính:
   - **Cột Trái (`<main>`)**: Vùng chiếm diện tích lớn nhất, dùng để viết code và hiển thị chi tiết nội dung giải thích các thẻ cốt lõi gồm `DOCTYPE`, `html`, `head`, `body`.
   - **Cột Phải (`<aside>`)**: Thanh bên chứa các hộp thông tin bổ trợ, lưu ý học tập và danh sách "Tiến trình thời gian".
4. **Vùng Chân Trang (`<footer>`)**: Nằm ở dưới cùng của giao diện, hiển thị thông tin bản quyền và liên kết nguồn.
