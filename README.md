# GitHub New Project Practice

Bài thực hành tạo dự án mới trên GitHub.

## Mục tiêu

- Khởi tạo Local Repository bằng Git.
- Tạo Remote Repository trên GitHub.
- Kết nối Local Repository với Remote Repository.
- Thực hành git add, git commit và git push.

## Các câu lệnh đã sử dụng

### git init

Khởi tạo một Git Repository mới trong thư mục hiện tại.

### git branch -M main

Đổi tên nhánh hiện tại thành main.

### git remote add origin <URL>

Kết nối Local Repository với Remote Repository trên GitHub và đặt tên remote là origin.

### git add README.md

Đưa file README.md vào vùng staging để chuẩn bị commit.

### git commit -m "Add README.md file"

Tạo một commit lưu lại trạng thái của các file đã được đưa vào staging.

### git push -u origin main

Đẩy các commit từ nhánh main của Local Repository lên Remote Repository origin.

Tùy chọn -u thiết lập origin/main làm upstream cho nhánh main.

### git status

Kiểm tra trạng thái các file và repository hiện tại.

### git remote -v

Kiểm tra địa chỉ Remote Repository đang được liên kết.
