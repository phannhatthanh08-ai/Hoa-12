# Hệ Thống Ôn Tập Chinh Phục 9+ & Điểm 10 Hóa Học 12 – Kết Nối Tri Thức
> Trọn Bộ 8 Chương & Đề Cương Word — Bản Cập Nhật Mới Nhất (Version 4) Sẵn Sàng Triển Khai Vercel 🚀

---

## 🔒 Cam kết toàn vẹn dữ liệu (100% Nguyên bản)
Toàn bộ mã nguồn trang web được sao chép nguyên vẹn 1:1 từ file gốc:
`h_th_ng_n_t_p_chinh_ph_c_9_i_m_10_h_a_h_c_12_k_t_n_i_tri_th_c_tr_n_b_8_ch_ng_c_ng_word (4).html`

- **Mã kiểm tra tính toàn vẹn (SHA-256):**
  `3E4D38F9AB8B62A888DAA3C4C2EC13B1F96BFE7BC37CE273D5C82E5F187C8BAD`
- **Kích thước file:** `3,160,656 bytes`
- **Tuyệt đối không can thiệp, chỉnh sửa hay xóa bất kỳ dòng mã nào bên trong file HTML.** Tất cả tính năng, giao diện, dữ liệu trắc nghiệm, lý thuyết 8 chương và đề cương Word đều được giữ nguyên 100%.

---

## 📁 Cấu trúc thư mục dự án

```text
hoa12-chinh-phuc-9-10-vercel/
├── index.html                                                                                 # File giao diện chính phục vụ Vercel (bản sao 1:1 nguyên vẹn)
├── h_th_ng_n_t_p_chinh_ph_c_9_i_m_10_h_a_h_c_12_k_t_n_i_tri_th_c_tr_n_b_8_ch_ng_c_ng_word (4).html # Giữ nguyên tên gốc để đối chiếu & kiểm tra SHA-256
├── vercel.json                                                                                # Cấu hình routing, Clean URLs và Security Headers cho Vercel
├── package.json                                                                               # Thông tin dự án và script khởi chạy / deploy
├── .gitignore                                                                                 # Bỏ qua thư mục tạm / cache khi deploy
└── README.md                                                                                  # Hướng dẫn chi tiết các bước đưa lên Vercel
```

---

## 🚀 Các cách đưa lên Vercel để tạo Website

### Cách 1: Triển khai nhanh bằng Vercel CLI (Khuyên dùng)
1. Mở PowerShell hoặc Terminal tại thư mục này:
   ```bash
   cd "C:\Users\hp\.gemini\antigravity\scratch\hoa12-chinh-phuc-9-10-vercel"
   ```
2. Chạy lệnh deploy:
   ```bash
   npx vercel
   ```
3. Đăng nhập tài khoản Vercel (nếu được hỏi), nhấn `Enter` để chấp nhận các thiết lập mặc định:
   - `Set up and deploy?` ➜ Nhấn `Y`
   - `Which scope do you want to deploy to?` ➜ Chọn tài khoản của bạn
   - `Link to existing project?` ➜ Nhấn `N` (hoặc `Y` nếu muốn liên kết dự án cũ)
   - `What's your project's name?` ➜ Nhấn `Enter` để giữ tên mặc định
   - `In which directory is your code located?` ➜ Nhấn `Enter` (`./`)
4. Đưa lên môi trường Production chính thức (có link vĩnh viễn):
   ```bash
   npx vercel --prod
   ```
   Sau vài giây, bạn sẽ nhận được đường link web hoạt động 24/7 (dạng: `https://hoa-hoc-12-ket-noi-tri-thuc.vercel.app`).

---

### Cách 2: Triển khai qua GitHub (Tự động cập nhật)
1. Tạo một repository mới trên GitHub (ví dụ đặt tên: `hoa12-ket-noi-tri-thuc`).
2. Mở PowerShell tại thư mục này và đẩy code lên:
   ```bash
   git init
   git add .
   git commit -m "Deploy He thong on tap Hoa hoc 12 KNTT v4"
   git branch -M main
   git remote add origin https://github.com/<tai-khoan-github-cua-ban>/hoa12-ket-noi-tri-thuc.git
   git push -u origin main
   ```
3. Truy cập [vercel.com](https://vercel.com) > Đăng nhập > Nhấn nút **Add New...** > **Project**.
4. Chọn repository GitHub vừa tạo và bấm **Deploy**.
5. Vercel sẽ tự động build và cấp domain miễn phí tốc độ cao.

---

### Cách 3: Kéo thả file Zip hoặc thư mục lên Vercel Dashboard
- Bạn có thể dùng file nén `hoa12-chinh-phuc-9-10-vercel.zip` đã được đóng gói sẵn để kéo thả hoặc upload trực tiếp.

---

## 💻 Xem trước trên máy tính (Local Preview)
- Cách 1: Nhấp đúp chuột trực tiếp vào file `index.html` để mở bằng trình duyệt (Chrome, Edge, Cốc Cốc,...).
- Cách 2: Chạy máy chủ tĩnh local:
  ```bash
  npx serve .
  ```
  Sau đó truy cập địa chỉ `http://localhost:3000` trên trình duyệt.
