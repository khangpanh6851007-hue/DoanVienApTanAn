# Chi Đoàn Ấp Tân An - Cổng Thông Tin Điện Tử

Hệ thống quản lý đoàn viên thanh niên của **Chi Đoàn Ấp Tân An**, Xã Tân Thành Bình, Tỉnh Vĩnh Long. Dự án được thiết kế tối ưu hóa hoàn toàn cho thiết bị di động, chạy trực tiếp trên các trình soạn thảo code di động như **Acode** hoặc **Trebedit** và sẵn sàng triển khai lên **GitHub Pages**.

## 🌟 Tính Năng Nổi Bật

- **Hệ thống Auth 5.0**: Hỗ trợ tính năng Đăng nhập và Đăng ký tài khoản nhanh chóng dành cho đoàn viên.
- **Phân quyền Bí Thư**: Chỉ tài khoản Bí Thư chính thức mới có quyền thêm, sửa, xóa danh sách đoàn viên. Các tài khoản thành viên khác chỉ có quyền tra cứu thông tin.
- **Lưu trữ LocalStorage**: Dữ liệu được lưu trữ trực tiếp trên trình duyệt, hoạt động ổn định mà không cần cơ sở dữ liệu phức tạp.
- **Giao diện chuẩn Đoàn Thanh Niên**: Gam màu đỏ cờ thắm kết hợp vàng hoàng yến, bố cục tối ưu trực quan cho màn hình smartphone.

## 🔐 Tài Khoản Quản Trị (Bí Thư)

Sử dụng tài khoản hệ thống mặc định để kiểm tra toàn bộ quyền hạn quản trị viên:
- **Tài khoản:** `*********
- **Mật khẩu:** `********`

## 📱 Hướng Dẫn Sử Dụng & Triển Khai

### Chạy trực tiếp trên điện thoại (Acode / Trebedit)
1. Mở ứng dụng **Acode** hoặc **Trebedit** trên thiết bị Android của bạn.
2. Tạo file mới đặt tên là `index.html`.
3. Dán toàn bộ mã nguồn website vào file và lưu lại.
4. Chọn chế độ xem trước (Preview) để trải nghiệm giao diện ngay trên điện thoại.

### Đưa lên GitHub & Kích hoạt GitHub Pages
1. Tạo một repository mới trên GitHub (Ví dụ: `chi-doan-tan-an`).
2. Tải file `index.html` lên nhánh chính (`main`).
3. Vào phần **Settings** của repository $\rightarrow$ chọn **Pages**.
4. Tại mục **Build and deployment**, chọn nguồn phát hành là **Deploy from a branch** (`main` / `root`).
5. Nhấn **Save** và nhận đường link website công khai sau vài phút.

## 🛠️ Công Nghệ Sử Dụng
- **HTML5 / CSS3**: Thiết kế giao diện tương thích đa thiết bị (Responsive).
- **Vanilla JavaScript**: Xử lý logic xác thực tài khoản, phân quyền động và quản lý state.
- **Web Storage API**: Lưu trữ danh sách đoàn viên và tài khoản người dùng an toàn tại phía client.

## 📄 Thông Tin Dự Án
Phát triển năm 2026 phục vụ công tác Đoàn và phong trào thanh thiếu nhi tại Ấp Tân An, Xã Tân Thành Bình, Tỉnh Vĩnh Long.
