# 📱 PhoneShop - Website Bán Điện Thoại

Hệ thống website bán hàng điện thoại với 3 giao diện: **Khách hàng**, **Nhân viên**, và **Admin**.

## 🎯 Tính năng

### 👥 Khách hàng
- ✅ Trang chủ với banner, sản phẩm nổi bật, Flash Sale
- ✅ Danh sách sản phẩm với bộ lọc (hãng, giá, RAM, dung lượng)
- ✅ Chi tiết sản phẩm (hình ảnh, thông số kỹ thuật, đánh giá)
- ✅ Giỏ hàng (thêm, sửa, xóa sản phẩm)
- ✅ Thanh toán (COD, chuyển khoản, MoMo, thẻ, trả góp 0%)
- ✅ Tài khoản cá nhân (thông tin, lịch sử đơn hàng, yêu thích, đánh giá)
- ✅ Responsive design (mobile, tablet, desktop)

### 👨‍💼 Nhân viên
- ✅ Dashboard tổng quan (thống kê đơn hàng, doanh số)
- ✅ Quản lý đơn hàng (xác nhận, hủy, cập nhật trạng thái)
- ✅ Quản lý sản phẩm (cập nhật thông tin, tồn kho)
- ✅ Quản lý khách hàng (xem thông tin, hỗ trợ)
- ✅ Báo cáo - Thống kê (doanh thu, sản phẩm bán chạy)
- ✅ Hỗ trợ khách hàng (chat trực tuyến)

### 🔐 Admin
- ✅ Dashboard tổng hợp (doanh thu, đơn hàng, khách hàng, sản phẩm)
- ✅ Quản lý tài khoản (Admin, Nhân viên, Khách hàng)
- ✅ Quản lý sản phẩm CRUD (thêm, sửa, xóa, import)
- ✅ Quản lý danh mục & thương hiệu
- ✅ Quản lý đơn hàng tổng hợp
- ✅ Quản lý khuyến mãi & mã giảm giá
- ✅ Quản lý phản hồi khách hàng
- ✅ Báo cáo tổng hợp (doanh thu, lượng truy cập, phân tích)
- ✅ Sao lưu & khôi phục dữ liệu
- ✅ Cài đặt hệ thống

## 📂 Cấu trúc thư mục

```
phone-shop/
├── index.html                 # Trang chủ khách hàng
├── products.html              # Danh sách sản phẩm
├── product-detail.html        # Chi tiết sản phẩm
├── cart.html                  # Giỏ hàng
├── checkout.html              # Thanh toán
├── account.html               # Tài khoản khách hàng
├── staff-dashboard.html       # Dashboard nhân viên
├── admin-dashboard.html       # Dashboard admin
├── css/
│   └── style.css              # CSS chính (52KB)
├── js/
│   └── main.js                # JavaScript chính (17KB)
└── README.md                  # Tài liệu hướng dẫn
```

## 🚀 Cách sử dụng

### 1. Mở trực tiếp trên trình duyệt
```bash
# Mở file index.html bằng trình duyệt
# Hoặc double-click vào file index.html
```

### 2. Sử dụng Live Server (VS Code)
```bash
# Cài đặt extension "Live Server" trong VS Code
# Click phải vào index.html -> Open with Live Server
```

### 3. Upload lên host free

#### ✅ **GitHub Pages** (Khuyên dùng)
```bash
1. Tạo repository mới trên GitHub
2. Upload toàn bộ thư mục phone-shop
3. Vào Settings > Pages > chọn branch main
4. Website của bạn: https://username.github.io/phone-shop/
```

#### ✅ **Netlify** (Deploy tự động)
```bash
1. Truy cập https://www.netlify.com/
2. Kéo thả thư mục phone-shop vào Netlify
3. Website tự động deploy trong vài giây
```

#### ✅ **Vercel** (Nhanh và miễn phí)
```bash
1. Truy cập https://vercel.com/
2. Import project từ GitHub hoặc upload trực tiếp
3. Deploy tự động
```

#### ✅ **Firebase Hosting**
```bash
1. Truy cập https://firebase.google.com/
2. Tạo project mới
3. Upload và deploy qua Firebase CLI
```

## 🎨 Thiết kế

