# Hướng Dẫn Phát Hành Lên GitHub Pages

## Bước 1: Khởi tạo Git Repository

Mở terminal và chạy các lệnh sau:

```bash
cd /Users/huynguyen/Codegym
git init
git add .
git commit -m "Initial commit: Truyện xuyên không thầy Huy"
```

## Bước 2: Tạo Repository trên GitHub

1. Truy cập https://github.com và đăng nhập
2. Nhấn vào nút "+" ở góc trên bên phải, chọn "New repository"
3. Đặt tên repository (ví dụ: `xuyen-khong-code`)
4. Chọn "Public" để có thể sử dụng GitHub Pages miễn phí
5. **KHÔNG** tích vào "Initialize this repository with a README"
6. Nhấn "Create repository"

## Bước 3: Kết nối Local Repository với GitHub

Thay `YOUR_USERNAME` và `REPO_NAME` bằng thông tin của bạn:

```bash
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
git branch -M main
git push -u origin main
```

## Bước 4: Kích hoạt GitHub Pages

1. Vào repository vừa tạo trên GitHub
2. Nhấn vào tab **Settings** (ở menu trên cùng)
3. Cuộn xuống phần **Pages** ở menu bên trái
4. Trong phần **Source**, chọn:
   - Branch: `main`
   - Folder: `/ (root)`
5. Nhấn **Save**

## Bước 5: Truy cập Website

Sau vài phút, GitHub sẽ tự động deploy website của bạn. Truy cập tại:

```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

**Lưu ý:** 
- Có thể mất vài phút để GitHub Pages hoạt động lần đầu
- Nếu bạn đổi tên repository, URL cũng sẽ thay đổi
- Mỗi lần push code mới, GitHub sẽ tự động cập nhật website

## Cập nhật Nội dung

Khi muốn cập nhật nội dung, chỉ cần:

```bash
git add .
git commit -m "Update: Thêm nội dung mới"
git push
```

GitHub Pages sẽ tự động cập nhật sau vài phút!

## Tùy Chỉnh URL

Nếu muốn sử dụng domain riêng, bạn có thể:
1. Mua domain từ các nhà cung cấp như Namecheap, GoDaddy...
2. Vào Settings > Pages > Custom domain
3. Nhập domain của bạn và làm theo hướng dẫn

---

**Chúc bạn thành công! 🚀**

