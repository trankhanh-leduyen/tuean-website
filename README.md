[README_DEPLOY.md](https://github.com/user-attachments/files/21821269/README_DEPLOY.md)
# TueAn Website (GitHub Pages)

Đây là source code đã sẵn sàng chạy trên **GitHub Pages**.

## Cách triển khai (5–7 phút)

1) Tạo repo mới trên GitHub (Public) tên: `tuean-website`  
   - Link tạo nhanh: https://github.com/new
   - Tích “Add a README file” (không bắt buộc).

2) Tải các file trong gói này lên repo:  
   - Vào repo → **Add file → Upload files** → kéo thả toàn bộ file trong `.zip`.
   - Nhấn **Commit changes**.

3) Bật GitHub Pages:  
   - Repo → **Settings → Pages**  
   - **Source: Branch = `main`**, **Folder = `/ (root)`** → **Save**.  
   - Đợi 1–2 phút, truy cập link dạng:  
     `https://<your-username>.github.io/tuean-website/`

**Với tài khoản của bạn:**  
`https://trankhanh-leduyen.github.io/tuean-website/`

## Thay ảnh thật
- Đổi 3 file ảnh theo đúng tên trong `index.html`:  
  - `denhoacuoi.jpg` (ảnh trang chủ)  
  - `z6915709612083_19abe15d6b13a0007568296217639cfa.jpg`  
  - `d.jpg`
- Nếu muốn đổi tên file, nhớ sửa lại đường dẫn trong HTML.

## Chỉnh sửa nội dung
- Mở `index.html` trực tiếp trên GitHub → **Edit** → sửa text → **Commit**.  
- Web tự cập nhật sau vài chục giây.

## Domain miễn phí (tuỳ chọn)
- Bạn đã có sẵn **link miễn phí** của GitHub Pages như trên.  
- Nếu muốn dùng tên miền riêng, sau khi mua/đăng ký domain:
  - Tạo bản ghi DNS `CNAME` → trỏ tới: `trankhanh-leduyen.github.io`
  - Trong repo, tạo file `CNAME` chứa tên miền của bạn, ví dụ: `www.tuean.vn`
