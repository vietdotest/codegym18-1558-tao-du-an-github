# Tạo dự án mới trên GitHub

Bài thực hành 1558 — khóa 18, CodeGym.

## Mục tiêu
Khởi tạo kho mã cục bộ, kết nối kho từ xa và đồng bộ các commit.

## Các lệnh Git
- `git init`: khởi tạo repository cục bộ.
- `git remote add origin <URL>`: gắn remote GitHub với tên origin.
- `git add README.md`: đưa nội dung vào staging area.
- `git commit -m "Add README"`: lưu một phiên bản vào lịch sử cục bộ.
- `git push -u origin <branch>`: đưa commit lên GitHub và thiết lập nhánh theo dõi.
- `git status`: kiểm tra tệp thay đổi và trạng thái staging.
- `git log --oneline`: xem lịch sử commit.
- `git fetch`: lấy thông tin remote mà chưa gộp vào nhánh làm việc.
- `git pull`: lấy và tích hợp thay đổi từ remote.

## Kiểm tra
Đối chiếu SHA commit cục bộ với SHA nhánh từ xa bằng `git ls-remote`.
Đọc README trực tiếp trên GitHub sau khi đẩy để xác nhận nội dung.

## Tài liệu
[Đề bài CodeGym](https://internship.codegym.vn/learning/18/activity/1558)

Repository dành riêng cho bài này, không chứa tệp cá nhân hoặc thông tin đăng nhập.
