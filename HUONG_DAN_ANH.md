# Hướng Dẫn Sử Dụng Ảnh Cá Nhân

## 📸 Thêm Ảnh của Bạn Vào Portfolio

Portfolio của bạn hiện đang sử dụng hình ảnh SVG placeholder (avatar.svg). Để thay thế bằng ảnh thực tế của bạn, hãy làm theo các bước sau:

### Bước 1: Chuẩn bị Ảnh
1. Chuẩn bị ảnh của bạn (ảnh đã được cung cấp: avatar.jpg hoặc tương tự)
2. Đặt tên ảnh là: `avatar.jpg` hoặc `avatar.png`
3. Kích thước khuyên dùng: 300x300px hoặc 400x400px
4. Định dạng: JPG hoặc PNG

### Bước 2: Lưu Ảnh Vào Thư Mục
- Copy ảnh của bạn vào thư mục: `d:\quangvinh\images\`
- Đặt tên file: `avatar.jpg` (hoặc `.png`)

### Bước 3: Cập Nhật Code
Mở file `index.html` tìm dòng:
```html
<img src="images/avatar.svg" alt="Bùi Quang Vinh - Cybersecurity Specialist" style="width: 100%; height: 100%; object-fit: contain;">
```

Thay thành:
```html
<img src="images/avatar.jpg" alt="Bùi Quang Vinh - Cybersecurity Specialist" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
```

### Bước 4: Cập Nhật Các Bài Blog
Tương tự, trong các file blog (`blog/blog-posts/*.html`), thay:
```html
<img src="../../images/avatar.svg" alt="..." style="...">
```

Thành:
```html
<img src="../../images/avatar.jpg" alt="..." style="...">
```

---

## ✅ Các File Đã Được Cập Nhật

### Trang Chủ (index.html)
- ✅ Phần hero section đã sẵn sàng cho ảnh
- ✅ Avatar container đã được tối ưu cho ảnh thực tế

### Bài Viết Blog
Tất cả 8 bài viết đã được thêm ảnh placeholder:
1. ✅ `xdr-explained.html` - XDR
2. ✅ `networking-basics.html` - Networking
3. ✅ `n8n-automation.html` - n8n
4. ✅ `splunk-siem.html` - Splunk
5. ✅ `python-security.html` - Python
6. ✅ `soc-building.html` - SOC
7. ✅ `firewall-ids.html` - Firewall
8. ✅ `cryptography.html` - Cryptography

---

## 🎨 CSS Styles Cho Ảnh

Các style đã được tối ưu cho ảnh cá nhân:

```css
/* Cho ảnh trong trang chủ (hero section) */
.avatar-container {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    box-shadow: 0 0 50px rgba(0, 212, 255, 0.3);
}

/* Cho ảnh trong các bài blog */
img {
    width: 100%;
    max-width: 400px;
    height: auto;
    margin: 2rem 0;
    border-radius: 8px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}
```

---

## 📝 Ghi Chú Quan Trọng

1. **Định dạng ảnh:** JPG hoặc PNG
2. **Kích thước:** Tối thiểu 300x300px, tối ưu 400x400px hoặc hơn
3. **Chất lượng:** Ảnh chân dung, nền trắng hoặc gradient
4. **Đường dẫn:** Luôn dùng `/images/avatar.jpg` (từ thư mục gốc)

---

## 🚀 Kế Tiếp

Sau khi thêm ảnh của bạn:
1. Test portfolio trên các trình duyệt khác nhau
2. Kiểm tra responsive design trên mobile
3. Tối ưu hóa kích thước ảnh để tải nhanh hơn
4. Xem xét thêm ảnh cho các projects/achievements

Chúc bạn thành công! 🎉
