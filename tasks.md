# KẾ HOẠCH LÀM VIỆC - NHÓM 10
**Dự án:** Website Quản lý (Bài tập thực hành Git)
**Người lập kế hoạch:** Thành viên 4

---

## 1. MỤC TIÊU DỰ ÁN
- Xây dựng thành công workflow làm việc nhóm trên GitHub.
- Áp dụng đúng mô hình nhánh: Main, Develop, Feature.
- Hoàn thành chức năng cơ bản của website demo.

---

## 2. PHÂN CÔNG THÀNH VIÊN (ROLES)

| Thành viên | Vai trò (Role) | Nhiệm vụ chính |
| :--- | :--- | :--- |
| **Vinh Sơn** | Team Lead | Khởi tạo Repo, Setup nhánh Develop, Merge cuối cùng. |
| **Xuân Tài** | Developer | Code chức năng Frontend (Giao diện chính). |
| **Phước Thiện** | Developer | Code chức năng Backend (Xử lý dữ liệu). |
| **Đăng Khoa** | Reviewer/Planner | Lên kế hoạch (tasks.md), Review code (Pull Requests). |

---

## 3. LỘ TRÌNH THỰC HIỆN (TIMELINE)

### Giai đoạn 1: Khởi tạo (Tuần 1)
- [x] Tạo Repository trên GitHub.
- [x] Team Lead tạo nhánh `develop`.
- [x] Add thành viên vào dự án (Collaborators).
- [x] Mỗi thành viên clone source về máy.

### Giai đoạn 2: Phát triển tính năng (Tuần 2)
*(Quy tắc: Không commit thẳng lên main/develop, phải tạo nhánh feature riêng)*

#### Công việc cụ thể:
1. **Team Lead:**
   - Tạo cấu trúc thư mục dự án.
   - Setup file `README.md` giới thiệu nhóm.

2. **Developer (Tài & Thiện):**
   - Tạo nhánh `feature/frontend-home`: Thiết kế giao diện trang chủ.
   - Tạo nhánh `feature/backend-api`: Tạo API đăng nhập/đăng ký.
   - Commit code ít nhất 2 lần/người.

3. **Reviewer (Khoa):**
   - Tạo nhánh `feature/holedangkhoa`: Viết file `tasks.md`.
   - Theo dõi tiến độ Pull Request của nhóm.

### Giai đoạn 3: Review & Merge (Tuần 3)
- [ ] Các thành viên tạo Pull Request (PR) từ `feature` -> `develop`.
- [ ] **Reviewer** kiểm tra code (Convention, Logic) và Approve.
- [ ] **Team Lead** merge các nhánh vào `develop`.
- [ ] Xử lý xung đột (Conflict) nếu có.

### Giai đoạn 4: Hoàn thiện (Tuần 4)
- [ ] Kiểm tra toàn bộ dự án trên nhánh `develop`.
- [ ] Team Lead tạo PR từ `develop` -> `main`.
- [ ] Đóng gói và nộp bài.

---

## 4. QUY ƯỚC COMMIT (CONVENTION)
Áp dụng format: `<type>: <mô tả ngắn>`
- `feat`: Tính năng mới
- `fix`: Sửa lỗi
- `docs`: Tài liệu (tasks.md, readme)
- `style`: Chỉnh sửa format, giao diện