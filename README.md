# Mẫu Hình Học Phần

## Giới thiệu
Dự án này thực hiện một hệ thống quản lý học phần dựa trên kiến trúc microservices. Mỗi dịch vụ sẽ xử lý một phần chức năng của hệ thống tổng thể, bao gồm quản lý sinh viên, quản lý giảng viên và quản lý khóa học.

## Các thành phần chính
- **Sinh viên Service**: Quản lý thông tin sinh viên, đăng ký học phần và theo dõi điểm số.
- **Giảng viên Service**: Quản lý thông tin giảng viên và phân công công việc.
- **Khóa học Service**: Quản lý danh sách học phần, thời gian và lịch của từng khóa học.

## Công nghệ sử dụng
- Node.js cho backend.
- MongoDB cho cơ sở dữ liệu.
- Docker để đóng gói các dịch vụ.
- React cho giao diện người dùng.

## Cài đặt
```bash
# Tải về dự án
git clone https://github.com/yourusername/mau-hinh-hoc-phan.git

# Di chuyển vào thư mục dự án
cd mau-hinh-hoc-phan

# Chạy docker compose
docker-compose up
```

## Cách sử dụng
- Truy cập vào trang chủ để xem tổng quan hệ thống.
- Đăng nhập với tài khoản quản trị để quản lý dữ liệu.

## Đóng góp
Nếu bạn muốn đóng góp vào dự án, hãy mở issue hoặc gửi pull request.

## Giấy phép
Dự án này được cấp phép theo Giấy phép MIT.