- **Màu chủ đạo**: Đỏ (#D70018) - Lấy cảm hứng từ CellphoneS
- **Font chữ**: Inter, Roboto
- **Icons**: Font Awesome 6 (CDN)
- **Framework**: HTML5, CSS3, JavaScript ES6+
- **Responsive**: Mobile-first design

## 📋 Danh sách trang

### Khách hàng (Customer)
- [x] Trang chủ (index.html)
- [x] Danh sách sản phẩm (products.html)
- [x] Chi tiết sản phẩm (product-detail.html)
- [x] Giỏ hàng (cart.html)
- [x] Thanh toán (checkout.html)
- [x] Tài khoản (account.html)

### Nhân viên (Staff)
- [x] Dashboard nhân viên (staff-dashboard.html)
  - Tổng quan
  - Quản lý đơn hàng
  - Quản lý sản phẩm
  - Quản lý khách hàng
  - Báo cáo - Thống kê
  - Hỗ trợ khách hàng

### Admin
- [x] Dashboard admin (admin-dashboard.html)
  - Dashboard tổng quan
  - Quản lý tài khoản
  - Quản lý sản phẩm
  - Quản lý danh mục & thương hiệu
  - Quản lý đơn hàng
  - Quản lý khuyến mãi
  - Quản lý phản hồi
  - Báo cáo tổng hợp
  - Phân tích dữ liệu
  - Sao lưu & khôi phục
  - Cài đặt hệ thống

## 🔧 Tính năng JavaScript

- ✅ **LocalStorage**: Lưu giỏ hàng và wishlist
- ✅ **Toast Notification**: Thông báo thao tác
- ✅ **Product Tabs**: Chuyển đổi tab sản phẩm
- ✅ **Account Menu**: Menu tài khoản
- ✅ **Dashboard Navigation**: Điều hướng dashboard
- ✅ **Add to Cart**: Thêm vào giỏ hàng
- ✅ **Wishlist**: Danh sách yêu thích
- ✅ **Thumbnail Gallery**: Gallery hình ảnh
- ✅ **Quantity Selector**: Chọn số lượng
- ✅ **Product Options**: Chọn màu sắc, dung lượng
- ✅ **Form Validation**: Kiểm tra form
- ✅ **Countdown Timer**: Đếm ngược Flash Sale

## 📱 Responsive Breakpoints

- **Desktop**: > 1200px
- **Laptop**: 992px - 1200px
- **Tablet**: 768px - 992px
- **Mobile**: < 768px

## 🌐 Tương thích trình duyệt

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📝 Ghi chú

### Điểm mạnh
- ✅ Frontend thuần (HTML/CSS/JS) - không cần backend
- ✅ Responsive 100% trên mọi thiết bị
- ✅ UI/UX đẹp, hiện đại, giống CellphoneS
- ✅ Có đầy đủ 3 giao diện: Khách hàng, Nhân viên, Admin
- ✅ LocalStorage để demo dữ liệu
- ✅ Dễ dàng upload lên host free
- ✅ Kích thước nhỏ gọn (~70KB total)

### Hạn chế
- ⚠️ Chỉ là demo frontend - không có backend thật
- ⚠️ Dữ liệu lưu trong LocalStorage (bị xóa khi clear cache)
- ⚠️ Không có xác thực người dùng thật
- ⚠️ Không có thanh toán thật
- ⚠️ Biểu đồ chỉ là placeholder (cần thêm Chart.js để có biểu đồ thật)

### Để tích hợp backend
```javascript
// Trong file main.js, bạn có thể thay đổi:
// LocalStorage -> API calls

// Ví dụ:
async function addToCart(product) {
    const response = await fetch('/api/cart', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(product)
    });
    return response.json();
}
```

## 🎓 Hướng dẫn mở rộng

### Thêm biểu đồ thật (Chart.js)
```html
<!-- Thêm vào <head> -->
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

<!-- Trong main.js -->
const ctx = document.getElementById('myChart');
new Chart(ctx, {
    type: 'line',
    data: {...},
    options: {...}
});
```

### Thêm thanh toán thật (Stripe/PayPal)
```html
<!-- Thêm Stripe SDK -->
<script src="https://js.stripe.com/v3/"></script>
```

### Thêm tìm kiếm thật (Algolia)
```html
<!-- Thêm Algolia SDK -->
<script src="https://cdn.jsdelivr.net/npm/algoliasearch@4"></script>
```

## 📞 Liên hệ & Hỗ trợ

- 🌐 Website: Đang phát triển
- 📧 Email: contact@phoneshop.com
- 📱 Hotline: 1800.xxxx

## 📄 License

MIT License - Tự do sử dụng cho mục đích học tập và thương mại.

---

**Developed with ❤️ by PhoneShop Team**

🚀 **Chúc bạn thành công!**