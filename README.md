# Zalo Data Mover Pro 🚀
<img width="980" height="852" alt="image" src="https://github.com/user-attachments/assets/bf81a0ab-f38f-423f-bade-8d409a728e32" />


**Zalo Data Mover Pro** là công cụ tối ưu hóa không gian lưu trữ và quản lý dữ liệu Zalo an toàn, thông minh. Công cụ giúp bạn di chuyển hàng trăm GB dữ liệu Zalo từ ổ C sang các ổ đĩa khác (D, E...) mà không làm gián đoạn hay ảnh hưởng đến ứng dụng Zalo, đặc biệt hữu ích khi ổ C của bạn bị đầy.

---

## 🌟 Tính Năng Nổi Bật

- ⚡ **Tối Ưu Tự Động (AI)**: Sử dụng Robocopy phân tích cấu trúc CPU để tự động chia luồng (từ 8-32 luồng) giúp copy siêu tốc hàng trăm GB mà không gây treo máy.
- 🛡️ **Bảo Toàn Quyền Phân Cấp**: Giữ nguyên 100% thuộc tính Timestamps & Security gốc của từng file, folder, đảm bảo không bị lỗi mã hóa tin nhắn.
- 🔨 **Đóng Băng Tiến Trình**: Tự động nhận diện và Force Kill ngầm toàn bộ background services của Zalo trước khi chạy, tránh tuyệt đối lỗi khóa file hệ thống.
- 🔄 **Khởi Tạo Liên Kết (Junction)**: Cắm ống nối Low-level Link đánh lừa Zalo hoạt động trơn tru, Zalo vẫn tin rằng nó đang đọc dữ liệu từ ổ C.
- 🧹 **Quản Lý Rác Thông Minh**: Dọn dẹp an toàn các file `.old` rác, khôi phục ngay lập tức không gian lưu trữ khổng lồ cho ổ C.
- 🎯 **Tự Động Định Tuyến**: Nhận diện thông minh thư mục thật, lọc bỏ thư mục ảo, hỗ trợ linh hoạt mọi thiết lập ổ đĩa cục bộ.
- 🔐 **An Toàn Tuyệt Đối**: Không can thiệp mã nguồn ứng dụng, loại bỏ rủi ro mất dữ liệu Zalo.
- 👥 **Đăng Nhập Đa Zalo**: Tạo phân vùng lưu trữ data ảo riêng biệt trên ổ đĩa đích (ổ D, E...), tự động tạo Shortcut Desktop mở nhiều nick độc lập, không nhấp nháy cửa sổ đen CMD.
- 🩺 **Phục Hồi Link (Restore)**: Auto-Scan siêu việt! Bỏ qua copy, tự động quét và nối lại thư mục gốc chỉ trong 1 giây (Vô cùng tiện lợi khi Cài lại Windows).

---

## 🚀 2 Chức Năng Chính (Giao Diện Dạng Tab)

1. **Tab 1: Di Chuyển Dữ Liệu**:
   - **Clone**: Sao chép toàn bộ dữ liệu an toàn sang ổ đích, đổi tên thư mục gốc thành `.old` làm backup dự phòng.
   - **Move**: Di chuyển dữ liệu sang ổ đĩa đích và xóa vĩnh viễn thư mục gốc ở ổ C để giải phóng ngay lập tức dung lượng.
   - **Restore**: Tự động quét và nối lại thư mục gốc chỉ trong 1 giây khi cài lại Windows.
2. **Tab 2: Đăng Nhập Đa Zalo**:
   - Quét và quản lý danh sách các tài khoản Zalo Clone đang lưu trên ổ đĩa đích.
   - **Tạo mới tài khoản clone** với phân vùng dữ liệu riêng, tự động đặt shortcut ra Desktop.
   - **Khởi chạy nhanh** tài khoản bất kỳ trực tiếp từ giao diện tool hoặc bằng cách click đúp shortcut.
   - **Tự động sửa lỗi & phục hồi** liên kết Junction và shortcut của toàn bộ tài khoản clone chỉ trong 1 giây sau khi cài lại Windows.

---

## 💻 Hướng Dẫn Sử Dụng

### Chức năng 1: Di chuyển dữ liệu để dọn ổ C
1. **Bước 1**: Mở phần mềm `ZaloMove` (Chạy dưới quyền Administrator).
2. **Bước 2**: Tại Tab **Di Chuyển Dữ Liệu**, chọn **Đường dẫn đích** (Ví dụ: `D:\Zalo`).
3. **Bước 3**: Chọn các thư mục cần di chuyển và chế độ sao lưu mong muốn (Clone / Move / Restore).
4. **Bước 4**: Bấm **Bắt Đầu Chuyển Dữ Liệu**.

### Chức năng 2: Tạo và quản lý Zalo Đa Tài Khoản
1. **Bước 1**: Chọn **Đường dẫn đích** ở Tab 1 để làm nơi lưu trữ dữ liệu đa tài khoản (Ví dụ: `D:\Zalo`).
2. **Bước 2**: Chuyển sang Tab **Đăng Nhập Đa Zalo**.
3. **Bước 3**: Nhập tên tài khoản phụ (không dấu, ví dụ: `CongViec`, `GiaDinh`) và bấm **Tạo Mới** (hoặc ấn Enter).
4. **Bước 4**: Click đúp vào tài khoản trong danh sách (hoặc Shortcut ngoài Desktop) để mở Zalo đăng nhập nick mới.

---

## 🔐 Cam Kết An Toàn
- **Zalo Data Mover Pro** hoàn toàn KHÔNG can thiệp vào mã nguồn Zalo.
- KHÔNG yêu cầu tài khoản, mật khẩu hay đọc lén dữ liệu tin nhắn.
- Cơ chế xử lý hoàn toàn dựa trên các tập lệnh hệ thống chuẩn cấp thấp của Windows (Robocopy & Mklink).

---
*© Bản quyền thuộc về **HOMITA** | Hotline Zalo: **0906 988 186***
