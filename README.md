# Student Manager

Ứng dụng quản lý sinh viên — DevOps Lab 5: Quản lý mã nguồn với Git Flow và Code Review trên GitHub.

**Version 1.0.0** — Phát triển bởi Nhóm A & Nhóm B.

## Thông tin nhóm

- Nhóm: DIEN_SO_NHOM
- Lớp: DIEN_TEN_LOP

Vai trò

Dev A | Nguyễn Văn Nghiệp
Dev B DTC235180135 

## Repository

https://github.com/minhnghiep2k5-blip/devops-lab5-student-manager

## Tính năng

- Quản lý thông tin sinh viên bằng lớp `Student`, gồm mã sinh viên, họ tên, tuổi và khóa.
- Chuyển thông tin sinh viên thành dictionary bằng `to_dict()`.
- Thêm sinh viên mới bằng `add_student()`.
- Kiểm tra trùng mã trước khi thêm sinh viên.
- Tìm kiếm theo tên hoặc mã sinh viên bằng `search_student()`.
- Tìm kiếm không phân biệt chữ hoa và chữ thường.
- Hiển thị danh sách và tổng số sinh viên.

## Công nghệ sử dụng

- Python 3.
- Git và GitHub.
- Visual Studio Code.

## Cài đặt và chạy

### Yêu cầu

- Python 3.
- Git từ phiên bản 2.40 trở lên.

Chương trình không cần cài thêm thư viện Python bên ngoài.

### Tải mã nguồn

```bash
git clone https://github.com/minhnghiep2k5-blip/devops-lab5-student-manager.git
cd devops-lab5-student-manager
```

### Chạy chương trình

Tại thư mục gốc dự án:

```bash
python src/main.py
```

### Kết quả mong đợi

- Khởi tạo 3 sinh viên mẫu: SV001, SV002 và SV003.
- Thêm thành công SV004 — Pham Thi D.
- Hiển thị tổng cộng 4 sinh viên.
- Tìm kiếm từ khóa `Van` trả về 2 sinh viên:
  - Nguyen Van A.
  - Le Van C.

## Thực hành merge conflict

Hai nhánh README thay đổi cùng một vị trí với nội dung khác nhau.

Nhánh B được merge vào `develop` trước. Khi merge nhánh A vào `develop`, Git phát hiện conflict trong `README.md`.

Conflict được giải quyết bằng cách kết hợp nội dung thành:

**Version 1.0.0** — Phát triển bởi Nhóm A & Nhóm B.

Sau đó thực hiện `git add`, `git commit` và `git push` để lưu kết quả.

## Minh chứng bài thực hành

Thư mục `screenshots` trong bài nộp gồm:

| Tên ảnh | Nội dung |
|---|---|
| `01-git-log.png` | Lịch sử commit dạng đồ thị |
| `02-git-branch.png` | Danh sách nhánh trước khi dọn dẹp |
| `03-pr-add-student.png` | Pull Request thêm sinh viên đã merge |
| `04-pr-search-student.png` | Pull Request tìm kiếm sinh viên đã merge |
| `05-code-review.png` | Nhận xét và review chéo |
| `06-merge-conflict.png` | Trạng thái conflict trong VS Code |
| `07-conflict-resolved.png` | Kết quả giải quyết conflict |
| `08-final-output.png` | Kết quả chạy chương trình hoàn chỉnh |